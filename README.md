I)Use Case
-Sprint 1:
UC-02: Đăng ký
UC-01: Đăng nhập
UC-22: Tạo tài khoản
UC-14: Tạo dịch vụ mới
UC-15: Chỉnh sửa dịch vụ.
UC-16: Xóa dịch vụ
UC-19: Quản lý khả dụng (khung thời gian)
-Sprint 2:
UC-05: Xem danh sách dịch vụ
UC-04: Tìm kiếm dịch vụ
UC-06: Xem chi tiết dịch vụ
UC-10: Đặt dịch vụ
UC-12: Xem chi tiết đặt chỗ
UC-17: Kiểm tra lịch sử đặt chỗ
UC-11: Hủy đặt chỗ
UC-18: Chấp nhận/Hủy đặt chỗ
-Sprint 3:
UC-25: Xác nhận thanh toán
UC-13: Phản hồi dịch vụ
UC-08: Xem hồ sơ
UC-09: Chỉnh sửa hồ sơ
UC-03: Quên mật khẩu
-Sprint 4:
UC-20: Xem danh sách tài khoản
UC-21: Xem chi tiết tài khoản
UC-23: Chỉnh sửa tài khoản
UC-24: Xóa tài khoản

II)Test Case
Spring 1:
UC-02: Đăng ký
T45: Đăng ký thành công với thông tin hợp lệ.
T46: Đăng ký thất bại với email đã tồn tại.
T47: Đăng ký thất bại khi tên đăng nhập đã tồn tại.
UC-01: Đăng nhập
T42: Đăng nhập thành công với thông tin hợp lệ.
T43: Đăng nhập thất bại khi tài khoản bị khóa.
T48: Đăng ký thất bại khi mật khẩu và xác nhận mật khẩu không khớp.
T-: Số điện thoại đã tồn tại
UC-22: Tạo tài khoản
T33: Tạo tài khoản thành công với thông tin hợp lệ.
T34: Tạo tài khoản thất bại khi email đã tồn tại.
T35: Tạo tài khoản thất bại khi tên đăng nhập đã tồn tại
UC-14: Tạo dịch vụ mới
T13: Tạo dịch vụ mới thành công với thông tin hợp lệ.
T14: Tạo dịch vụ mới thất bại khi dịch vụ đã tồn tại.
T15: Tạo dịch vụ mới thất bại khi không có quyền truy cập..
UC-15: Chỉnh sửa dịch vụ
T16: Chỉnh sửa dịch vụ thành công với thông tin hợp lệ.
T17: Chỉnh sửa dịch vụ thất bại khi dịch vụ không tồn tại.
T18: Chỉnh sửa dịch vụ thất bại khi không có quyền truy cập.
UC-16: Xóa dịch vụ
T19: Xóa dịch vụ thành công với dịch vụ tồn tại.
T20: Xóa dịch vụ thất bại khi dịch vụ đang được sử dụng.
T21: Xóa dịch vụ thất bại khi không có quyền truy cập.
UC-19: Quản lý khả dụng (khung thời gian)
T26: Quản lý khung thời gian thành công với thông tin hợp lệ.
T27: Quản lý khung thời gian thất bại khi không có quyền truy cập.
T28: Quản lý khung thời gian thất bại khi thời gian không hợp lệ.
Spring 2:
UC-04: Tìm kiếm dịch vụ
T53: Tìm kiếm dịch vụ thành công với từ khóa tồn tại.
T54: Tìm kiếm dịch vụ thất bại với từ khóa không tồn tại.
UC-06: Xem chi tiết dịch vụ
T1: Xem chi tiết dịch vụ với quyền truy cập khách hàng.
T2: Xem chi tiết dịch vụ với quyền truy cập quản trị viên.
UC-10: Đặt dịch vụ
T3: Đặt dịch vụ thành công với thông tin hợp lệ.
T4: Đặt dịch vụ thất bại khi dịch vụ đã đầy. (Slot không thể đặt đc do đã hết available slot)
T5: Đặt dịch vụ thất bại khi chọn thời gian không hợp lệ.(Lúc book không chọn được ngày trong quá khứ không )
T6: Đặt dịch vụ với thời gian đã bị đặt trước.
T7: Đặt dịch vụ với số lượng thú cưng vượt quá giới hạn cho phép.
UC-12: Xem chi tiết đặt chỗ
UC-17: Kiểm tra lịch sử đặt chỗ
UC-11: Hủy đặt chỗ
T8: Hủy đặt chỗ thành công với thông tin hợp lệ.
T9: Hủy đặt chỗ thất bại khi đặt chỗ không tồn tại.
T10: Hủy đặt chỗ thât bại khi thời gian đã quá hạn
T11 : Hủy đặt chỗ thất bại khi dịch vụ đã hoàn thành 
UC-18: Chấp nhận/Hủy đặt chỗ
T22: Chấp nhận đặt chỗ thành công với thông tin hợp lệ.
T23: Hủy đặt chỗ thành công với thông tin hợp lệ.
T24: Chấp nhận đặt chỗ thất bại khi không có quyền truy cập.
T25: Hủy đặt chỗ thất bại khi không có quyền truy cập.
T-: Cập nhật slot khi hủy đặt chỗ

Spring 3:
UC-25: Xác nhận thanh toán
T10: Xác nhận thanh toán thành công với thông tin hợp lệ.
T11: Xác nhận thanh toán thất bại khi thẻ hết hạn.
T12: Xác nhận thanh toán thất bại khi số dư không đủ.
UC-13: Phản hồi dịch vụ
T57: Đánh giá dịch vụ thất bại khi không có quyền truy cập.
UC-08: Xem hồ sơ
UC-09: Chỉnh sửa hồ sơ
UC-03: Quên mật khẩu
T49: Gửi email khôi phục mật khẩu thành công với email hợp lệ.
T50: Gửi email khôi phục mật khẩu thất bại với email không tồn tại trong hệ thống.
T51: Đặt lại mật khẩu thành công với liên kết hợp lệ.
T52: Đặt lại mật khẩu thất bại với liên kết đã hết hạn.
Spring 4:

UC-20: Xem danh sách tài khoản
T29: Xem danh sách tài khoản thất bại khi không có quyền truy cập.
UC-21: Xem chi tiết tài khoản
T30: Xem chi tiết tài khoản thành công với tài khoản tồn tại.
T31: Xem chi tiết tài khoản thất bại khi tài khoản không tồn tại.
T32: Xem chi tiết tài khoản thất bại khi không có quyền truy cập.
UC-23: Chỉnh sửa tài khoản
T36: Chỉnh sửa tài khoản thành công với thông tin hợp lệ.
T37: Chỉnh sửa tài khoản thất bại khi thông tin không hợp lệ.
T38: Chỉnh sửa tài khoản thất bại khi không có quyền truy cập.
T-: Mật khẩu mới không trùng mật khẩu cũ
T-: Email mới không trùng với email đã có/cũ
T-: Số điện thoại đã tồn tại
UC-24: Xóa tài khoản
T39: Xóa tài khoản thành công với tài khoản tồn tại.
T40: Xóa tài khoản thất bại khi tài khoản đang được sử dụng.
T41: Xóa tài khoản thất bại khi không có quyền truy cập.

Phân công viết Test case
--------sping 1---------------
Nguyên UC 14
Bin UC 2,1
Phong UC 22
Minh UC 16
Hoàng UC 15
Hòa UC 19
---------Spring 2----------
Hòa UC 4
Hoàng Uc 11
Nguyên UC 5,6
Phong 10,18
Minh 12
Bin 17
--------Spring 3-----------
Hòa UC 25
Minh Uc 13
Nguyên UC 8
Bin 9
Hoàng 3
-------Spring 4-----------
Phong UC 20
Minh UC 21
Hoàng UC 23
Hòa UC 24



