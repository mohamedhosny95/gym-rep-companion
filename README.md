# 🏋️ Gym Rep & Recomp Companion

A mobile-first, fully accessible single-page web application designed for seamless workout tracking, progressive overload guidance, rest interval timing, and nutrition planning.

---

## ✨ Features

- **🏋️ Workout Hub:**
  - Full body workout routines for **Sunday (Gym A - Strength)**, **Tuesday (Gym B - Volume)**, and **Thursday (Gym A - Baseline / Progression)**.
  - Interactive set check-off chips with automatic `localStorage` persistence.
  - Collapsible cues and form safety checklists.
- **⏱️ Automated Rest Timer:**
  - Automatically triggers the target rest interval (e.g. 180s for Squats, 90s for Lunges, 60s for Curls) when a set is marked complete.
  - Built-in `+30s` increment, `Pause / Resume`, and offline audio chime (Web Audio API).
- **🥗 Recomp Nutrition Planner:**
  - High-contrast macro breakdown (Calories, Protein, Carbs, Fats) and timeline meal schedules for **Plan A (10:30 AM)**, **Plan B (5:00 PM)**, and **Rest Day**.
  - **🌙 Ramadan Fasting Mode Toggle:** Instant swap to Iftar and Suhoor timing.
- **📈 8-Week Progression Roadmaps:**
  - Multi-week target tables, "+2kg green light" criteria, and safety red flags for every lift.
- **🧘 Sports & Mobility Routines:**
  - 15-minute Morning Activation flow.
  - Pre/post routines for **Monday Padel** and **Wednesday Football**.
- **♿ WCAG 2.1 AA Accessibility:**
  - High contrast dark mode ($\ge 4.5:1$ contrast ratio).
  - 48px+ touch targets for mobile/gym conditions.
  - Semantic ARIA roles (`tablist`, `tab`, `tabpanel`, `aria-expanded`).

---

## 🚀 Getting Started

Simply open `index.html` in any web browser or deploy it to GitHub Pages / Vercel. No build step or dependencies required.
