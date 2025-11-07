# 🚀 Portfolio Website - Rayhan Hidayatul Fikri

Portfolio website modern, responsif, dan interaktif yang menampilkan projects, experiences, dan informasi kontak.

## ✨ Fitur Utama

### 🎨 Design & UI/UX
- **Glassmorphism Effect** - Navbar dan card dengan backdrop blur untuk tampilan modern
- **Gradient Animations** - Text gradient yang bergerak smooth
- **Custom Cursor** - Cursor kustom yang interaktif (desktop only)
- **Smooth Animations** - Animasi slide-up, float, dan fade-in
- **Parallax Effects** - Efek parallax pada foto profil dan karakter

### 🎯 Interactive Features
- **Scroll Progress Bar** - Bar di atas halaman yang menunjukkan progress scroll
- **Navbar Auto-hide** - Navbar menghilang saat scroll ke bawah
- **Active Section Highlighting** - Menu navbar otomatis highlight sesuai section
- **Card Tilt Effect** - Card yang mengikuti gerakan mouse (3D tilt)
- **Hover Animations** - Efek hover yang smooth pada semua elemen interaktif
- **Ripple Button Effect** - Efek ripple saat klik button
- **Mobile Menu** - Hamburger menu untuk tampilan mobile

### 📱 Responsive Design
- **Mobile First Approach** - Optimized untuk semua ukuran layar
- **Breakpoints**:
  - Mobile: < 480px
  - Tablet: 481px - 768px
  - Desktop: > 768px

### ⚡ Performance
- **Lazy Loading Images** - Gambar dimuat dengan blur effect
- **Smooth Scrolling** - Scroll behavior yang halus
- **Optimized Animations** - Menggunakan CSS transforms dan will-change
- **Intersection Observer** - Efisien untuk scroll reveal animations

## 🛠️ Teknologi

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS dengan custom properties, flexbox, dan grid
- **JavaScript (Vanilla)** - No dependencies, pure JavaScript
- **Font** - Inter (Google Fonts)

## 📂 Struktur File

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Styles dengan animations & responsive design
├── script.js           # Interactive features & animations
├── README.md           # Documentation
└── img/               # Images folder
    ├── fotorayhan.png
    ├── sapaan.png
    ├── gradien.png
    └── ...
```

## 🎬 Animasi & Effects

### CSS Animations
- `slide-up` - Entrance animation untuk sections
- `fade-in` - Fade in effect
- `float` - Floating animation untuk karakter sapaan
- `glow` - Glowing effect untuk foto profil
- `gradient-shift` - Animated gradient background
- `ripple-animation` - Button click effect

### JavaScript Features
- Smooth scroll navigation
- Navbar scroll behavior
- Section intersection observer
- Parallax scrolling
- 3D card tilt effect
- Custom cursor tracking
- Mobile menu toggle
- Image lazy loading

## 🚀 Cara Menggunakan

1. Clone atau download repository
2. Buka `index.html` di browser
3. Enjoy! ✨

Atau langsung double-click file `index.html` untuk membuka di browser default Anda.

## 🎨 Customization

### Mengubah Warna
Edit CSS variables di `:root`:
```css
:root {
    --primary-bg: #0D1B1B;
    --dark-grey: #444444;
    --light-grey: #D9D9D9;
    --text-color: #FFFFFF;
    --accent-color: #152C2C;
    --blue-text: #50B6E2;
    --corner-radius: 20px;
}
```

### Menonaktifkan Custom Cursor
Hapus atau comment baris ini di `style.css`:
```css
body {
    cursor: none; /* Hapus baris ini */
}
```

### Mengubah Kecepatan Animasi
Edit transition speeds:
```css
--transition-smooth: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
--transition-bounce: all 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55);
```

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

## 🔧 Development Tips

### Testing Responsiveness
1. Buka DevTools (F12)
2. Toggle device toolbar (Ctrl+Shift+M)
3. Test di berbagai ukuran layar

### Performance Testing
- Gunakan Lighthouse di Chrome DevTools
- Target: 90+ Performance Score

## 📝 To-Do / Future Improvements

- [ ] Dark/Light mode toggle
- [ ] Multi-language support (ID/EN)
- [ ] Project filtering system
- [ ] Contact form integration
- [ ] Blog section
- [ ] Loading screen animation
- [ ] PWA support
- [ ] Analytics integration

## 👨‍💻 Author

**Rayhan Hidayatul Fikri**
- LinkedIn: [rayhanhidayatulfikri](https://www.linkedin.com/in/rayhanhidayatulfikri)
- Email: rayhanhidayatulfikri@gmail.com
- Instagram: [@rayhanhidayatul_](https://www.instagram.com/rayhanhidayatul_/)
- GitHub: [rayhanhidayatul022](https://github.com/rayhanhidayatul022/)

## 📄 License

Feel free to use this as inspiration for your own portfolio! 

---

Made with ❤️ and lots of ☕ by Rayhan
