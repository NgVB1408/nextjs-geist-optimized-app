# Betino.win Clone - Hướng dẫn tải về PC

## Cấu trúc Project
```
betino-clone/
├── package.json
├── next.config.ts
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.mjs
├── eslint.config.mjs
├── components.json
├── public/
│   ├── next.svg
│   ├── vercel.svg
│   └── ...
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── globals.css
│   │   ├── login/
│   │   │   └── page.tsx
│   │   └── customer-service/
│   │       └── page.tsx
│   ├── components/
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   └── ui/ (shadcn components)
│   ├── hooks/
│   │   └── use-mobile.ts
│   └── lib/
│       └── utils.ts
```

## Cách chạy project sau khi tải về:

1. **Cài đặt Node.js** (phiên bản 18 trở lên)
2. **Mở terminal/command prompt** trong thư mục project
3. **Cài đặt dependencies:**
   ```bash
   npm install
   ```
4. **Chạy development server:**
   ```bash
   npm run dev
   ```
5. **Mở trình duyệt** và truy cập: http://localhost:3000

## Tính năng đã hoàn thành:

✅ **Trang chủ** - Giao diện giống betino.win với form đăng nhập
✅ **Header** - Navigation với logo và menu
✅ **Footer** - Links và thông tin liên hệ
✅ **Trang đăng nhập** - Form đăng nhập riêng biệt
✅ **Trang Customer Service** - Hỗ trợ khách hàng với live chat
✅ **Responsive Design** - Tương thích mobile và desktop
✅ **Dark Theme** - Giao diện tối như website gốc
✅ **Modern UI** - Sử dụng Tailwind CSS và Next.js 15

## Công nghệ sử dụng:
- **Next.js 15** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Shadcn/ui** - UI components
- **React Hook Form** - Form handling

## Lưu ý:
- Project này chỉ là bản clone giao diện, không có backend thực tế
- Các form đăng nhập chỉ là demo, không kết nối database
- Để deploy production, cần cấu hình thêm backend và database
