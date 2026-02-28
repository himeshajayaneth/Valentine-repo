<div align="center">

# 💝 Valentine & Birthday Card Collection

### *Beautiful interactive web cards crafted with love* 💌

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-pink?style=for-the-badge)](LICENSE)

<br>

*Send someone special a card they’ll never forget — no app, no install, just pure love in a browser.* 🌹

</div>

---

## 📁 What’s Inside

| 🗂️ Project | 💬 Description | ✨ Highlight |
|---|---|---|
| 💘 [Valentine Card](#-valentine-card) | Interactive Valentine’s Day card | Runaway “No” button |
| 🎂 [Birthday Card — Horizontal](#-birthday-card--horizontal) | Full-screen page-slide birthday card | 11-page swipeable experience |
| 🎂 [Birthday Card — Vertical](#-birthday-card--vertical) | Scroll-based birthday card | Classic one-page flow |

---

## 💘 Valentine Card

> *“Will you be my Valentine?”* — but the **No** button won’t let them say no. 😏

A fun, interactive Valentine’s Day card that makes saying no impossible. Hover over the “No” button and watch it panic and run away! 🏃💨

### ✨ Features
- 💕 Sweet animated Valentine message with a cute GIF
- 🙅 **“No” button runs away** on hover / tap (mobile friendly too!)
- 🎉 A delightful **“Yes” celebration page** with confetti
- 📱 Fully responsive — works on all screen sizes
- 🎨 Soft pink aesthetic with smooth animations

### 📂 Files
```
Valentine Card/
└── index.html      ← Everything in one file, zero dependencies
```

---

## 🎂 Birthday Card — Horizontal

> *11 pages of love, one swipe at a time.* 🥑7

A comprehensive, immersive birthday card split into **11 full-screen pages**. Navigate by swiping, clicking arrows, or pressing keyboard keys.

### ✨ Features
- 🧭 **Page-slide navigation** — swipe, click arrows, or use ← → keys
- 🟠 **Page dot indicators** + live page counter (e.g. `3 / 11`)
- 🎊 **Confetti cannon** fires on load & when you blow the candles
- 🎵 **Happy Birthday melody** via Web Audio API (no audio files needed!)
- 🎈 Floating balloons & twinkling sparkles in the background
- 🌸 Light warm-pink theme with Nunito + Sacramento + Dancing Script fonts

### 📖 Pages at a Glance

| # | Page | What’s There |
|---|------|-------------|
| 1 | 🎂 Hero | Animated cake, gradient title, subtitle |
| 2 | 🎀 Flip Card | 3D flip-on-tap birthday card |
| 3 | 💌 Love Letter | Handwritten-style paper letter with stamp |
| 4 | 💖 Reasons I Love You | Auto-advancing carousel (10 reasons) |
| 5 | 🕰️ Our Journey | Staggered timeline of memories |
| 6 | 🌟 Birthday Wishes | 6-card wishes wall |
| 7 | 🎯 Fun Quiz | 4-question interactive quiz with scoring |
| 8 | 🤞 Promises | 8 animated promise cards |
| 9 | 📸 Photo Gallery | 6-slot gallery (replace with your real photos!) |
| 10 | ⏳ Time Counter | Live counter since the day you two met |
| 11 | ❤️ Final Wish | Grand finale + Blow The Candles! 🕯️ |

### 🎮 Navigation Controls

| Action | How |
|--------|-----|
| Next page | `→` arrow button · Swipe left · `→` / `↓` key |
| Previous page | `←` arrow button · Swipe right · `←` / `↑` key |
| Jump to any page | Click any dot in the bottom nav bar |

### 📂 Files
```
Birthday Card-Horizontal/
└── index.html      ← Single self-contained file
```

---

## 🎂 Birthday Card — Vertical

> *All the love, in one beautiful scroll.* 📜

The same heartfelt content as the Horizontal card, delivered as a classic **single-page scroll experience** — great for sharing as a simple link.

### ✨ Features
- 📜 Smooth scroll-reveal animations as you scroll down
- 🌸 Warm light-pink aesthetic throughout
- 🎊 Confetti, floating balloons & birthday melody included
- 📱 Fully mobile responsive with fine-tuned breakpoints

### 📂 Files
```
Birthday Card-Vertical/
└── index.html      ← Single self-contained file
```

---

## 🚀 How To Use

### Option 1 — Open Locally
```bash
# Clone the repo
git clone https://github.com/himeshajayaneth/Valentine-repo.git

# Open any card directly in your browser
start "Valentine Card/index.html"
start "Birthday Card-Horizontal/index.html"
```

### Option 2 — Share via GitHub Pages 🌐
Deploy in seconds and share the link!

1. Go to **Settings → Pages**
2. Set source to `main` branch, `/ (root)` folder
3. Copy your URL and send it to your special someone 💌

---

## 🛠️ Personalization

Open any `index.html` and find the **CONFIG** block near the top of the `<script>` tag:

```js
// ─── CONFIG (Customize these!) ───
const PARTNER_NAME = "My Love";            // ← Change to their name
const DATE_WE_MET  = new Date(2024, 0, 1); // ← Your special date (year, month-1, day)
```

### 📸 Replace Gallery Placeholder Photos

```html
<!-- Replace this placeholder: -->
<div class="placeholder-photo">📷<span>Our first photo</span></div>

<!-- With a real image: -->
<img src="your-photo.jpg" alt="Our first photo" style="width:100%;height:100%;object-fit:cover;">
```

---

## 🎨 Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure & semantic markup |
| **CSS3** | Animations, transitions, flex/grid, glassmorphism effects |
| **Vanilla JavaScript** | Navigation, carousel, quiz engine, confetti, audio |
| **Google Fonts** | Nunito · Sacramento · Dancing Script |
| **Font Awesome 6** | Icons throughout the UI |
| **Web Audio API** | Happy Birthday melody — zero audio file downloads |
| **Canvas API** | Confetti particle system |

> 🚫 **Zero dependencies** — no npm, no build step, no frameworks.
> Clone → Open → Share. That’s it.

---

## 🐣 Easter Egg

On any Birthday Card page, type **`iloveyou`** on your keyboard and watch what happens... 🎊✨

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
Feel free to fork, customize, and send love to whoever deserves it. 💕

---

<div align="center">

Made with 💖 by [himeshajayaneth](https://github.com/himeshajayaneth)

*If this put a smile on someone’s face, it did exactly what it was made to do.* 🌸

<br>

⭐ **Star this repo** if you found it sweet — it means a lot!

</div>
