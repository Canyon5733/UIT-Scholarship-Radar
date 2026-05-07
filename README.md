# UIT Scholarship Radar — UIT Knowledge

UIT Scholarship Radar là một website tĩnh giúp sinh viên UIT kiểm tra khả năng nhận **học bổng khuyến khích học tập** dựa trên MSSV, ngành học và GPA học kỳ.

Website được xây dựng bởi **UIT Knowledge** nhằm hỗ trợ sinh viên tham khảo nhanh mốc GPA dự đoán theo từng ngành/khoá.

## Demo

Sau khi deploy lên Vercel, bạn có thể thêm link tại đây:

```txt
https://your-project-name.vercel.app
```

## Tính năng chính

- Nhập MSSV, ngành học và GPA để kiểm tra khả năng nhận học bổng.
- Tự động nhận diện khoá dựa trên MSSV:
  - `2352` → K18
  - `2452` → K19
  - `2552` → K20
- So sánh GPA của người dùng với:
  - GPA dự đoán của ngành
  - GPA an toàn của ngành
- Hiển thị phần trăm dự đoán khả năng nhận học bổng.
- Có bảng dữ liệu dự đoán theo ngành cho K18, K19 và K20.
- Giao diện responsive, dùng tốt trên desktop và mobile.
- Không yêu cầu đăng nhập.
- Không lưu MSSV, GPA hoặc thông tin cá nhân của người dùng.

## Công nghệ sử dụng

Dự án sử dụng các công nghệ đơn giản, dễ deploy:

- HTML
- CSS
- JavaScript thuần
- Vercel để deploy website tĩnh

## Cấu trúc dự án

```txt
.
├── index.html
├── favicon.svg
└── README.md
```

> Lưu ý: file chính của website là `index.html`, cần đặt ở thư mục gốc để Vercel nhận diện và deploy đúng.

## Cách chạy trên máy local

Chỉ cần mở trực tiếp file `index.html` bằng trình duyệt.

Hoặc dùng extension **Live Server** trong VS Code:

1. Mở project bằng VS Code.
2. Cài extension `Live Server`.
3. Click chuột phải vào `index.html`.
4. Chọn `Open with Live Server`.

## Cách deploy lên Vercel

### Cách 1: Deploy bằng GitHub

1. Tạo repository mới trên GitHub.
2. Push source code lên GitHub:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

3. Vào Vercel.
4. Chọn **Add New Project**.
5. Import repository từ GitHub.
6. Giữ cấu hình mặc định:
   - Framework Preset: `Other`
   - Build Command: để trống
   - Output Directory: để trống
7. Chọn **Deploy**.

### Cách 2: Deploy bằng Vercel CLI

Cài Vercel CLI:

```bash
npm install -g vercel
```

Deploy project:

```bash
vercel
```

Deploy production:

```bash
vercel --prod
```

## Gợi ý tên repository

Bạn có thể đặt tên repository là:

```txt
uit-scholarship-radar
```

hoặc:

```txt
uit-scholarship-checker
```

Tên project trên Vercel có thể là:

```txt
uit-scholarship-radar
```

Khi deploy xong, link có thể có dạng:

```txt
https://uit-scholarship-radar.vercel.app
```

## Lưu ý quan trọng

Website này chỉ mang tính chất **tham khảo**. Kết quả học bổng chính thức vẫn phụ thuộc hoàn toàn vào thông báo từ nhà trường.

UIT Knowledge không đại diện cho Trường Đại học Công nghệ Thông tin trong việc công bố kết quả học bổng.

## Tác giả

Made by **UIT Knowledge**

- YouTube: https://www.youtube.com/@UIT_Knowledge
- Facebook: https://www.facebook.com/GenCanyon/
- Discord: https://discord.gg/pFMpsQA6r4

## License

Dự án phục vụ mục đích học tập và cộng đồng sinh viên UIT.
