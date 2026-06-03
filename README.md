<div align="center">

<img src="https://img.shields.io/badge/FED-KIIT-FF6B00?style=for-the-badge&labelColor=0D0D1A&color=FF6B00" alt="FED KIIT"/>

# 🔥 FED KIIT — Homepage Redesign

**A bold, modern, fully interactive homepage for the Federation of Entrepreneurship Development, KIIT TBI.**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-View_Site-FF6B00?style=for-the-badge&labelColor=0D0D1A)](https://akshatanand.github.io/fed-kiit-homepage/)
[![HTML](https://img.shields.io/badge/HTML5-Single_File-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![CSS](https://img.shields.io/badge/CSS3-Pure_Vanilla-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![JS](https://img.shields.io/badge/JavaScript-No_Frameworks-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()

<br/>

> *Submitted for the **FED UI/UX Design Challenge 2026** — FED Entrepreneurship & Skill Development Program, KIIT University*

<br/>

---

</div>

## ✨ Features at a Glance

| Feature | Details |
|---|---|
| 🎨 **Dark / Light Mode** | Toggle with smooth CSS variable transitions |
| 🖱️ **Custom Cursor** | Magnetic ring cursor with hover scale effects |
| 📊 **Live Progress Bar** | Scroll-linked gradient progress indicator |
| 🌌 **Particle Canvas** | 130-node animated network with connecting lines |
| 📱 **Fully Responsive** | Mobile hamburger nav, fluid typography via `clamp()` |
| 🔢 **Count-Up Animations** | Intersection Observer–driven number counters |
| 👁️ **Scroll Reveal** | Staggered fade-in for every section as you scroll |
| 🏗️ **5-Page SPA** | Home · About · Programs · Events · Contact |
| ⚡ **Zero Dependencies** | Pure HTML + CSS + Vanilla JS — no libraries, no build step |

---

## 🖼️ Preview

<div align="center">

### 🌑 Dark Mode
```
╔══════════════════════════════════════════════════════════╗
║  🔥 FED KIIT          Home  About  Programs  Events  ☀️  ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║         ░░ ·  ·  ░  ·   ░   ·  ░  ·   ░   ·  ░  ·     ║
║       ·  ░   · ░    ·  ░   ·   ░    ·   ░    ·          ║
║                                                          ║
║              Federation of                               ║
║            ████████████████                              ║
║              Entrepreneurship                            ║
║                                                          ║
║         [ Join FED ]    [ Explore Programs ]             ║
║                                                          ║
║      500+Members   40+Events   12+Programs   6+Years     ║
╚══════════════════════════════════════════════════════════╝
```

</div>

---

## 🏗️ Project Structure

```
fed-kiit-homepage/
│
└── index.html          ← Entire site — HTML + CSS + JS in one file
```

> All styles and scripts are self-contained. No external dependencies beyond **Google Fonts** (Syne + Outfit).

---

## 🎯 Pages Included

```
🏠  Home        →  Hero with particle canvas, stats counter, domain cards, events preview
👥  About       →  Story, rotating orbit visual, pillars, team grid
📚  Programs    →  Domain program cards with hover effects
📅  Events      →  Timeline-style upcoming & past events
📬  Contact     →  Contact form + social links
```

---

## 🚀 Getting Started

### Option 1 — Just open it
```bash
# Clone the repo
git clone https://github.com/akshatanand/fed-kiit-homepage.git

# Open directly in browser — no server needed!
open index.html
```

### Option 2 — Live Server (recommended for development)
```bash
# Using VS Code Live Server extension, or:
npx serve .
```

---

## 🛠️ Tech Stack

```
┌─────────────────────────────────────────────┐
│                                             │
│   HTML5        —  Semantic structure        │
│   CSS3         —  Custom properties,        │
│                   Grid, Flexbox,            │
│                   @keyframes               │
│   Vanilla JS   —  Canvas API,              │
│                   IntersectionObserver,     │
│                   requestAnimationFrame     │
│   Google Fonts —  Syne (headings)          │
│                   Outfit (body)            │
│                                             │
└─────────────────────────────────────────────┘
```

---

## 💡 Design Decisions

- **`clamp()` typography** — headings scale fluidly from mobile to 4K, no breakpoint hacks
- **CSS custom properties** — entire theme (dark/light) switches with a single `data-theme` attribute flip
- **`IntersectionObserver`** — scroll reveals and counters fire only when in viewport, zero scroll event overhead
- **Canvas particles** — 130 nodes with proximity-linked edges, pure `requestAnimationFrame` loop, no canvas library
- **Single file** — zero build toolchain; works offline, embeds anywhere, submittable as-is

---

## 🏆 Challenge Submission

| Field | Value |
|---|---|
| **Challenge** | FED UI/UX Design Challenge 2026 |
| **Program** | FED Entrepreneurship & Skill Development Program |
| **Institute** | KIIT University — TBI |
| **Submitted by** | Akshat Anand |
| **Contact** | akshatanandkiit@gmail.com |

---

## 📄 License

This project was built as a design challenge submission for **FED KIIT**.  
Feel free to use it as inspiration — credit appreciated! 🧡

---

<div align="center">

**Built with 🧡 for FED KIIT · KIIT TBI**

*© 2026 FED KIIT. All rights reserved.*

</div>
