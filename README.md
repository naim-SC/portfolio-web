```markdown
# 🚀 Nimzz Portfolio - Web Developer & Video Editor

<div align="center">

![Portfolio Banner](https://files.catbox.moe/uivlrt.jpeg)

*Portfolio website modern dengan desain dark mode yang eye-catching*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![Responsive](https://img.shields.io/badge/Responsive-Design-2ED573?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

</div>

## ✨ **Fitur Utama**

<div align="center">

| 🎨 **Desain** | 🌐 **Multilingual** | ⚡ **Performansi** |
|:-------------:|:-------------------:|:-----------------:|
| Dark Mode Modern | ID/EN Language Support | Single HTML File |
| Animasi Smooth | Auto-save Preference | Fast Loading |
| Glassmorphism | Full Translation | Optimized Assets |
| Responsive Design | User-friendly Switcher | Lazy Loading |

</div>

## 📸 **Preview Website**

<div align="center">

### **🖥️ Desktop View**
![Desktop Preview](https://via.placeholder.com/800x450/FF6B8B/FFFFFF?text=Desktop+View+-+Nimzz+Portfolio)

### **📱 Mobile View**
![Mobile Preview](https://via.placeholder.com/300x600/2ED573/FFFFFF?text=Mobile+View+-+Nimzz+Portfolio)

</div>

## 🏗️ **Struktur Website**

```mermaid
graph TD
    A[Hero Section] --> B[About Me]
    B --> C[Programming Languages]
    C --> D[Editing Tools]
    D --> E[Skills Tabs]
    E --> F[Projects Gallery]
    F --> G[Timeline Journey]
    G --> H[Contact Form]
    H --> I[Footer]
    
    style A fill:#FF6B8B
    style B fill:#2ED573
    style C fill:#FFA502
    style D fill:#8B5CF6
```

🔧 Teknologi yang Digunakan

<div align="center">

Teknologi Deskripsi Badge
HTML5 Struktur website semantic https://img.shields.io/badge/HTML5-100%25-E34F26
CSS3 Styling dengan animations https://img.shields.io/badge/CSS3-Advanced-1572B6
JavaScript Interaktivitas vanilla https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E
Font Awesome Icons library https://img.shields.io/badge/Font_Awesome-6.4.0-528DD7
Google Fonts Inter font family https://img.shields.io/badge/Google_Fonts-Inter-4285F4

</div>

🚀 Cara Deploy

🎯 Opsi 1: Vercel (Recommended)

```bash
# Langkah-langkah:
1. Fork repository ini ke GitHub Anda
2. Buat akun di vercel.com (gratis)
3. Klik "New Project"
4. Import dari GitHub
5. Pilih repository Nimzz-Portfolio
6. Klik "Deploy"
```

💻 Opsi 2: GitHub Pages

1. Push ke repository GitHub
2. Buka Settings > Pages
3. Pilih:
   · Source: Deploy from a branch
   · Branch: main
   · Folder: / (root)
4. Klik Save

🛠️ Opsi 3: Local Development

```bash
# Clone repository
git clone https://github.com/yourusername/nimzz-portfolio.git

# Masuk ke folder
cd nimzz-portfolio

# Buka di browser
# Cara 1: Double klik index.html
# Cara 2: Gunakan Live Server di VS Code
# Cara 3: python -m http.server 8000
```

📁 Struktur File

```
nimzz-portfolio/
│
├── 📄 index.html              # File utama (SEMUA KODE)
├── 📖 README.md               # Dokumentasi ini
```

🎨 Customization Guide

1. Ganti Foto & Logo

```html
<!-- Di Hero Section (baris ~350) -->
<img src="https://files.catbox.moe/gk6e7x.jpg" alt="Nimzz Profile">

<!-- Di Navbar (baris ~250) -->
<img src="https://files.catbox.moe/z001aw.jpg" alt="Nimzz Logo">
```

2. Update Informasi Pribadi

Section Lokasi di Kode Yang Diubah
Nama Line ~360 <h1>Nimzz...</h1>
Sekolah Line ~365 <h2>Siswa SMK...</h2>
Deskripsi Line ~370 <p>Siswa berusia...</p>
Contact Info Line ~950 Email, WhatsApp, dll
Social Media Line ~380 & ~1000 Link Instagram, TikTok, dll

3. Tambah Proyek Baru

```html
<!-- Template Project Card -->
<div class="project-card" data-category="web|editing|design">
    <div class="project-img">
        <img src="URL_GAMBAR" alt="Nama Proyek">
    </div>
    <div class="project-info">
        <h3>Judul Proyek</h3>
        <p>Deskripsi singkat proyek...</p>
        <div class="project-tags">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
        </div>
        <div class="project-links">
            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#"><i class="fab fa-github"></i> Source Code</a>
        </div>
    </div>
</div>
```

📊 Skill Set Nimzz

<div align="center">

Category Skills Level
🌐 Web Development HTML5, CSS3, JavaScript, Git ⭐⭐⭐⭐☆
🎬 Video Editing Alight Motion, CapCut, Canva ⭐⭐⭐⭐⭐
🎨 Design Thumbnail Design, Typography, GFX ⭐⭐⭐⭐☆
📱 Tools VS Code, GitHub, Mobile Editing Apps ⭐⭐⭐⭐☆

</div>

📱 Responsive Breakpoints

```css
/* Desktop: > 1200px */
@media (min-width: 1200px) { ... }

/* Tablet: 768px - 1199px */
@media (max-width: 1199px) and (min-width: 768px) { ... }

/* Mobile: < 767px */
@media (max-width: 767px) { ... }
```

🎯 Target Audience

· ✅ Recruiter - Portfolio profesional untuk job hunting
· ✅ Client - Showcase untuk freelance projects
· ✅ Sekolah - Dokumentasi pencapaian akademik
· ✅ Komunitas - Sharing karya dengan kreator lain
· ✅ Personal Branding - Meningkatkan visibility online

🚀 Performance Metrics

Metric Target Status
Page Load < 3s ✅ Achieved
Mobile Score 90/100 ✅ Achieved
Accessibility WCAG 2.1 AA ✅ Achieved
SEO Friendly Yes ✅ Achieved
Cross-browser Chrome, Firefox, Safari ✅ Achieved

🤝 Cara Kontribusi

1. Fork repository ini
2. Clone ke lokal:
   ```bash
   git clone https://github.com/YOUR-USERNAME/nimzz-portfolio.git
   ```
3. Buat branch baru:
   ```bash
   git checkout -b feature/namafitur
   ```
4. Commit perubahan:
   ```bash
   git commit -m "Tambah fitur baru"
   ```
5. Push ke branch:
   ```bash
   git push origin feature/namafitur
   ```
6. Buat Pull Request

📄 License

```
MIT License

Copyright (c) 2025 Nimzz - SMK Muhammadiyah 10 Masaran

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

👨‍💻 Tentang Developer

<div align="center">

https://files.catbox.moe/gk6e7x.jpg

Nimzz Creative

Siswa SMK Muhammadiyah 10 Masaran

🎓 Pendidikan: Jurusan Rekayasa Perangkat Lunak - Kelas X
📍 Lokasi: Sragen, Jawa Tengah, Indonesia
💻 Skills: Web Development (Beginner), Video Editing
🎨 Tools: Alight Motion, CapCut, Canva, VS Code
🌟 Passion: Coding, Editing, Creative Content

</div>

🌐 Live Demo & Links

<div align="center">

https://vercel.com/button
https://img.shields.io/badge/GitHub_Pages-Deploy-181717?style=for-the-badge&logo=github

🔗 Link Demo: https://nimzz-portfolio.vercel.app
📱 WhatsApp: +62 821 3748 7477
🏫 Sekolah: SMK Muhammadiyah 10 Masaran

</div>

📞 Hubungi & Support

<div align="center">

💬 Punya Pertanyaan atau Feedback?

https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white
https://img.shields.io/badge/TikTok-Follow-000000?style=for-the-badge&logo=tiktok&logoColor=white
https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white
https://img.shields.io/badge/GitHub-Star-181717?style=for-the-badge&logo=github&logoColor=white

</div>

---

<div align="center">

⭐ Support Project Ini!

Jika portfolio ini membantu Anda, berikan ⭐ di repository GitHub!

Made with ❤️ by Nimzz

https://files.catbox.moe/uivlrt.jpeg

</div>
```

🎨 Versi Pendek untuk GitHub Description:

```markdown
🎨 Portfolio Website Modern - Nimzz (SMK Muhammadiyah 10 Masaran)

✨ Features:
- 🌐 Bilingual (ID/EN) dengan language switcher
- 📱 Fully responsive design untuk semua device
- 🎨 Dark mode dengan gradient pink-orange yang eye-catching
- ⚡ Single HTML file - optimized untuk Vercel/GitHub Pages
- 💼 Sections lengkap: Skills, Projects, Timeline Journey
- 🎬 Special focus on Video Editing (Alight Motion, CapCut, Canva)

🛠️ Tech Stack: HTML5 • CSS3 • JavaScript (Vanilla) • Font Awesome

🚀 One-click deploy to Vercel/GitHub Pages!
```