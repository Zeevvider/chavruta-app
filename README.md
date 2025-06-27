# 📖 Chavruta App

A Torah-based chavruta video learning app — powered by React Native + Sefaria + custom video layouts.  

> 🔧 Work in progress. This project is structured around small, reviewable feature branches.

---

## 🚀 Project Structure

```bash
chavruta-app/
├── assets/                # Fonts, images, icons
├── components/            # Reusable UI components
├── screens/               # Onboarding, Video, Calendar, etc.
├── navigation/            # React Navigation logic
├── services/              # API, storage, authentication
├── utils/                 # Helpers and constants
├── App.js
├── package.json
└── README.md

## 📱 Features

📖 Learn Torah with a live chavruta via video chat  
🔍 Highlight and track learning progress (paragraph-based)  
📆 Schedule chavruta sessions using calendar availability  
🧠 Select learning preferences (read, watch, listen)  
🏆 Earn points, badges, and track learning streaks  
🧩 Connect to the Sefaria API for Torah text  
🗂️ Save notes or questions per line/paragraph  
🎥 Custom video layout (small bubble view + fullscreen)

---

## 🛠️ Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/Zeevider/chavruta-app.git
cd chavruta-app
npm install
npm start
---

## 🌿 Branching Strategy

We work feature-by-feature using Git branches:

- `main` – Production-ready stable code
- `onboarding-ui` – For onboarding screen layout and flow
- `video-layout` – For chavruta video call UI
- `calendar-scheduler` – Availability & scheduling screens
- `learning-engine` – Text display, highlighting, and tracking logic

✅ Each task/feature should be in its own branch and reviewed before merging to `main`.


---


## ✅ Development Tasks

### MVP Goals

- [ ] Project setup with Git & React Native
- [ ] Connected Sefaria API
- [ ] Build onboarding screens (login, profile, learning style)
- [ ] Implement chavruta video layout (bubble + full screen)
- [ ] Create paragraph-based text navigation with highlights
- [ ] Add point/streak/leaderboard system
- [ ] Setup availability calendar for chavruta scheduling
- [ ] Add “Need Explanation” feature
- [ ] Profile page with saved notes & sessions

---

### In Progress

- [ ] Onboarding UI branch setup
- [ ] First paragraph highlight system
- [ ] Bubble video view with mic toggle

---



## 🤝 Contribution Guide

### How to Contribute

1. **Fork this repo** or clone it directly
2. **Create a new branch** for your feature:
   ```bash
   git checkout -b your-feature-name

3. Make your changes:

4. Commit your code:
 ```bash 
 git add .
git commit -m "Add: feature name"

5. Push your branch:
```bash
git push origin your-feature-name


6. Submit a pull request for review!


---


## 🗺️ Feature Roadmap

### ✅ Completed
- Project initialized with Git + React Native
- Sefaria API integration tested
- Design system setup in Figma
- Onboarding wireframes (login, profile, learning style)

### 🚧 In Progress
- Onboarding UI build
- Paragraph navigation with highlight & “I’m Ready” sync
- Basic video layout with toggle mic & fullscreen
- Weekly availability scheduler

### 🔜 Planned
- Calendar integration for scheduling chavruta
- Chavruta requests + personal calendar UI
- Points, streaks, badges, leaderboard
- “Need Explanation” feature in text reader
- Notification system for learning reminders
- Audio-only learning mode (optional)


---

## 🧠 Tech Stack

### Frontend
- ⚛️ React Native (Expo)
- 🧩 Figma (UI/UX Design)
- 📱 Mobile-first design system

### Backend
- 🌐 Node.js (Express)
- 🧾 MongoDB (or Postgres)

### APIs & SDKs
- 📖 Sefaria API – Torah text & navigation
- 🎥 Video SDK (Daily / Zoom)
- 📆 (Planned) Google Calendar API for scheduling

### Tools
- 🧠 Git + GitHub (task branches + commits)
- ✨ VS Code
- 📦 npm or yarn
