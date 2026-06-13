 🌐 Hardika Raut — Developer Portfolio

> Personal portfolio website of **Hardika Raut** — Full Stack Developer & MCA student from Pune, Maharashtra.  
> Built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step — just open and deploy.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-00D4FF?style=for-the-badge&logo=vercel&logoColor=black)](https://https://portfoliohardikaraut.vercel.app/)
[![Made With](https://img.shields.io/badge/Made%20With-HTML%20%7C%20CSS%20%7C%20JS-C4B5FD?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-34D399?style=for-the-badge)](#license)

---

✨ Features

- **Animated hero section** — rotating 3D tech globe with orbital rings, floating skill chips, and a typed-text role switcher
- **Custom cursor** — glowing dot + lagging ring, expands on hover, bursts on click
- **Particle trail** — colorful glowing particles stream behind the cursor with speed-based intensity
- **Card tilt effect** — 3D perspective tilt on project, skill, about, and cert cards on hover
- **Magnetic buttons** — CTA buttons gently pull toward the cursor
- **Ripple on click** — wave animation on all interactive buttons
- **Scroll reveal** — sections fade up into view as you scroll
- **Spotlight glow** — subtle radial light follows the cursor across the page
- **Certification filter tabs** — filter 18 certificates by issuer (Google, NPTEL, IBM, IIT Bombay, etc.)
- **Publications section** — two peer-reviewed research papers with journal metadata
- **Fully responsive** — mobile-friendly layout, visual effects gracefully disabled on small screens
- **Single-file deployment** — photo embedded as base64, no external assets required

---

📁 Project Structure

```
portfolio/
└── index.html        # Entire portfolio — HTML + CSS + JS in one file
└── README.md         # This file
```

> The profile photo is base64-encoded directly into `index.html`, so **no separate image files are needed**.

---

 🧩 Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | **Hero** | Name, animated role, 3D globe visual, stats |
| 02 | **About** | Bio, profile photo, education & contact cards |
| 03 | **Skills** | Bento-grid layout of languages, frameworks, tools |
| 04 | **Experience** | Timeline — Full Stack Intern @ Peakprosys Solutions |
| 05 | **Projects** | EmoLearn, System Integration Solution, Pizza Restro |
| 06 | **Publications** | 2 peer-reviewed research papers (IRE Journals, IJSREM) |
| 07 | **Certifications** | 18 certificates with live links, filterable by issuer |
| 08 | **Contact** | Email, LinkedIn, GitHub, Phone |

---

🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, keyframe animations) |
| Scripting | Vanilla JavaScript (ES6+, Canvas API, IntersectionObserver) |
| Fonts | Space Grotesk · Inter · JetBrains Mono (Google Fonts) |
| Icons | SVG inline icons |
| Animation | Canvas 2D API (globe), CSS keyframes (chips, cursor, reveal) |


# 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--navy` | `#0A0F1E` | Page background |
| `--navy2` | `#111827` | Alternate section bg |
| `--card` | `#141B2D` | Card backgrounds |
| `--cyan` | `#00D4FF` | Primary accent |
| `--lavender` | `#C4B5FD` | Secondary accent |
| `--green` | `#34D399` | Success / status |
| `--white` | `#F8FAFC` | Body text |
| `--muted` | `#94A3B8` | Muted / meta text |

**Fonts:** Space Grotesk (headings) · Inter (body) · JetBrains Mono (code / labels)

---

📄 Customisation

Want to adapt this portfolio for yourself? Here's what to edit in `index.html`:

| What | Where in file |
|------|--------------|
| Name & role | Hero `<h1>` and `roles[]` array in JS |
| Description | `.hero-desc` paragraph |
| Profile photo | `<img src="data:image/jpeg;base64,...">` in About |
| About text | `.about-text` paragraphs |
| Education cards | `.about-card` divs |
| Skills | `.pill-group` spans in Skills section |
| Experience | `.timeline-item` in Experience section |
| Projects | `.project-card` divs in Projects section |
| Publications | `.pub-card` divs in Publications section |
| Certifications | `.cert-card` divs in Certifications section |
| Contact links | `.contact-link` anchors |
| Color theme | `:root` CSS variables at top of `<style>` |

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).  
Feel free to fork, adapt, and use it as a base for your own portfolio — a credit or star is always appreciated! ⭐

---

<div align="center">
  <sub>Designed & built by <strong>Hardika Raut</strong> · Pune, Maharashtra 🇮🇳</sub>
</div>
