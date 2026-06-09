
<div align="center">

<svg width="800" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- violet title gradient -->
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#4A43A0"/>
      <stop offset="30%"  stop-color="#9D97DC"/>
      <stop offset="50%"  stop-color="#C8C4F0"/>
      <stop offset="70%"  stop-color="#9D97DC"/>
      <stop offset="100%" stop-color="#4A43A0"/>
    </linearGradient>
    <!-- border gradient -->
    <linearGradient id="borderGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#1E1F26"/>
      <stop offset="30%"  stop-color="#7B73C8"/>
      <stop offset="50%"  stop-color="#9D97DC"/>
      <stop offset="70%"  stop-color="#7B73C8"/>
      <stop offset="100%" stop-color="#1E1F26"/>
    </linearGradient>
    <!-- background -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"   stop-color="#161720"/>
      <stop offset="100%" stop-color="#0D0E12"/>
    </linearGradient>
    <!-- soft glow on title -->
    <filter id="softGlow" x="-20%" y="-40%" width="140%" height="180%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="6" result="blur"/>
      <feColorMatrix in="blur" type="matrix"
        values="0 0 0 0 0.48
                0 0 0 0 0.45
                0 0 0 0 0.80
                0 0 0 0.7 0" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- subtle glow on diamonds -->
    <filter id="dimGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- main background -->
  <rect width="800" height="220" rx="16" fill="url(#bgGrad)"/>

  <!-- outer border -->
  <rect x="1" y="1" width="798" height="218" rx="15.5" fill="none"
        stroke="url(#borderGrad)" stroke-width="1.2"/>

  <!-- inner border offset -->
  <rect x="10" y="10" width="780" height="200" rx="10" fill="none"
        stroke="#2A2B35" stroke-width="0.6"/>

  <!-- top center rule with gap for diamond -->
  <line x1="30" y1="28" x2="370" y2="28" stroke="url(#borderGrad)" stroke-width="0.8"/>
  <line x1="430" y1="28" x2="770" y2="28" stroke="url(#borderGrad)" stroke-width="0.8"/>

  <!-- bottom center rule with gap for diamond -->
  <line x1="30" y1="192" x2="370" y2="192" stroke="url(#borderGrad)" stroke-width="0.8"/>
  <line x1="430" y1="192" x2="770" y2="192" stroke="url(#borderGrad)" stroke-width="0.8"/>

  <!-- top center diamond -->
  <polygon points="400,18 410,28 400,38 390,28"
           fill="#7B73C8" fill-opacity="0.2"
           stroke="#9D97DC" stroke-width="1.2"
           filter="url(#dimGlow)"/>
  <polygon points="400,22 407,28 400,34 393,28"
           fill="#7B73C8" fill-opacity="0.4" stroke="none"/>

  <!-- bottom center diamond -->
  <polygon points="400,182 410,192 400,202 390,192"
           fill="#7B73C8" fill-opacity="0.2"
           stroke="#9D97DC" stroke-width="1.2"
           filter="url(#dimGlow)"/>
  <polygon points="400,186 407,192 400,198 393,192"
           fill="#7B73C8" fill-opacity="0.4" stroke="none"/>

  <!-- corner accent lines TL -->
  <line x1="16" y1="40" x2="16" y2="65" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <line x1="16" y1="40" x2="42" y2="40" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <!-- corner accent lines TR -->
  <line x1="784" y1="40" x2="784" y2="65" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <line x1="758" y1="40" x2="784" y2="40" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <!-- corner accent lines BL -->
  <line x1="16" y1="180" x2="16" y2="155" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <line x1="16" y1="180" x2="42" y2="180" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <!-- corner accent lines BR -->
  <line x1="784" y1="180" x2="784" y2="155" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>
  <line x1="758" y1="180" x2="784" y2="180" stroke="#7B73C8" stroke-width="0.8" opacity="0.6"/>

  <!-- decorative side dots -->
  <circle cx="30" cy="110" r="1.5" fill="#7B73C8" opacity="0.5"/>
  <circle cx="770" cy="110" r="1.5" fill="#7B73C8" opacity="0.5"/>
  <circle cx="22" cy="110" r="1" fill="#7B73C8" opacity="0.3"/>
  <circle cx="778" cy="110" r="1" fill="#7B73C8" opacity="0.3"/>

  <!-- eyebrow label -->
  <text x="400" y="62"
        font-family="'Courier New', monospace"
        font-size="9"
        letter-spacing="6"
        text-anchor="middle"
        fill="#4A4870"
        font-weight="400">◆  PLATINUM AI TECH GROUP  ◆</text>

  <!-- main PLATINUMAI title -->
  <text x="400" y="130"
        font-family="Georgia, 'Times New Roman', serif"
        font-size="52"
        font-weight="700"
        letter-spacing="16"
        text-anchor="middle"
        fill="url(#titleGrad)"
        filter="url(#softGlow)">PLATINUMAI</text>

  <!-- divider line between title and subtitle -->
  <line x1="160" y1="150" x2="640" y2="150" stroke="#2E3038" stroke-width="0.8"/>
  <circle cx="160" cy="150" r="2" fill="#7B73C8" opacity="0.6"/>
  <circle cx="640" cy="150" r="2" fill="#7B73C8" opacity="0.6"/>
  <circle cx="400" cy="150" r="2.5" fill="#9D97DC" opacity="0.8"/>

  <!-- subtitle -->
  <text x="400" y="177"
        font-family="'Courier New', monospace"
        font-size="11"
        letter-spacing="9"
        text-anchor="middle"
        fill="#6B6590"
        font-weight="400">✦   THE  PROMPTING  BIBLE   ✦</text>
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
