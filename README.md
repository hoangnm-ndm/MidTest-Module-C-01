# Hướng dẫn làm bài

- Thời gian làm bài: 180 phút.
- Download [Repository](https://github.com/hoangnm-ndm/MidTest-Module-C-01) về máy của học viên và thực hiện code trực tiếp trong thư mục này.
- Sau khi làm bài xong, học viên đẩy code lên github của mình và nộp lại link repo đó qua google form: [Form Nộp Bài](https://forms.gle/joNB5cDdMK5Eqv5E7).
- Trong quá trình làm bài, gỡ bỏ và không sử dụng các extensions có sử dụng AI như Tabnine, Github copilot, Codeium, v.v.
- Được phép mở các trang web lấy giao diện hoặc icons như tailwindCSS, bootstrap, boxicon, fontawesome, .v.v trong quá trình làm bài.

# Yêu cầu

Xây dựng ứng dụng quản lý hệ thống học tập (LMS) bản MVP với ReactJS và json-server bao gồm các tính năng sau:

## 1. Giao diện và routing (2 điểm)

- Dữ liệu trong `db.json` (Khóa học, Bài học, Học viên) đã được cung cấp sẵn.
- Xây dựng hệ định tuyến cho các trang:
  - Trang danh sách khóa học.
  - Trang chi tiết khóa học (bao gồm danh sách bài học).
  - Trang danh sách học viên của khóa học.
- Xử lý route không tồn tại (404) và hiển thị thông báo lỗi cho người dùng.
- Giao diện thân thiện và dễ sử dụng, có thể sử dụng CSS hoặc thư viện UI đơn giản.

---

## 2. Quản Lý Khóa Học (courses) (2 điểm)

- **GET**: Lấy danh sách khóa học từ API và hiển thị tên + mô tả khóa học.
- **POST**: Thêm mới khóa học qua form.
- **PUT**: Cập nhật thông tin khóa học.
- **DELETE**: Xóa khóa học.

---

## 3. Quản Lý Bài Học (lessons) (2 điểm)

- **GET**: Lấy danh sách bài học theo khóa học (khi ấn vào tên khoá học sẽ vào trang danh sách bài học thuộc khoá học đó).
- **POST**: Thêm bài học cho khóa học.
- **PUT**: Cập nhật thông tin bài học.
- **DELETE**: Xóa bài học khỏi khóa học.

---

## 4. Các tính năng nâng cao (2 điểm)

- Tìm kiếm khóa học theo tên.
- Tìm kiếm bài học theo tên.
- Sắp xếp khoá học theo tên từ A-Z hoặc Z-A.
- Sắp xếp khoá học theo giá từ thấp đến cao hoặc từ cao xuống thấp, bỏ sắp xếp.

---

## 5. Đăng ký, đăng nhập và nhập học (2 điểm)

- Đăng ký vào hệ thống (bao gồm email, password, tên học viên).
- Đăng nhập vào hệ thống (bao gồm email, password). Sau khi đăng nhập thành công, chuyển hướng đến trang danh sách khóa học.
- Học viên có thể đăng ký khoá học hoặc huỷ đăng ký khoá học.
- Học viên có thể xem danh sách khoá học đã đăng ký.

---

## Quy ước tính điểm:

- **Routing và giao diện:** 2 điểm
- **Quản lý khóa học:** 2 điểm
- **Quản lý bài học:** 2 điểm
- **Tính năng nâng cao:** 2 điểm
- **Đăng ký, đăng nhập và nhập học:** 2 điểm
