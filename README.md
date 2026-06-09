
<div align="center">

<svg width="640" height="160" viewBox="0 0 640 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="vg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#5B54A8"/>
      <stop offset="50%"  stop-color="#9D97DC"/>
      <stop offset="100%" stop-color="#5B54A8"/>
    </linearGradient>
    <linearGradient id="bg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"   stop-color="#13141A"/>
      <stop offset="100%" stop-color="#0D0E12"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- background -->
  <rect width="640" height="160" rx="14" fill="url(#bg)"/>

  <!-- corner diamonds -->
  <polygon points="18,12 24,18 18,24 12,18" fill="none" stroke="#7B73C8" stroke-width="1.2"/>
  <polygon points="622,12 628,18 622,24 616,18" fill="none" stroke="#7B73C8" stroke-width="1.2"/>
  <polygon points="18,136 24,142 18,148 12,142" fill="none" stroke="#7B73C8" stroke-width="1.2"/>
  <polygon points="622,136 628,142 622,148 616,142" fill="none" stroke="#7B73C8" stroke-width="1.2"/>

  <!-- top & bottom rules -->
  <line x1="36" y1="18" x2="604" y2="18" stroke="#2E3038" stroke-width="0.8"/>
  <line x1="36" y1="142" x2="604" y2="142" stroke="#2E3038" stroke-width="0.8"/>

  <!-- center diamond -->
  <polygon points="320,22 327,29 320,36 313,29" fill="#7B73C8" fill-opacity="0.25" stroke="#7B73C8" stroke-width="1"/>

  <!-- main title -->
  <text x="320" y="90"
        font-family="'Courier New', monospace"
        font-size="38"
        font-weight="700"
        letter-spacing="14"
        text-anchor="middle"
        fill="url(#vg)"
        filter="url(#glow)">PLATINUMAI</text>

  <!-- subtitle -->
  <text x="320" y="122"
        font-family="'Courier New', monospace"
        font-size="11"
        font-weight="400"
        letter-spacing="8"
        text-anchor="middle"
        fill="#8890A2">✦  THE PROMPTING BIBLE  ✦</text>
</svg>

**World-class image direction for GPT-Image-2.**  
Nineteen sections built from real production prompting — not beginner tutorials.  
Built for you to think like a senior art director, not a wishlist writer.

[![Deploy with Vercel](https://img.shields.io/badge/Deploy%20with-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com)
[![HTML](https://img.shields.io/badge/HTML-Single%20File-7B73C8?style=flat-square)](./index.html)
[![License](https://img.shields.io/badge/License-Private-B8BDC8?style=flat-square)]()

</div>

---

## ◆ What This Is

A single-file interactive reference guide for crafting professional prompts for AI image generation. Every section is structured around real production workflows — the same patterns used by senior art directors and visual designers.

---

## ◆ Sections

| # | Section | Topic |
|---|---------|-------|
| 00 | 📖 How to use this | Read this first |
| 01 | 🧠 How the system reads prompts | Mental model |
| 02 | 💡 Lighting | The biggest quality lever |
| 03 | 📷 Camera & composition | Lens, framing, depth |
| 04 | 👁️ Skin, eyes, hair | Portrait realism |
| 05 | 💎 Material rendering (PBR) | Surface & texture |
| 06 | 🤖 3D & robots | Hard-surface & mecha |
| 07 | 📦 Product photography | Studio & commercial |
| 08 | 🔤 Brand & typography | Logo & type treatment |
| 09 | 🎨 Style clusters | Aesthetic direction |
| 10 | 🔓 Hidden tricks | Pro patterns |
| 11 | 🚫 Negative prompting | What to exclude |
| 12 | 🔄 Iteration protocols | Refining output |
| 13 | 🖼️ Reference images | Using refs effectively |
| 14 | 📐 Aspect ratios | Resolution & framing |
| 15 | ⚠️ Failure modes | What breaks and why |
| 16 | 🧬 Things you didn't ask | Hidden depth |
| 17 | 🎯 Master template | The one template |
| 18 | ✨ 10 practice prompts | Copy. Paste. Run. |
| 19 | ⚡ Custom Instructions | Permanent setup |

---

## ◆ Stack

```
Pure HTML · CSS · Vanilla JS
No framework. No build step. No dependencies.
```

---

## ◆ Run Locally

```bash
npx serve .
```

Open `http://localhost:3000`

---

## ◆ Deploy to Vercel

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "PlatinumAI Master Prompting Bible"
git remote add origin YOUR_REPO_URL
git push -u origin main

# 2. Import on vercel.com → select repo → deploy
# No build settings needed. Vercel auto-detects static HTML.
```

---

## ◆ Project Structure

```
/
├── index.html          ← entire app (styles + content + JS)
├── images/             ← section banner images
│   ├── s02-lighting.png
│   ├── s03-camera.png
│   ├── s04-skin.png
│   ├── s05-pbr.png
│   ├── s06-robots.png
│   ├── s07-product.png
│   ├── s08-brand.png
│   ├── s09-style.png
│   ├── s10-hidden.png
│   ├── s11-negative.png
│   ├── s12-iteration.png
│   ├── s13-reference.png
│   ├── s14-aspect.png
│   ├── s16-things.png
│   ├── s17-template.png
│   ├── s18-practice.png
│   └── s19-custom.png
└── README.md
```

---

<div align="center">

```
   ◈  ━━━━━━━━━━━━━━━━━━━━━━━━━━  ◈
        Built by  P L A T I N U M A I
             Wyoming  ·  2026
           " You  Always  Win "
   ◈  ━━━━━━━━━━━━━━━━━━━━━━━━━━  ◈
```

</div>
