# QA Portfolio — Đoàn Thành Trung

Trang portfolio cá nhân cho vị trí QA Engineer / Senior Tester, trình bày theo phong cách một bản
**test-run report** (mỗi phần là một `describe()`, kỹ năng hiển thị dạng coverage bar, kinh nghiệm
trình bày như changelog), theme tối kiểu terminal/hacker.

Đây là dự án **tĩnh, một file duy nhất** (`index.html`) — không cần cài đặt, không cần build.

## Xem thử

Mở trực tiếp file `index.html` bằng trình duyệt bất kỳ (double-click hoặc kéo thả vào trình duyệt).

## Nội dung hiện tại

Nội dung (kinh nghiệm, dự án, học vấn, chứng chỉ, kỹ năng) đã được điền theo CV thật. Còn lại cần bạn
tự bổ sung:

- **Link LinkedIn / GitHub thật**: trong `<div class="contact-row">` ở đầu file, hiện đang là `href="#"`
- **Ảnh đại diện**: file `avatar.jpg` trong cùng thư mục, thay file này để đổi ảnh (giữ nguyên tên hoặc
  sửa lại đường dẫn `src` trong thẻ `<img>` ở phần `.avatar-frame`)

Khi có thêm số liệu định lượng thật (số test case đã viết, số bug phát hiện, % cải thiện...), có thể bổ
sung vào phần thống kê đầu trang (`.hero-stats`).

## Deploy miễn phí (khi đã ưng nội dung)

Vì chỉ có 1 file HTML tĩnh (+ ảnh avatar), có thể deploy miễn phí bằng nhiều cách, ví dụ:

- **GitHub Pages**: đẩy cả thư mục lên một repo GitHub, bật Pages trong Settings → có link công khai
- **Netlify Drop**: vào [app.netlify.com/drop](https://app.netlify.com/drop), kéo thả cả thư mục này vào là có link ngay, không cần tài khoản
- **Vercel**: tương tự, kéo thả qua `vercel.com`
