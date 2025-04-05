## 📚 Library Management Web App

**Nhóm 4 - THLTUDDN**

### 🌟 Giới thiệu

👉 Đây là một **ứng dụng web quản lý thư viện** được xây dựng bằng **Next.js**, **React**, và **Tailwind CSS**. Ứng dụng hỗ trợ quản lý sách, người đọc, mượn trả sách và gửi thông báo email nhắc nhở. Hệ thống giúp thư viện tối ưu hóa quy trình làm việc, giảm thiểu sai sót trong việc quản lý dữ liệu và nâng cao trải nghiệm của người dùng.

> ⚠️ **Lưu ý:** Đây là phiên bản **demo** chỉ tập trung vào giao diện, chưa tích hợp backend thực tế.

---

### 🚀 Công Nghệ Sử Dụng

- **Frontend**: [Next.js](https://nextjs.org/) + [React.js](https://react.dev/)
- **UI**: [Tailwind CSS](https://tailwindcss.com/)
- **Quản lý package**: `pnpm`

---

### 🔑 Tính Năng

👉 **Tìm kiếm sách & đọc giả**
   - Cho phép tìm kiếm sách theo **tên sách**, **tác giả**, hoặc **thể loại**.
   - Tìm kiếm thông tin đọc giả dựa trên **tên**, **email** hoặc **mã thành viên**.
   - Giao diện tìm kiếm được thiết kế rõ ràng, hỗ trợ lọc kết quả tức thì.

👉 **Quản lý sách & danh mục**
   - Thêm, chỉnh sửa, xóa thông tin sách bao gồm tên, tác giả, thể loại, số lượng, mô tả ngắn.
   - Phân loại sách theo danh mục như khoa học, văn học, lịch sử, v.v...
   - Dễ dàng duyệt và tìm kiếm sách trong từng danh mục cụ thể.

👉 **Quản lý mượn/trả sách**
   - Đăng ký mượn sách và trả sách qua giao diện người dùng đơn giản, dễ thao tác.
   - Theo dõi lịch sử mượn của từng người đọc.
   - Tự động cập nhật trạng thái mượn/trả và kiểm soát sách quá hạn.

👉 **Quản lý tác giả**
   - Quản lý danh sách tác giả bao gồm thông tin cá nhân, quốc tịch, tiểu sử ngắn.
   - Gắn kết sách với tác giả cụ thể để phục vụ tra cứu và tìm kiếm nâng cao.

👉 **Quản lý người đọc**
   - Thêm mới, chỉnh sửa, xóa người đọc.
   - Theo dõi số lượng sách đã và đang mượn, lịch sử mượn sách.
   - Giao diện người đọc thân thiện, dễ tra cứu và cập nhật.

👉 **Thông báo email nhắc nhở trả sách**
   - Gửi email tự động đến người dùng khi sách gần đến hạn trả hoặc đã quá hạn.
   - Nội dung email tùy chỉnh, hỗ trợ đa ngôn ngữ nếu cần.
   - Hỗ trợ gửi thông báo hàng loạt theo lịch trình.

---

### 📂 Cấu Trúc Dự Án

```
library-management/
├── app/                 # Thư mục chính của Next.js
├── components/          # Các component UI
├── hooks/               # Custom hooks (nếu có)
├── lib/                 # Thư viện & helper functions
├── public/              # Assets tĩnh (hình ảnh, icons, ...)
├── styles/              # Tệp CSS, Tailwind config
├── tailwind.config.ts   # Cấu hình Tailwind CSS
├── package.json         # File khai báo dependencies
├── next.config.mjs      # Cấu hình Next.js
├── .gitignore           # Danh sách file cần bỏ qua trong Git
└── README.md            # Tài liệu hướng dẫn (file này)
```

---

### 🛠 Cách Cài Đặt

1️⃣ **Clone repo**

```bash
git clone https://github.com/group4/library-management.git
cd library-management
```

2️⃣ **Cài đặt dependencies**

```bash
pnpm install
```

3️⃣ **Chạy ứng dụng**

```bash
pnpm dev
```

🔗 Ứng dụng sẽ chạy tại: `http://localhost:3000`

---

### 🎯 Mục Tiêu

- Xây dựng giao diện **UI/UX thân thiện**, hiện đại và dễ sử dụng cho hệ thống quản lý thư viện.
- Mô phỏng **quy trình quản lý sách, người đọc và mượn trả** để giúp thư viện tối ưu hóa việc vận hành.
- Hỗ trợ chức năng **tìm kiếm nhanh và chính xác**, giúp người dùng dễ dàng truy xuất thông tin cần thiết mà không cần kiến thức kỹ thuật.
- Cải thiện trải nghiệm người dùng thông qua **giao diện mượt mà**, dễ tiếp cận và có thể tùy biến.
- Triển khai **hệ thống thông báo qua email**, giúp nhắc nhở người đọc về hạn trả sách, giảm thiểu tình trạng quá hạn.
- Đặt nền tảng cho việc tích hợp **backend thực tế** (Django hoặc Node.js) để phát triển thành sản phẩm hoàn chỉnh trong tương lai.
- Hướng đến xây dựng một **giải pháp thư viện số thông minh**, tiết kiệm thời gian và công sức cho cả thủ thư và người đọc.

---

### 👥 Nhóm Thực Hiện

- **Lê Đức Kiên**
- **Lê Nguyễn Ngọc Tú Hương**
- **Nguyễn Thị Bích Ngọc**

📧 **Liên hệ**: [group4.libraryapp@example.com](mailto:group4.libraryapp@example.com)
🔗 **GitHub**: [https://github.com/group4/library-management](https://github.com/group4/library-management)
