# 🗺️ Pathcraft

> Build a structured, AI-generated learning roadmap for any skill — and actually stick to it.

Pathcraft is an offline-first Flutter app that uses **Google Gemini AI** to create personalized, multi-month learning roadmaps from a simple goal. Each roadmap breaks down into months, weeks, and daily tasks — giving you a daily checklist and a study timer to stay on track.

---

## ✨ Features

### 🤖 AI Roadmap Generation
- Describe any learning goal, like “Learn Figma UI Design in 4 months”
- Gemini AI generates a structured month-by-month plan
- Each month can be expanded into weeks and daily tasks on demand

### 📋 Daily Checklist
- See all tasks scheduled for today, grouped by roadmap
- Animated task completion with strike-through
- Daily progress percentage summary

### ⏱️ Built-in Study Timer
- Floating timer overlay per task
- Play / Pause / Stop controls
- Session length saved with task progress

### 📅 Calendar View
- Visual overview of your task schedule by month
- See which days have tasks planned

### 📊 Skill Progress Map
- Per-roadmap analytics view
- Circular progress indicators per month
- Overall roadmap completion tracking

### 🎨 Beautiful, Premium UI
- Dark mode, Light mode, and System Default themes
- Smooth animations
- Glassmorphism cards and glowing progress bars
- Premium empty states and onboarding for new users

### 💾 Offline-First
- All data stored locally using Hive
- No account required
- Import/export roadmaps as JSON files for backup

### ⚙️ Settings
- Set your Gemini API key securely
- Import previously exported roadmaps
- Switch themes

---

## ⚙️ Requirements

- **Platform:** Android
- **Gemini API Key:** Required for roadmap generation  
  Get your free key at [Google AI Studio](https://aistudio.google.com)
- **Flutter SDK:** `^3.9.2` for building from source

---

## 🚀 Getting Started

1. Download the APK from the **Assets** section
2. Install it on your Android device
3. Enable **Unknown Sources** if needed
4. Open the app and go to **Settings**
5. Enter your **Gemini API Key**
6. Tap **+** and describe your learning goal
7. Let AI build the roadmap for you

---

## ⚠️ Known Limitations

- Push notifications are not yet active
- Editing a roadmap is not yet supported
- No cloud backup — data is device-local only
- AI generation requires an internet connection
- A valid Gemini API key is required
- No retry button yet if AI generation fails

---

## 🔮 Roadmap

### v1.1.0
- Push notification reminders
- Edit roadmap title, goal, and duration
- Calendar day tap → task detail navigation
- Retry button on AI generation failure
- Cloud sync / account support

---

## 🛠️ Building from Source

```bash
git clone https://github.com/your-username/pathcraft.git
cd pathcraft
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run --release
