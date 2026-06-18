<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Page%20Replacement%20Simulator&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Interactive%203D%20OS%20Memory%20Visualizer%20%E2%80%94%20FIFO%20%7C%20LRU%20%7C%20LFU%20%7C%20Optimal&descAlignY=60&descSize=15" width="100%"/>

<br/>

<a href="#"><img src="https://img.shields.io/badge/Algorithms-FIFO%20%7C%20LRU%20%7C%20LFU%20%7C%20OPT-7c3aed?style=for-the-badge&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/3D%20Background-Three.js%20r128-0891b2?style=for-the-badge&logo=threedotjs&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Charts-Chart.js%204.4-f59e0b?style=for-the-badge&logo=chartdotjs&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Export-PNG%20%2B%20CSV-059669?style=for-the-badge&logoColor=white"/></a>

<br/><br/>

<a href="#"><img src="https://img.shields.io/badge/Dark%20%2F%20Light-Mode%20Toggle-111?style=for-the-badge&logo=halfmoon&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Belady's%20Anomaly-Demo%20Included-dc2626?style=for-the-badge&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Works-100%25%20Offline-22c55e?style=for-the-badge&logo=pwa&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&logo=opensourceinitiative&logoColor=white"/></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=1000&lines=Compare+FIFO+vs+LRU+vs+LFU+vs+OPT+in+Real-Time;Visualize+Every+Page+Fault+and+Memory+Hit;Explore+Beladys+Anomaly+Interactively;Powered+by+Three.js+Charts+and+Animations" alt="Typing SVG" />

<br/><br/>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700"/>

<br/><br/>

<h3>
  A premium, single-file OS Memory Visualizer that runs four page replacement algorithms<br/>
  simultaneously with 3D backgrounds, real-time charts, step-by-step traces, and Belady's Anomaly demo.
</h3>

<br/>

**[🚀 Quick Start](#-quick-start) • [✨ Features](#-features) • [🎮 Interactive Experience](#-interactive-experience) • 🌐 [Live Preview](#-live-preview) • [⚙️ How It Works](#️-how-it-works) • [🛠 Tech Stack](#-tech-stack) • [🤝 Contributing](#-contributing)**

</div>

---

## 🚀 Quick Start

```bash
# No npm. No build. No server. Just open.
git clone https://github.com/yourusername/page-replacement-simulator
cd page-replacement-simulator
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

> ⚡ **Single HTML file. 110KB. Works completely offline in any modern browser.**

---

## ✨ Features

### 🧠 Algorithm Engine
| Algorithm | Full Name | Eviction Policy | Optimal? |
|-----------|-----------|-----------------|---------|
| **FIFO** 🟣 | First In, First Out | Oldest page in memory | ❌ |
| **LRU** 🔵 | Least Recently Used | Page not used for longest time | ✅ Practical best |
| **LFU** 🟡 | Least Frequently Used | Page with fewest accesses | ❌ |
| **OPT** 🟢 | Optimal (Belady's) | Page not needed for longest future | ✅ Theoretical best |

### 🎨 Visual & UX
- ✅ **Live 3D animated background** — Three.js floating geometry
- ✅ **Animated hero section** — Spinning orbital rings with algorithm pills
- ✅ **Dual theme** — Light `#f5f4f1` and ultra-dark `#050505` with one-click toggle
- ✅ **Glassmorphism UI** — Frosted glass cards with specular highlights
- ✅ **Film grain texture** — Subtle SVG noise overlay for premium feel
- ✅ **Cursor glow** — Radial gradient follows mouse movement
- ✅ **Smooth animations** — 60fps spring physics on cards, cells, and buttons
- ✅ **Confetti winner reveal** — Canvas-based confetti when algorithm wins 🎊
- ✅ **Tilt cards** — 3D perspective tilt on hover for stat cards
- ✅ **Scroll reveal** — Elements animate in as they enter viewport

### 🔬 Simulation Features
- ✅ **All 4 algorithms run simultaneously** — compare side-by-side
- ✅ **Step-by-step mode** — pause at every page reference, see exactly what changes
- ✅ **Auto-play with speed control** — slow-motion to blazing fast
- ✅ **Page fault/hit animations** — cells shake on fault, glow on hit
- ✅ **Eviction highlighting** — evicted page highlighted in amber
- ✅ **Step progress bar** — visual timeline of simulation progress
- ✅ **Real-time fault counter** — hits and faults update live

### 📊 Analytics & Export
- ✅ **Bar chart** — total page faults comparison across all 4 algorithms
- ✅ **Line chart** — cumulative page faults over time (step-by-step)
- ✅ **Stat cards** — hits, faults, fault rate, efficiency score per algorithm
- ✅ **Best algorithm badge** — winner card highlighted with green border + badge
- ✅ **Export PNG** — html2canvas snapshot of entire results section
- ✅ **Export CSV** — full trace data (step, page, algorithm states)

### ⚠️ Belady's Anomaly
- ✅ **Dedicated Belady demo** — auto-detects when FIFO shows the anomaly
- ✅ **Visual explanation** — shows how MORE frames = MORE faults in FIFO
- ✅ **Educational card** — explains WHY Belady's anomaly occurs

### 📚 Educational Panel
- ✅ **Accordion section** — expandable explanations for each algorithm
- ✅ **Algorithm properties** — Optimal tag, Theoretical tag, tooltips
- ✅ **Tooltips** — hover over terms for instant definitions
- ✅ **Toast notifications** — non-intrusive feedback messages

---

## ⚙️ How It Works

```
User Input:
  ┌─────────────────────────────────────────┐
  │  Page Reference String: 7 0 1 2 0 3 0 4 │
  │  Number of Frames: 3                     │
  │  Preset Examples (Belady's, Random-20)  │
  └─────────────────────────────────────────┘
              ↓
  Algorithm Engine runs all 4 simultaneously:
  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐
  │  FIFO   │  │   LRU   │  │   LFU   │  │   OPT   │
  │ Queue   │  │Timestamp│  │Counter  │  │ Future  │
  │ based   │  │ based   │  │ based   │  │ lookup  │
  └─────────┘  └─────────┘  └─────────┘  └─────────┘
              ↓
  Outputs per step:
  • Frame state (which pages are in memory)
  • Hit ✅ or Fault ❌
  • Which page was evicted (if fault)
  • Running fault count
              ↓
  Visualizations:
  • Animated page tables (cell-by-cell)
  • Real-time bar + line charts
  • Stat cards with efficiency metrics
  • Belady's anomaly detection
  • Winner reveal with confetti 🎊
```

---

## 🎮 Controls

| Control | Description |
|---------|-------------|
| **Page String input** | Enter any space/comma-separated page reference sequence |
| **Frame Slider** | Drag to set 1–10 memory frames |
| **Preset dropdown** | Belady's Anomaly demo, Random 20-page sequence |
| **🎲 Random button** | Generate a new random page reference string |
| **▶ Run / Reset** | Start or clear simulation |
| **🦶 Step-Through** | Enter step-by-step mode |
| **⏩ Auto Play** | Auto-advance through steps |
| **☀️/🌙 Toggle** | Switch between light and dark theme |
| **📷 PNG** | Export results as PNG image |
| **📄 CSV** | Download full trace as CSV |

---

## 🎮 Interactive Experience

<div align="center">

### Light Mode — Hero + Input
*Glassmorphism card with 3D spinning rings, algorithm pills, and frame slider*

### Dark Mode — Step-by-Step Tables
*4 algorithms running side-by-side with hit/fault cell animations*

### Charts Section
*Bar chart (total faults) + Line chart (cumulative faults over time)*

### Belady's Anomaly Card
*Auto-detected and highlighted when FIFO demonstrates the anomaly*

### Winner Reveal
*Best algorithm gets confetti 🎊, green border badge, and highlighted stat card*

</div>

---

## 🚀 Live Demo

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=90&section=header&text=LIVE%20DEMO&fontSize=34&fontColor=ffffff&animation=twinkling" width="100%"/>

<br>

### 👇👇👇👇👇👇👇👇👇👇👇👇👇

[![🚀 TRY IT NOW](https://img.shields.io/badge/🚀_TRY_IT_NOW-LIVE_DEMO-ff4d4d?style=for-the-badge&logo=netlify&logoColor=white)](https://pras-os.netlify.app/)

### 👆👆👆👆👆👆👆👆👆👆👆👆👆

<br>

**Experience PRAS directly in your browser.**

**No installation • No setup • Instant access**

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=7C3AED&center=true&vCenter=true&width=900&lines=Compare+FIFO+vs+LRU+vs+LFU+vs+OPT;Visualize+Every+Page+Fault+and+Memory+Hit;Explore+Belady's+Anomaly+Interactively;Powered+by+Animated+Charts+and+3D+Visuals" alt="Typing SVG" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=70&section=footer" width="100%"/>

</div>

---

### ✨ What You Can Explore

- 📊 Compare FIFO, LRU, LFU & OPT simultaneously
- 🎯 Visualize Belady's Anomaly in real time
- 📈 Interactive memory and page fault charts
- ⚡ Step-by-step page replacement tracing
- 🌌 Animated 3D background environment
- 💾 Export results as PNG snapshots
- 📄 Export analytics as CSV reports

## 🛠 Tech Stack

```
Core:        Vanilla HTML5 + CSS3 + JavaScript (ES6+)
3D Engine:   Three.js r128 — floating background geometry
Charts:      Chart.js 4.4.0 — bar + cumulative line charts
Screenshot:  html2canvas 1.4.1 — PNG export
Fonts:       Sora (UI) + JetBrains Mono (code/data)
No framework. No bundler. No npm. Single file.
```

| Library | Version | Usage |
|---------|---------|-------|
| [Three.js](https://threejs.org/) | r128 | Animated 3D background particles/geometry |
| [Chart.js](https://www.chartjs.org/) | 4.4.0 | Bar chart + cumulative line chart |
| [html2canvas](https://html2canvas.hertzen.com/) | 1.4.1 | Export results section as PNG |
| Google Fonts | — | Sora (body) + JetBrains Mono (mono) |

### CSS Architecture
```css
/* Dual theme via CSS custom properties */
:root          → Light theme tokens
[data-theme="dark"] → Dark theme tokens

/* Key design tokens */
--fifo: #7c3aed   /* Purple */
--lru:  #0891b2   /* Cyan   */
--lfu:  #d97706   /* Amber  */
--opt:  #059669   /* Green  */
```

---

## 📁 File Structure

```
page-replacement-simulator/
│
├── 📄 index.html          ← Entire app (HTML + CSS + JS, self-contained)
│
└── 📄 README.md           ← You are here
```

> 💡 **Everything in one file** — the CSS, JavaScript, Three.js setup, Chart.js config, algorithm engines, animation system, export logic, and UI are all contained in `index.html`. Share it by sending just this file.

---

## 🧮 Algorithm Deep Dive

<details>
<summary><b>🟣 FIFO — First In, First Out</b></summary>

**Policy:** Evict the page that has been in memory the longest.

```
Frames = 3, Reference = 7 0 1 2 0 3 0 4

Step 1: Page 7  → FAULT  [7, -, -]
Step 2: Page 0  → FAULT  [7, 0, -]
Step 3: Page 1  → FAULT  [7, 0, 1]
Step 4: Page 2  → FAULT  [2, 0, 1]  ← evict 7 (oldest)
Step 5: Page 0  → HIT    [2, 0, 1]
...

Pros: Simple to implement
Cons: Suffers from Belady's Anomaly
```

</details>

<details>
<summary><b>🔵 LRU — Least Recently Used</b></summary>

**Policy:** Evict the page that was accessed least recently (longest time ago).

```
Implemented via timestamps updated on every access.
On fault: evict page with smallest timestamp.

Pros: No Belady's Anomaly, good practical performance
Cons: Requires tracking access history (hardware support needed)
```

</details>

<details>
<summary><b>🟡 LFU — Least Frequently Used</b></summary>

**Policy:** Evict the page that has been accessed the fewest times.

```
Implemented via per-page frequency counters.
On fault: evict page with lowest frequency count.

Pros: Good for skewed access patterns
Cons: Old popular pages can persist too long (frequency bias)
```

</details>

<details>
<summary><b>🟢 OPT — Optimal (Belady's Optimal)</b></summary>

**Policy:** Evict the page that will NOT be used for the longest time in the future.

```
Requires knowledge of the ENTIRE future reference string.
This is why it's called "theoretical" — impossible in practice.

Implementation: look ahead in reference string to find
which current frame page appears latest (or never).

Pros: Minimum possible page faults (theoretical lower bound)
Cons: Cannot be implemented in a real OS (future unknown)
Use: Benchmarking other algorithms
```

</details>

<details>
<summary><b>⚠️ Belady's Anomaly</b></summary>

**What:** With FIFO, adding MORE frames can cause MORE page faults — counterintuitive!

```
Classic example: Reference string = 1 2 3 4 1 2 5 1 2 3 4 5

With 3 frames: 9 page faults
With 4 frames: 10 page faults  ← MORE faults!

This anomaly ONLY affects FIFO and similar non-stack algorithms.
Stack algorithms (LRU, OPT) are immune to Belady's Anomaly.
```

</details>

---

## 🎯 Use Cases

- 📖 **OS Course Students** — Visualize what textbooks describe abstractly
- 🎓 **Professors** — Use in lectures to demonstrate algorithms live
- 💻 **Interview Prep** — Understand page replacement for system design interviews
- 🔬 **Algorithm Comparison** — Quickly see which algorithm performs best on your input
- 📊 **Lab Assignments** — Export CSV for analysis reports

---

## 🤝 Contributing

```bash
# Fork & clone
git clone https://github.com/yourusername/page-replacement-simulator
cd page-replacement-simulator

# Make your changes to index.html
# Test in browser

# Commit with conventional commits
git commit -m "feat: Add Clock algorithm (NRU variant)"
git commit -m "fix: LFU tie-breaking now uses FIFO order"
git commit -m "docs: Add NFU algorithm explanation in accordion"

# Push & PR
git push origin your-branch
```

### 💡 Contribution Ideas
- [ ] Add **Clock / NRU algorithm** (5th algorithm)
- [ ] Add **Working Set model** visualization
- [ ] Add **custom animation speed slider**
- [ ] Add **side-by-side Belady's anomaly comparison** (3 frames vs 4 frames)
- [ ] Add **mobile swipe gestures** for step navigation
- [ ] Add **algorithm race mode** — visual horse race between algorithms
- [ ] Internationalization (i18n) support

---

## 📄 License

```
MIT License — Free to use, modify, and distribute.
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

**Built with obsessive attention to detail 🎨**

*From Three.js 3D backgrounds to confetti winner reveals —*  
*every pixel crafted for the best possible learning experience.*

<br/>

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)

<br/>

⭐ **If this helped you understand page replacement algorithms, drop a star!** ⭐

</div>
