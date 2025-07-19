# MADONE Studio - Game Studio Website

Website giới thiệu game studio chuyên nghiệp được tạo bằng HTML, CSS và JavaScript thuần.

## 📁 Cấu trúc file

```
├── index.html          # File HTML chính
├── styles.css          # File CSS chính với animations và responsive
├── script.js           # File JavaScript với tất cả tính năng tương tác
├── data.js             # File data mẫu để dễ dàng thay đổi thông tin
└── README.md           # File hướng dẫn
```

## 🎨 Tính năng

### ✅ Header & Navigation
- Logo với gradient effect
- Navigation menu responsive
- Mobile hamburger menu
- Smooth scroll navigation
- Header background blur khi scroll

### ✅ Hero Section
- Background image với overlay gradient
- Floating elements với mouse parallax
- Animated title với gradient text
- Call-to-action buttons với hover effects
- Scroll indicator animation

### ✅ Games Section
- Grid layout responsive
- Game cards với hover animations
- Image scale effect
- Button interactions
- Scroll-triggered animations

### ✅ Studio Section
- Team mission với layout grid
- Statistics counters
- Team member cards
- Image hover effects với social links
- Scroll animations

### ✅ Contact Section
- Contact form với validation
- Contact methods display
- Social media links
- Form submission với notification
- Responsive grid layout

### ✅ Footer
- Logo và description
- Quick links navigation
- Social media icons
- Copyright information

## 🚀 Animations & Effects

- **Scroll animations**: Fade in, slide in từ left/right
- **Hover effects**: Scale, glow, color transitions
- **Parallax effects**: Mouse following, scroll parallax
- **Loading animation**: Page load spinner
- **Ripple effects**: Button click animations
- **Mobile animations**: Menu toggle, responsive transitions

## 📱 Responsive Design

- **Mobile-first approach**
- **Breakpoints**: 768px, 480px
- **Mobile menu**: Hamburger navigation
- **Grid layouts**: Auto-responsive
- **Touch-friendly**: Button sizes và spacing

## 🛠 Cách sử dụng

### 1. Thay đổi thông tin cơ bản

Mở file `data.js` để thay đổi:

```javascript
// Thông tin games
const gamesData = [
    {
        title: "Tên Game Của Bạn",
        description: "Mô tả game...",
        image: "link-hình-ảnh",
        // ...
    }
];

// Thông tin team
const teamData = [
    {
        name: "Tên thành viên",
        role: "Vai trò",
        description: "Mô tả...",
        github: "link-github",
        linkedin: "link-linkedin"
    }
];

// Thông tin liên hệ
const contactData = {
    email: "email-của-bạn@domain.com",
    telegram: "@username-telegram",
    location: "Địa chỉ của bạn"
};
```

### 2. Thay đổi màu sắc và style

Mở file `styles.css` và tìm phần CSS variables:

```css
:root {
    --primary-color: #ef4444;    /* Màu chính (đỏ) */
    --secondary-color: #a855f7;  /* Màu phụ (tím) */
    --background-color: #000000; /* Màu nền */
    /* ... */
}
```

### 3. Thay đổi hình ảnh

Thay thế các URL hình ảnh trong:
- `index.html` (hero background, game images, team photos)
- `data.js` (data mẫu)
- `styles.css` (background images)

### 4. Thêm tính năng mới

File `script.js` chứa tất cả JavaScript:
- Form handling
- Scroll animations
- Mobile navigation
- Notification system
- Parallax effects

## 🎯 Customization Guide

### Thay đổi logo và branding

1. **Logo text**: Tìm `MADONE Studio` trong HTML và thay đổi
2. **Logo icon**: Thay đổi chữ "M" trong class `.logo-icon`
3. **Gradient colors**: Sửa các gradient trong CSS

### Thêm section mới

1. Thêm HTML structure
2. Thêm CSS styling
3. Thêm scroll animation trong JavaScript nếu cần

### Thay đổi animations

Tất cả animations được định nghĩa trong CSS:
- `@keyframes` cho các animation
- `transition` cho hover effects
- `transform` cho các effects

### Form integration

Để kết nối form với backend thực:

1. Tìm function `handleSubmit` trong `script.js`
2. Thay thế phần simulation bằng API call thực
3. Cập nhật validation rules nếu cần

## 📋 Checklist tùy chỉnh

- [ ] Thay đổi tên studio và logo
- [ ] Cập nhật thông tin games
- [ ] Thay đổi hình ảnh team members
- [ ] Cập nhật thông tin liên hệ
- [ ] Thay đổi màu sắc chủ đạo
- [ ] Cập nhật social media links
- [ ] Test responsive trên mobile
- [ ] Test form submission
- [ ] Check tất cả animations

## 🌐 Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📝 Notes

- Tất cả hình ảnh hiện tại sử dụng Unsplash (demo)
- Form chỉ có validation frontend, cần backend để submit thực
- CSS sử dụng modern features (CSS Grid, Flexbox, CSS Variables)
- JavaScript sử dụng ES6+ features

## 🚀 Deploy

Để deploy website:

1. Upload tất cả files lên web hosting
2. Đảm bảo `index.html` là file chính
3. Test tất cả tính năng
4. Cập nhật thông tin thực tế

Website hoàn toàn static, không cần server-side processing.