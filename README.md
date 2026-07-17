# Praruj Thapa — Portfolio Website

> Personal portfolio for **Praruj Thapa**, Machine Learning & Computer Vision Engineer based in Osaka, Japan.

🔗 **Live site:** [PRaruj.github.io/praruj-portfolio](https://PRaruj.github.io/praruj-portfolio)

---

## Features

- **Bilingual (EN / 日本語)** — full language toggle, every section translates including nav, descriptions, dates, and labels. Built for Japanese recruiters.
- **Dark terminal aesthetic** — hacker-style design with scanline overlay, green-on-black palette, and monospace typography.
- **Active nav on scroll** — nav link for the current section highlights automatically as you scroll.
- **Responsive + mobile menu** — hamburger menu on small screens, single-column layout on mobile.
- **CV download button** — links to `cv.pdf` in the repo root.
- **Open Graph meta tags** — clean link previews when shared on LinkedIn, Discord, or Twitter.
- **Zero dependencies** — pure HTML, CSS, and vanilla JS. No frameworks, no build step.

---

## Sections

| # | Section | 日本語 |
|---|---------|--------|
| 01 | About | 自己紹介 |
| 02 | Work Experience | 職務経験 |
| 03 | Projects | プロジェクト |
| 04 | Skills | スキル |
| 05 | Education | 学歴 |
| 06 | Contact | 連絡 |

---

## Project Highlights

**Automated Cap Opening & Closing Mechanism** — Capstone project with Shimadzu Corporation. Automated screw-type lab container caps using SolidWorks CAD, Arduino, servo motors, IR sensors, and electromagnets. 🏆 *Capstone Exhibition Award 2025*

**Smart Showcase Management System** — Industry project with フクシマガリレイ株式会社. Real-time shelf monitoring using Raspberry Pi + computer vision. Reduced manual stock checks for retail stores. 🏆 *Pre-Capstone Exhibition Award*

**ML & CV Learning Projects** — Personal GitHub repository documenting machine learning experiments and computer vision implementations from fundamentals to advanced models.

---

## Tech Stack

```
HTML5  ·  CSS3 (custom properties, grid, flexbox)  ·  Vanilla JS
Fonts: Share Tech Mono · Rajdhani · Noto Sans JP (Google Fonts)
Hosted: GitHub Pages
```

---

## Getting Started

No build tools needed — just open `index.html` in a browser.

```bash
git clone https://github.com/PRaruj/praruj-portfolio.git
cd praruj-portfolio
open index.html        # macOS
# or just drag into your browser
```

### Adding your CV

Place your CV as `cv.pdf` in the repo root. The **Download CV** button in the hero will automatically link to it.

```
praruj-portfolio/
├── index.html
└── README.md
```

### Updating content

All content is in `index.html`. Each translated element uses `data-en` and `data-ja` attributes:

```html
<h2 data-en="About Me" data-ja="自己紹介">About Me</h2>
```

The JS reads these on toggle — just update both attributes and you're done.

---

## Deployment

This site is deployed via **GitHub Pages**.

1. Push changes to the `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://PRaruj.github.io/praruj-portfolio`

---

## Contact

- 📧 thapa.praruj@gmail.com
- 💼 [linkedin.com/in/praruj-thapa](https://www.linkedin.com/in/praruj-thapa/)
- 🐙 [github.com/PRaruj](https://github.com/PRaruj)
