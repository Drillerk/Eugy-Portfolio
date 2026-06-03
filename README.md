# Eugine Okero | Advanced Technical Portfolio

Welcome to the central deployment repository for my professional portfolio. This platform showcases production implementations, advanced defensive networking infrastructure layout engines, and quantitative asset tracking hubs under my professional identity, **Manna Driller**.

## 🌐 Live Production Deployments
* **Live Portfolio Showcase:** `[Insert your main Vercel link here once live]`
* **DrillerHub Engine:** [https://drillerhub.vercel.app](https://drillerhub.vercel.app)
* **Manna Driller Launchpad:** [https://manna-driller-launchpad.vercel.app](https://manna-driller-launchpad.vercel.app)

---

## 🛠️ Core Technological Stack
* **Web Architecture:** Semantic HTML5, Core CSS3 (Dynamic Layout Box Engines, CSS Grid, Custom Media Breakpoints), and Vanilla JavaScript ES6+.
* **State Management:** Local Storage Session Persistence APIs for unified Dark/Light UI configuration.
* **Infrastructure Focus:** Enterprise Network Routing Optimization (MikroTik WinBox, Huawei GPON configurations), Automation scripting, and Threat Vector Security Modeling.

---

## 📐 Key Design Implementations & Code Structure

### 1. Advanced Two-Dimensional Layouts (CSS Grid)
The production cards and skill matrices are engineered using **CSS Grid** rather than standard flexbox rules. This allows for fluid multi-column alignment that adapts perfectly to desktop viewports and mobile breakpoints without relying on bloated external frameworks.

### 2. State-Persistent Dark Mode Engine
The theme-switching component uses vanilla JavaScript to modify a global `data-theme` variable on the root document level. To maximize user accessibility, state persistence is handled natively:
```javascript
// Example structural snippet from script.js
localStorage.setItem('theme', isDark ? 'dark' : 'light');
