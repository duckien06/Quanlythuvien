## 📚 Library Management Web App

**Nhóm 4 - THLTUDDN**

### 🌟 Giới thiệu

👉 Đây là một **ứng dụng web quản lý thư viện** được xây dựng bằng **Next.js**, **React**, và **Tailwind CSS**. Ứng dụng hỗ trợ quản lý sách, người đọc, mượn trả sách và gửi thông báo email nhắc nhở.

> ⚠️ **Lưu ý:** Đây là phiên bản **demo** chỉ tập trung vào giao diện, chưa tích hợp backend thực tế.

---

### 🚀 Công Nghệ Sử Dụng

- **Frontend**: [Next.js](https://nextjs.org/) + [React.js](https://react.dev/)
- **UI**: [Tailwind CSS](https://tailwindcss.com/)
- **Quản lý package**: `pnpm`

---

### 🔑 Tính Năng

👉 **Tìm kiếm sách & đọc giả**\
👉 **Quản lý sách & danh mục**\
👉 **Quản lý mượn/trả sách**\
👉 **Quản lý tác giả**\
👉 **Quản lý người đọc**\
👉 **Thông báo email nhắc nhở trả sách**

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

🔗  Ứng dụng sẽ chạy tại: ``

---

### 🎯 Mục Tiêu

- Xây dựng giao diện **UI/UX thân thiện** cho hệ thống quản lý thư viện.
- Mô phỏng quy trình quản lý sách, người đọc và mượn trả.
- Đặt nền tảng để tích hợp backend (Django hoặc Node.js) trong tương lai.

---

### 👥 Nhóm Thực Hiện

- **Lê Đức Kiên** - 221121514214
- **Và các thành viên khác...**

📧 **Liên hệ**: [group4.libraryapp@example.com](mailto:group4.libraryapp@example.com)\
🔗 **GitHub**: [https://github.com/group4/library-management](https://github.com/group4/library-management)
