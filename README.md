# AURA // BioSync OS (v4.8 Enterprise)
### Next-Generation Clinical Health Intelligence & Biometric Telemetry Dashboard

A premium, futuristic health monitoring dashboard engineered with the polish, typography, and visual hierarchy of a world-class health SaaS product (inspired by Whoop 4.0, Oura Horizon, Apple Health, and Linear).

---

## 🚀 Live Demo & Quick Launch

The entire application is completely self-contained in a standalone, zero-dependency `index.html` file.

### How to Run:
1. **Direct Double-Click**:
   - Navigate to `C:\Users\Guda Prahalad\.gemini\antigravity\scratch\health-pulse-dashboard\`
   - Double click [`index.html`](file:///C:/Users/Guda%20Prahalad/.gemini/antigravity/scratch/health-pulse-dashboard/index.html) to launch it immediately in Google Chrome, Microsoft Edge, Brave, Safari, or Firefox.
2. **Local HTTP Server (Optional)**:
   - Run any local static server (e.g. `npx serve`, Python `http.server`, or VS Code Live Server) from this directory.

> **Workspace Recommendation**: Set `C:\Users\Guda Prahalad\.gemini\antigravity\scratch\health-pulse-dashboard` as your active workspace in Antigravity.

---

## 💎 Design & Visual Architecture

- **Aesthetic Philosophy**: High-contrast, obsidian dark theme (`#080C14`), subtle cyber-clinical cyan (`#00F5FF`), vitality emerald (`#10B981`), circadian violet (`#8B5CF6`), and caloric amber (`#F59E0B`).
- **Surface Elevation**: Micro-borders (`rgba(255, 255, 255, 0.08)`), frosted glass (`backdrop-blur-16px`), and soft ambient glow radial gradients.
- **Typography**: Dual-font design pairing `Plus Jakarta Sans` for clean, human-centric UI and `JetBrains Mono` for tabular metrics and telemetry timestamps.
- **Micro-Interactions**: Ambient audio haptics synthesized via the browser's native **Web Audio API** (zero audio file downloads required).

---

## ⚡ Core Features & Modules

### 1. Collapsible Multi-Tier Sidebar
- Smooth expand/collapse rail with keyboard shortcut (`Ctrl + B` / `Cmd + B`).
- Dedicated navigation views:
  - 📊 **Telemetry Overview** (Master executive dashboard)
  - 🫀 **Cardiac & Vitals** (Lead II ECG waveform, blood pressure, vascular stiffness)
  - 🌙 **Sleep Architecture** (Polysomnogram stage hypnogram, restorative ratio)
  - ⚡ **Strain & Activity** (Cardiovascular strain zones 1–5, metabolic burn)
  - 💧 **Fluid & Nutrition** (Interactive liquid tank visualizer, electrolytes)
  - 🎯 **Target Milestones** (Interactive weekly benchmark progress)
  - 🔬 **AI Health Core** (Autonomous clinical inference engine)
- Hardware status pill: Oura Ring Gen 4 + Apple Watch Ultra 2 with live battery levels and latency indicators.

### 2. Overview Vital Cards
- **Heart Rate**: Real-time Lead II ECG canvas visualizer, live BPM counter with physiological micro-jitter, resting heart rate (56 BPM), and HRV (74 ms).
- **Sleep Quality**: 89/100 score, restorative sleep stage distribution bar (Deep: 1h 52m, REM: 2h 04m, Light: 3h 52m, Awake: 22m).
- **Daily Steps & Mobility**: 11,420 / 12,000 steps (95%), 8.64 km distance, floors climbed.
- **Day Strain**: 14.2 / 21.0 score, active calorie burn (642 kcal) vs basal metabolic burn (1,740 kcal).
- **Hydration Balance**: 2,750 mL / 3,200 mL, interactive quick-add buttons (`+250 mL`, `+500 mL`, `+750 mL`) with fluid tank wave animation.

### 3. Interactive Health Charts (Recharts & SVG Hybrid)
- Multi-metric toggle: Switch between **Heart Rate**, **HRV**, and **Day Strain**.
- Interactive timeframe filter: **24H**, **7D**, and **30D**.
- Hover crosshairs with exact timestamp and value tooltips.
- 7-Day comparative step volume bar chart.
- Circadian sleep hypnogram visualizer mapping Awake, REM, Light, and Deep sleep stages.

### 4. Interactive Modals & Tools
- **Log Activity Modal**: Add new workouts (Trail Run, Strength, HIIT, Cycling, Yoga) with custom duration, strain, and calories—immediately updates timeline and daily stats.
- **Adjust Targets Modal**: Live editing of daily step goals, hydration intake, and calorie burn targets.
- **AI Health Diagnostic Assistant**: Pre-loaded clinical queries with real-time simulated AI analysis.
- **Export Clinical Report**: Generates and downloads a clean `BioSync_Health_Report_YYYY-MM-DD.json` file.
- **Light/Dark Mode Switcher**: Seamless class-level toggle with full light theme palette.

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| **Core Framework** | React 18 (Hooks: `useState`, `useEffect`, `useRef`, `useMemo`) |
| **Styling** | Tailwind CSS with custom cyber-clinical tokens and glassmorphism |
| **Charts** | Recharts UMD with zero-dependency SVG fallback renderer |
| **Real-Time Graphics** | HTML5 Canvas ECG signal generator with trail sweep |
| **Icons** | Lucide-grade inline vector SVG suite (30+ icons, zero latency) |
| **Sound Engine** | Web Audio API Oscillator synthesizer for subtle haptic cues |
| **Data Engine** | Realistic clinical demo datasets with physiological streaming simulation |

---

## 📁 Project Directory

```
health-pulse-dashboard/
├── index.html       # Complete, standalone application (run directly in browser)
└── README.md        # Architecture, features, and setup guide
```

*Built with precision for world-class human performance monitoring.*
