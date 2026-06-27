# 🛡️ Balamurugan — Cybersecurity Portfolio

> **Personal portfolio website for Balamurugan A. — SOC Analyst & Blue Team Specialist**

[![Live Site](https://img.shields.io/badge/Live-Portfolio-00e5ff?style=for-the-badge&logo=googlechrome&logoColor=white)](https://balabm7.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/balamurugan-a-3581a120b)
[![GitHub](https://img.shields.io/badge/GitHub-BALAbm7-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BALAbm7)

---

## 📌 Overview

A cyberpunk-themed single-page portfolio built with pure **HTML, CSS, and Vanilla JavaScript** — no frameworks, no build tools, zero dependencies beyond Google Fonts. Designed to reflect a blue team security mindset: precise, clean, and intentional.

Features a live matrix rain canvas background, custom animated cursor, scroll-triggered fade-ins, animated stat counters, and a fully responsive layout.

---

## 🗂️ Repository Structure

```
portfolio-balamurugan/
│
├── index.html          # Main portfolio (single-file, self-contained)
├── README.md           # This file
├── .gitignore          # Standard web project gitignore
└── assets/             # (Optional) Place custom favicon, OG image, resume PDF here
    ├── favicon.ico
    ├── og-image.png
    └── resume.pdf
```

> **Note:** The portfolio is intentionally single-file (`index.html`). All CSS and JS are inlined for zero-dependency deployment.

---

## ✨ Features

| Feature | Details |
|---|---|
| **Matrix Rain Background** | Canvas-drawn katakana + binary rain at 13% opacity |
| **Custom Cursor** | Laggy ring + sharp dot, expands on interactive elements |
| **Scanline Overlay** | Subtle CRT scanline effect via CSS animation |
| **Scroll Fade-in** | `IntersectionObserver`-based section reveal |
| **Animated Counters** | Stats animate up when scrolled into view |
| **Cyber Navbar** | Glassmorphism nav with `//` prefix hover effects |
| **Responsive Layout** | Mobile-friendly grid collapse via CSS |
| **Zero JS Frameworks** | Pure Vanilla JS — no React, no Vue, no jQuery |

---

## 🚀 Deployment

### GitHub Pages (Recommended — Free)

```bash
# 1. Fork or clone this repo
git clone https://github.com/BALAbm7/portfolio.git
cd portfolio

# 2. Push to your GitHub repo
git remote set-url origin https://github.com/<your-username>/portfolio.git
git push -u origin main

# 3. Enable GitHub Pages
# Go to: Settings → Pages → Source → Branch: main → Folder: / (root) → Save
# Your site will be live at: https://<your-username>.github.io/portfolio
```

### Local Preview

No build step needed. Just open the file:

```bash
# macOS / Linux
open index.html

# Or serve locally with Python
python3 -m http.server 8080
# Then visit: http://localhost:8080
```

---


## 📜 Tech Stack

```
HTML5          → Structure & semantic markup
CSS3           → Custom properties, Grid, Flexbox, animations
Vanilla JS     → Canvas API, IntersectionObserver, cursor animation
Google Fonts   → Orbitron, Rajdhani, Share Tech Mono (CDN)
```

---

## 👤 About Me

**Balamurugan A.** — SOC Analyst with 2+ years in Blue Team Security Operations.

Specialized in Microsoft Sentinel (KQL), Microsoft Defender for Endpoint, SentinelOne, Cortex XDR, Zscaler ZIA/ZPA, Awake Security (NDR), and Armis (OT/IoT).

Certified: **SC-200** · **ISC2 CC** · **AWS SAA-C03**

📂 Blue Team Portfolio → [github.com/BALAbm7/BlueForge](https://github.com/BALAbm7)  

---

*Built with intent. Secured by design.*
