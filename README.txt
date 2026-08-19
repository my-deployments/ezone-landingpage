EzOne_Site.html — 2 trang trong 1 file
======================================
Mở EzOne_Site.html bằng trình duyệt. Giữ nguyên thư mục assets/ bên cạnh.
Dependency ngoài duy nhất: Google Fonts (Inter, Inter Tight, Poppins).

ĐIỀU HƯỚNG
  #/       -> Landing EzOne (dark)
  #/pms    -> Landing ezOne PMS (light)
Bấm "Sản phẩm > ezOne.Pms" ở header để sang trang PMS.
Bấm logo ở header trang PMS để về trang chủ.

CÁCH GỘP
- CSS 2 trang được scope vào .pg-home / .pg-pms (2 theme ngược nhau, trùng
  tên class nên bắt buộc phải tách). :root/body -> wrapper; html/* -> global
  khai 1 lần; @keyframes đổi tên hậu tố -h/-p.
- Toàn bộ id của trang PMS đổi tiền tố "p-" để không trùng id trang chủ.
- $ / $$ của JS mỗi trang ràng vào đúng gốc trang, tránh JS trang này
  bắt nhầm phần tử trang kia.

LOGO
- Header + footer trang PMS dùng SVG GỐC từ "Logo SVG.zip"
  (Module=PMS, Style=Horizontal — Light Mode cho header, Dark Mode cho footer).
- Dropdown Sản phẩm dùng Icon only / Light Mode của 5 module.
