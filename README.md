BƯỚC 1: 5 thành phần HTTT và Dữ liệu vs Thông tin
1. Năm thành phần HTTT
Thành phần HTTT	Ví dụ thực tế tại RikkeiStay	Vai trò cơ bản
1. Phần cứng (Hardware)	Máy Kiosk tự làm thủ tục tại sảnh, khóa cửa từ thông minh	Thiết bị vật lý cấp thẻ phòng và nhận diện
2. Phần mềm (Software)	Phần mềm quản trị khách sạn PMS, ứng dụng di động RikkeiStay	Quản lý đặt phòng, sơ đồ buồng phòng và thanh toán
3. Dữ liệu (Data)	Trạng thái phòng (Trống/Đã đặt/Đang dọn), thông tin hộ chiếu khách	Dữ liệu lưu trú và phục vụ
4. Con người (People)	Du khách lưu trú và nhân viên lễ tân	Người sử dụng, vận hành và quản lý hệ thống
5. Quy trình (Process)	Quy trình nhận phòng: xác nhận đặt phòng → xác thực khách → nhận phòng → cấp thẻ → cập nhật trạng thái phòng	Đảm bảo quá trình phục vụ khách diễn ra đúng trình tự
2. Dữ liệu vs Thông tin
STT	Nội dung	Data	Information	Lý do
1	302	X		Chuỗi số thô, chưa rõ là số phòng, số tiền hay mã khách
2	Phòng Deluxe 302 đã được dọn sạch và sẵn sàng đón khách lúc 13:30		X	Có đầy đủ ngữ cảnh: loại phòng, số phòng, trạng thái và thời gian
3	VIP2025	X		Chuỗi ký tự thô, chưa rõ là mã voucher hay hạng thẻ khách hàng
4	Tỷ lệ lấp đầy phòng trong kỳ nghỉ lễ 30/04 đạt 98% trên toàn hệ thống		X	Dữ liệu đã được tổng hợp và có ngữ cảnh về thời gian, phạm vi và tỷ lệ lấp đầy
5	KH05, John Smith, UK, 3 đêm	X		Các trường dữ liệu thô về mã khách, tên, quốc gia và thời gian lưu trú, chưa thể hiện nhận định tổng hợp
Đáp án ô trống
Câu 4: Information [X]
Câu 5: Data [X]
BƯỚC 2: Môi trường và Stakeholders
1. Phân loại môi trường
Yếu tố khảo sát	Thuộc loại môi trường	Tầm ảnh hưởng đến hệ thống
Trình độ ngoại ngữ và kỹ năng tin học của nhân viên lễ tân	Môi trường Nội bộ	Phần mềm cần hỗ trợ đa ngôn ngữ và thao tác đơn giản, nhanh chóng để giảm sai sót
Quy định khai báo tạm trú cho khách quốc tế của Công an địa phương	Môi trường Bên ngoài	Hệ thống phải hỗ trợ thu thập và gửi dữ liệu lưu trú theo quy định
Sự cạnh tranh về giá và dịch vụ từ các nền tảng OTA quốc tế	Môi trường Bên ngoài	Thúc đẩy hệ thống đồng bộ lịch phòng, giá và khuyến mãi để cạnh tranh và tránh overbooking
Thói quen sử dụng thanh toán không tiền mặt của du khách quốc tế	Môi trường Bên ngoài	Hệ thống cần hỗ trợ nhiều phương thức thanh toán điện tử và thanh toán quốc tế
Chất lượng hệ thống mạng Wi-Fi phủ sóng tại từng tầng khách sạn	Môi trường Nội bộ	Mạng yếu có thể làm Kiosk, ứng dụng nhân viên và hệ thống quản lý phản hồi chậm hoặc gián đoạn

Lưu ý: Hai dòng cuối có thể gây nhầm. Theo cách phân loại của bài này, Wi-Fi của chính khách sạn là yếu tố nội bộ, vì RikkeiStay có thể kiểm soát và đầu tư nâng cấp hạ tầng mạng.

2. Stakeholder – Quản lý buồng phòng
Nhóm Stakeholder	Vai trò trong dự án	Mối quan tâm lớn nhất đối với phần mềm
1. Khách lưu trú (Guest)	Người sử dụng dịch vụ	Nhận phòng nhanh chóng tại Kiosk không phải xếp hàng chờ đợi
2. Nhân viên Lễ tân (Front Desk)	Người trực quầy tiếp đón	Nắm rõ trạng thái từng phòng trên sơ đồ trực quan theo thời gian thực
3. Quản lý buồng phòng (Housekeeping)	Quản lý và phân công công việc dọn phòng, kiểm tra tình trạng phòng	Theo dõi trạng thái phòng theo thời gian thực, phân công nhân viên và đảm bảo phòng được dọn đúng hạn
BƯỚC 3: Kỹ thuật thu thập yêu cầu
1. Chọn kỹ thuật phù hợp
STT	Tình huống khảo sát	Kỹ thuật	Lý do
1	Quan sát thực tế nhân viên dọn dẹp phòng để nắm quy trình kiểm tra đồ minibar	Quan sát hiện trường (Observation)	Thấy trực tiếp các bước thao tác thực tế tại hiện trường
2	Thu thập đánh giá từ hơn 5.000 du khách sau khi trả phòng về chất lượng dịch vụ	Bảng câu hỏi / Khảo sát (Survey)	Số lượng khách lớn, thu thập nhanh số liệu đánh giá chất lượng
3	Phỏng vấn Tổng Giám đốc khách sạn về kế hoạch mở rộng chuỗi và định hướng dịch vụ	Phỏng vấn (Interview)	Cần trao đổi trực tiếp với lãnh đạo để khai thác sâu chiến lược, mục tiêu và định hướng nghiệp vụ
4	Đọc quy chế định mức thời gian dọn phòng và bảng giá đồ uống minibar	Nghiên cứu tài liệu (Document Analysis)	Bảng quy chế và đơn giá đã được ban hành chính thức
5	Lấy ý kiến của nhóm 10 nhân viên lễ tân ca đêm về các tình huống phát sinh	Thảo luận nhóm (Focus Group)	Có thể thu thập nhiều kinh nghiệm thực tế cùng lúc và phát hiện các vấn đề chung của nhóm
Đáp án cần điền
Câu 3: Phỏng vấn (Interview)
Câu 5: Thảo luận nhóm (Focus Group)
2. Câu hỏi phỏng vấn mở cho nhân viên lễ tân

Có thể hoàn thiện như sau:

"Những khó khăn hay sự cố phổ biến nhất mà bạn thường gặp khi làm thủ tục nhận phòng cho khách vào giờ cao điểm là gì? Bạn thường xử lý những tình huống đó như thế nào và bạn mong muốn hệ thống hỗ trợ thêm điều gì để quá trình nhận phòng nhanh và thuận tiện hơn?"

Câu này tốt vì nó khai thác được 3 thứ:

Vấn đề thực tế.
Cách nhân viên đang xử lý.
Nhu cầu cải tiến hệ thống.
BƯỚC 4: Phân loại FR / NFR
STT	Phát biểu yêu cầu	Phân loại	Mã ID	Giải thích
1	Khách hàng có thể chọn ngày nhận phòng và loại phòng trên trang web	FR	FR-01	Tính năng đặt phòng hệ thống cung cấp – LÀM GÌ
2	Thủ tục quét hộ chiếu và cấp thẻ phòng tại máy Kiosk tự động dưới 1 phút	NFR	NFR-01	Tiêu chuẩn tốc độ phục vụ tự động – TỐT NHƯ THẾ NÀO
3	Dữ liệu thông tin cá nhân và hộ chiếu của du khách phải được bảo mật an toàn	NFR	NFR-02	Tiêu chuẩn an toàn thông tin cá nhân – TỐT NHƯ THẾ NÀO
4	Nhân viên buồng phòng có thể cập nhật trạng thái phòng đã dọn xong trên điện thoại	FR	FR-02	Hệ thống cung cấp chức năng cập nhật trạng thái phòng – LÀM GÌ
5	Hệ thống quản lý lịch phòng phải đồng bộ theo thời gian thực 24/7 tránh trùng phòng	NFR	NFR-03	Yêu cầu về khả năng đồng bộ, tính sẵn sàng và độ tin cậy – TỐT NHƯ THẾ NÀO
Cần đặc biệt nhớ

Câu 4 là FR, vì nó mô tả một chức năng mà hệ thống phải cung cấp:

Nhân viên → cập nhật trạng thái phòng.

Câu 5 là NFR, vì trọng tâm nằm ở tiêu chuẩn:

thời gian thực + 24/7 + tránh trùng phòng.

BƯỚC 5: User Story
Điền phần "Để"

Để:

Tôi có thể nhận phòng nhanh chóng sau chuyến đi dài mà không phải xếp hàng chờ đợi tại quầy lễ tân.

User Story hoàn chỉnh

Là một du khách lưu trú tại khách sạn RikkeiStay, tôi muốn tự làm thủ tục nhận phòng và lấy thẻ khóa phòng tại máy Kiosk tự động, để tôi có thể nhận phòng nhanh chóng sau chuyến đi dài mà không phải xếp hàng chờ đợi tại quầy lễ tân.
