<div align="center">
  <h1>🗺️ Pathcraft</h1>
  <p><em>AI-powered learning roadmaps — structured, daily, and actually stickable.</em></p>

  <p>
    <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Platform: Android" />
    <img src="https://img.shields.io/badge/flutter-%5E3.9.2-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter ^3.9.2" />
    <img src="https://img.shields.io/badge/AI-Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Powered by Gemini" />
    <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License: MIT" />
  </p>
</div>

---

## Why Pathcraft?

Most learning plans die after week one. You write a vague goal, follow it for three days, and then life happens.

Pathcraft fixes that: **Gemini AI generates a month-by-month curriculum** from a single sentence goal. Every day, you open your checklist, tick off what's scheduled, and the built-in timer keeps you honest. Offline-first. No account. No excuses.

> *"Learn Figma UI Design in 4 months" → a structured plan with daily tasks, a progress tracker, and a timer — all in one app.*

---

## ✨ Features

### 🤖 AI-Generated Roadmaps
Describe any learning goal. Gemini produces a structured month-by-month plan. Expand any month into weeks and individual daily tasks. Adjust as you go.

### 📋 Daily Checklist
Today's tasks, grouped by roadmap. Animated strike-through on completion. Daily progress percentage so you know if you're on track.

### ⏱️ Study Timer
Floating timer overlay per task. Play, pause, stop. Session time is saved with the task — review how long each topic took.

### 📅 Calendar View
See your scheduled tasks across the month at a glance. Know exactly what's coming and where you have gaps.

### 📊 Progress Dashboard
Per-roadmap analytics. Circular progress indicators per month. Overall completion tracking. Watch the months fill up.

### 🎨 Premium UI
Dark mode, light mode, and system-default themes. Glassmorphism cards, glowing progress bars, smooth animations, and polished onboarding. It *feels* good to open.

### 💾 Offline-First
All data stored locally with Hive. No account, no login, no cloud dependency. Import and export roadmaps as JSON files for backup or sharing.

---

## 🚀 Download

| Method | Instructions |
|---|---|
| **Direct APK** | Download the latest `.apk` from the [Releases](https://github.com/hamdi-ab/pathcraft-release/releases) page |
| **Build from source** | See below |

Once installed, open the app, go to **Settings**, enter your **Gemini API Key**, tap **+**, and describe your goal.

> 💡 Get your free Gemini API key at [Google AI Studio](https://aistudio.google.com)

---

## 📱 Requirements

- **OS:** Android
- **Gemini API Key** (free) — required for roadmap generation
- **For building from source:** Flutter SDK `^3.9.2`

---

## 🔧 Building from Source

```bash
git clone https://github.com/hamdi-ab/pathcraft-release.git
cd pathcraft-release
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run --release
```

---

## ⚠️ Current Limitations

| Area | Status |
|---|---|
| Push notifications | Not yet active |
| Roadmap editing | Not yet supported |
| Cloud backup | Device-local only (JSON export/import available) |
| AI generation retry | Not yet implemented (tap + to retry) |

---

## 🔮 Planned

**v1.1.0** — Push reminders, roadmap editing, calendar navigation, retry on AI failure, cloud sync.

---

## 👤 About the Developer

Built by [Hamdi Abdel Fetah](https://github.com/hamdi-ab) — a Flutter & full-stack developer who ships. Pathcraft is an offline-first, AI-powered learning companion built with Flutter and Google Gemini.

---

<div align="center">
  <sub>⭐ If this app helps you learn something, star the repo — it keeps me shipping.</sub>
  <br/>
  <a href="https://github.com/hamdi-ab/hamdi-ab">🐙 View my GitHub profile</a>
</div>
