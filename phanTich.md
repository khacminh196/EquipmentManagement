# Mục đích sử dụng:

	- Quản lý các thiết bị trong công ty

		VD: Ổ điện, màn hình, bàn phím, ghế, ...


# Đối tượng sử dụng và chức năng từng đối tượng

	- Admin

		*Đăng nhập hệ thống*
		*Tìm kiếm thiết bị theo loại thiết bị, loại thiết bị, id thiết bị*
		*Duyệt các yêu cầu mượn thiết bị*
		*Xử lý các báo cáo thiết bị hỏng hóc của employee*
		*Xem chi tiết các thiết bị*
		*Thu hồi các thiết bị không sử dụng nữa*
		*Cấp thiết bị mặc định ban đầu cho nhân viên.*
		*Quản lý thiết bị theo nhân viên (Danh sách nhân viên và thiết bị)*
		*Tạo yêu cầu nhập thiết bị, mua thiết bị*
		*Tạo phiếu bảo dưỡng, sửa thiết bị*

	- Supper Admin:

		*Đăng nhập hệ thống*
		*Set nhân viên phụ trách quản lý*
		*Duyệt yêu cầu nhập thiết bị*
		*Xem số liệu thống kê ( Thiết bị nhập mới, thiết bị hỏng, ... )*

	- Employee
		*Đăng nhập hệ thống*
		*Gửi đơn yêu cầu mượn thiết bị (Loại thiết bị)*
		*Báo cáo thiết bị hỏng hóc (Nguyên nhân, ngày hỏng)*
		*Quản lý thiết bi đang sử dụng*

# Quy trình:
	
	1. Admin gửi yêu cầu nhập thiết bị lên Supper Admin, khi đc đồng ý Admin nhập thiết bị vào kho
	2. Khi có nhân viên mới, Admin sẽ cấp thiết bị mặc định cho nhân viên ( máy tính, ghế )
	3. Khi có báo cáo về hỏng hóc, Admin xác nhận và tạo phiếu sửa thiết bị, cung cấp thiết bị khác cho người bị hỏng máy