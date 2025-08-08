# 🧠 Biohacker App — MVP

An all-in-one platform to help you optimize your health through **personalized advice**, **smart tracking**, **AI coaching**, and **community support**.  
Designed for anyone who wants to take control of their **physical, mental, and emotional well-being**—whether you’re a seasoned biohacker or just getting started.

---

## 🚀 Overview

**Core Features:**
- **Daily Check-Ins** — Quickly log mood, energy, sleep, and brain fog
- **Personalized Task List** — Daily habits tailored to your goals
- **AI Health Coach** — Smart, science-backed recommendations
- **Supplement Tracker** — Log, track, and get reminders for your supplements
- **Learning Center** — Digestible science-backed health insights
- **Community Forum** — Engage with others, optionally get feedback from health professionals

**Target Users:**
- Anyone curious about improving their health
- No tech experience required — friendly, modern interface

---

## 📱 Tech Stack

| Tool | Purpose |
|------|---------|
| **React Native (Expo)** | Cross-platform app (iOS + Android) |
| **TypeScript** | Type safety & maintainable code |
| **Supabase** | Auth, database, and storage |
| **AsyncStorage** | Local caching |
| **nativewind (Tailwind CSS)** | Fast, responsive styling |
| **React Navigation** | Navigation |
| **Zustand** | Lightweight global state management |
| **Lucide Icons** | Clean, consistent icon set |

---

## 📂 Folder Structure

```
/src
  /components
    Button.tsx
    Card.tsx
    Input.tsx
    CheckInSlider.tsx
  /screens
    OnboardingScreen.tsx
    CheckInScreen.tsx
    DashboardScreen.tsx
    TasksScreen.tsx
    SupplementsScreen.tsx
    LearningCenterScreen.tsx
    CommunityScreen.tsx
  /navigation
    AppNavigator.tsx
  /store
    useUserStore.ts
    useTasksStore.ts
  /utils
    supabaseClient.ts
    colors.ts
    formatDate.ts
```

---

## 🗓 MVP Development Timeline (7 Days)

| Day | Tasks |
|-----|-------|
| **Day 1-2** | Setup project, auth flow, navigation, folder structure |
| **Day 3-4** | Build Check-In screen + Dashboard UI |
| **Day 5** | Implement Task List + Supplements tracker |
| **Day 6** | Add Learning Center + Community screens |
| **Day 7** | Polish UI, add reminders/notifications, testing |

---

## 🎨 UI Design Guidelines

**Typography**
- Headings: Bold, 24–28px
- Body: 14–16px, medium weight
- Font: `Inter` or `Nunito`

**Colors**
- Primary: `#4CAF93` (calming green)
- Secondary: `#4A90E2` (soft blue)
- Background: `#F9FAFB`
- Text primary: `#1F2937` (dark gray)
- Text secondary: `#6B7280` (cool gray)

**Component Style**
- Cards: `rounded-2xl` + `shadow-md`
- Buttons: `rounded-full` for CTAs
- Consistent iconography

---

## 🔑 Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/biohacker-app.git
cd biohacker-app
```

### 2. Install Dependencies
```bash
npm install
# or
yarn install
```

### 3. Run the App
```bash
npx expo start
```

### 4. Environment Variables
Create a `.env` file:
```
EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
EXPO_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
```

---

## 📌 Notes for Developers

- Keep **components small and reusable**.
- All styles must use `nativewind` classes for consistency.
- Use **Zustand** for global state, not Context API (faster and simpler).
- When building features that require AI, start with **mock responses** so UI/UX can be tested before AI integration.
- Write commit messages in the format:
```
[feature] short description
[fix] short description
[chore] short description
```

---

## 🛠 Future Enhancements

- Wearable device integrations (Apple Health, Fitbit, Oura)
- Advanced AI coaching
- Deeper analytics dashboard
- Subscription tiers with premium features

---

**Made with 💚 for the curious mind & healthy body.**
