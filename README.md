📁 README.md untuk Repository Portfolio Nimzz

```markdown
# 🚀 Nimzz Portfolio - Web Developer & Video Editor

![Portfolio Preview](https://files.catbox.moe/gk6e7x.jpg)

Portfolio website modern dan interaktif untuk Nimzz, siswa SMK Muhammadiyah 10 Masaran yang passionate dalam Web Development dan Video Editing. Dibangun dengan teknologi web terbaru dan desain yang eye-catching.

## ✨ Fitur Utama

### 🎨 **Desain Premium**
- **Dark Mode Modern** dengan gradient warna pink-orange
- **Animasi Smooth** dengan CSS3 dan JavaScript
- **Glassmorphism Effect** pada card components
- **Background Particles** yang interaktif
- **Responsive Design** untuk semua device

### 🌐 **Multi-Language Support**
- **Bilingual Website** (Indonesia & English)
- **Language Switcher** yang user-friendly
- **Auto-save preference** menggunakan Local Storage

### 💼 **Sections Lengkap**
1. **Hero Section** - Perkenalan dengan foto custom
2. **About Section** - Profil dan statistik
3. **Programming Languages** - Skill pemrograman dengan progress bars
4. **Editing Apps** - Tools editing (Alight Motion, CapCut, Canva)
5. **Skills Section** - Tabbed skills (Web Dev, Video Editing, Design)
6. **Projects Section** - Filterable project gallery
7. **Timeline Section** - Perjalanan belajar dengan animasi
8. **Contact Section** - Form kontak yang interaktif

### ⚡ **Teknologi yang Digunakan**
- **HTML5** - Struktur semantic
- **CSS3** - Styling dengan custom properties & animations
- **JavaScript (Vanilla)** - Interaktivitas tanpa framework
- **Font Awesome** - Icons library
- **Google Fonts (Inter)** - Typography modern

## 🛠️ Cara Menjalankan

### **Opsi 1: Deploy ke Vercel (Recommended)**
1. Fork repository ini
2. Buat akun di [Vercel](https://vercel.com)
3. Connect dengan GitHub
4. Import repository ini
5. Deploy dengan satu klik!

### **Opsi 2: Local Development**
```bash
# Clone repository
git clone https://github.com/yourusername/nimzz-portfolio.git

# Masuk ke folder
cd nimzz-portfolio

# Buka di browser (cukup buka file index.html)
# Atau gunakan Live Server di VS Code
```

Opsi 3: GitHub Pages

1. Push ke repository GitHub
2. Go to Settings > Pages
3. Pilih branch main dan folder /root
4. Save dan tunggu deploy

📁 Struktur File

```
nimzz-portfolio/
├── index.html              # File utama (SEMUA KODE DI SINI)
├── README.md               # Dokumentasi ini
└── assets/                 # (Opsional) Folder untuk assets
    ├── images/             # Simpan gambar custom di sini
    └── fonts/              # Font custom jika ada
```

🎯 Fitur Khusus untuk Nimzz

Profil Pemula yang Realistis

· Skill level sesuai kemampuan siswa SMK
· Fokus pada tools yang benar-benar digunakan (Alight Motion, etc.)
· Proyek-proyek yang sesuai dengan level pemula

Custom Assets

· Logo custom dari URL: https://files.catbox.moe/z001aw.jpg
· Foto profil dari URL: https://files.catbox.moe/gk6e7x.jpg

Editing Specialties

· Jedag-jedug effects dengan Alight Motion
· Typography animation untuk video
· GFX dan motion graphics
· Thumbnail design dengan Canva

🔧 Customization Guide

Ganti Foto/Logo

```html
<!-- Ganti URL foto di Hero Section -->
<img src="https://files.catbox.moe/gk6e7x.jpg" alt="Your Photo">

<!-- Ganti URL logo di Navbar -->
<img src="https://files.catbox.moe/z001aw.jpg" alt="Your Logo">
```

Update Informasi Pribadi

Edit bagian-bagian berikut di file HTML:

1. Nama & Title - Di Hero Section
2. About Text - Di About Section
3. Contact Info - Di Contact Section
4. Social Media Links - Di Footer

Tambah Proyek Baru

```html
<!-- Template project card -->
<div class="project-card" data-category="web">
    <div class="project-img">
        <img src="URL_GAMBAR" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span>Tag1</span>
            <span>Tag2</span>
        </div>
        <div class="project-links">
            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#"><i class="fab fa-github"></i> Source Code</a>
        </div>
    </div>
</div>
```

📱 Responsive Breakpoints

· Desktop: > 1200px
· Tablet: 768px - 1199px
· Mobile: < 767px

🎨 Color Palette

```css
:root {
    --primary: #FF6B8B;      /* Pink utama */
    --primary-dark: #FF4757; /* Pink gelap */
    --secondary: #2ED573;    /* Hijau */
    --accent: #FFA502;       /* Orange */
    --dark: #1A1A2E;         /* Dark blue */
    --darker: #0F0F1E;       /* Darker blue */
}
```

📊 Performance Optimizations

· Single HTML file - Minimize HTTP requests
· CSS minification via built-in optimization
· Lazy loading untuk images
· Efficient animations dengan hardware acceleration

🤝 Kontribusi

Portfolio ini adalah single-file HTML yang siap pakai. Untuk kontribusi:

1. Fork repository
2. Buat branch fitur baru
3. Commit perubahan
4. Push ke branch
5. Buat Pull Request

📄 License

MIT License - Silakan gunakan, modifikasi, dan distribusikan sesuai kebutuhan.

👤 Tentang Developer

Nimzz - Siswa SMK Muhammadiyah 10 Masaran

· 🎓 Jurusan: Rekayasa Perangkat Lunak
· 💻 Skills: Web Development (Beginner), Video Editing
· 🎨 Tools: Alight Motion, CapCut, Canva
· 📍 Location: Sragen, Jawa Tengah

🌐 Live Demo

https://vercel.com/button

Link live demo akan muncul setelah deploy ke Vercel

---

📞 Hubungi

· 📧 Email: nimzz.smkm10@gmail.com
· 📱 WhatsApp: +62 812 3456 7890
· 🏫 Sekolah: SMK Muhammadiyah 10 Masaran

---

⭐ Jika portfolio ini membantu, berikan star di repository! ⭐

```

## 🚀 Versi Pendek untuk GitHub Description:
```markdown
🎨 Portfolio website modern untuk Nimzz - Siswa SMK Muhammadiyah 10 Masaran

✨ Features:
- 🎯 Bilingual (ID/EN) dengan language switcher
- 📱 Fully responsive & mobile-friendly  
- 🎨 Dark mode dengan gradient pink-orange
- ⚡ Single HTML file - siap deploy ke Vercel
- 💼 Sections lengkap: Skills, Projects, Timeline
- 🎬 Special focus on Video Editing (Alight Motion, CapCut)

🛠️ Tech Stack: HTML5, CSS3, JavaScript (Vanilla)

🚀 One-click deploy to Vercel!
```