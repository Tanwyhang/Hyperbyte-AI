# **🔥 Expo Hackathon Blueprint (Shadcn-Style, Tailwind-Vibe)**  
### *Fast. Beautiful. Mobile-first.*  

---

## **1. Core Principles**  
✔ **Expo-Driven Mobile Dev** – Fastest way to build iOS/Android apps.  
✔ **Tailwind-Like Styling** – Use `nativewind` for utility-first styling.  
✔ **shadcn-Inspired UI** – Clean, consistent components (via `react-native-paper` or `ui-kitten`).  
✔ **Offline-Ready + Gamified** – User engagement without reliance on constant internet.  

---

## **2. Tech Stack (Expo-First, Styled Like Web)**  

### **Frontend (Expo + React Native)**  
✅ **Expo (Managed Workflow)** – Easy setup, fast testing.  
✅ **React Native + TypeScript** – Stable, scalable mobile code.  
✅ **nativewind** – Tailwind CSS utility classes for styling in React Native.  
✅ **react-native-paper / tamagui / ui-kitten** – Component libraries with shadcn-inspired design.  
✅ **react-navigation** – Stack, tab, drawer navigation.  
✅ **expo-router** *(optional)* – File-based routing (like Next.js!).  
✅ **react-native-reanimated + gesture-handler** – Smooth animations.  
✅ **AsyncStorage / React Query** – Data caching, offline support.

### **Backend (FastAPI / JSON API / Firebase)**  
✅ **FastAPI** – Quick RESTful backend with JSON responses.  
✅ **SQLite / JSON (Local API)** – Fast, no setup needed.  
✅ **Firebase (Optional)** – Auth, Firestore, or Realtime DB.

### **Dev & Deployment Tools**  
✅ **Expo Go** – Instant testing on real devices.  
✅ **EAS Build + Submit** – Compile and ship to app stores.  
✅ **GitHub + Expo GitHub Actions** – CI/CD for fast iterations.  
✅ **Railway / Vercel / Render** – Backend deployment.

---

## **3. App Structure: 3 Core Pillars**  

| **Pillar** | **What It Does** | **How to Build It** |
|------------|------------------|----------------------|
| **Learn**  | Deliver content or insights | API call to `/content`, render cards/list UI |
| **Act**    | Let users track progress/actions | AsyncStorage / SQLite to log data locally |
| **Engage** | Community, chat, or leaderboard | Firebase or basic chat via backend API |

### 🔁 Dev Phases (24-Hour Hackathon Flow)

| Time | Focus |
|------|-------|
| ⌛ 0–3 hrs | Brainstorm, wireframe, Expo setup with nativewind & navigation |
| ⌛ 3–6 hrs | Create main screens (Learn, Act, Engage) with Tailwind-style components |
| ⌛ 6–12 hrs | Hook up data – AsyncStorage or backend (FastAPI/Firebase) |
| ⌛ 12–18 hrs | Add animations, gamification (XP, badges, etc.) |
| ⌛ 18–24 hrs | Polish, test, deploy via EAS, record demo |

---

## **4. API & Data Flow**  

- **Endpoints (FastAPI or JSON-based):**  
  - `GET /content` → Fetch Learn data  
  - `POST /track` → Log user actions  
  - `GET /leaderboard` → Show ranks  

- **Auth:**  
  - Use Firebase Auth or Expo SecureStore  
- **Offline Support:**  
  - AsyncStorage for caching, default fallback  

---

## **5. Adaptability to Hackathon Themes**  

| **Theme** | **Example Features** |
|-----------|-----------------------|
| 🌱 **Environment** | Eco challenges, carbon tracker, streaks |
| 🧠 **Mental Health** | Daily mood check-ins, quote feed, journaling |
| 🎓 **Education** | Flashcards, interactive challenges, AI tutor |
| ✅ **Productivity** | Pomodoro timer, habits, achievement system |
| 🏋️ **Fitness** | Workout tracker, progress graphs, mini goals |

---

## **6. Why This Blueprint Wins Hackathons**  

✅ **Expo = Speed + Simplicity** – No native setup headaches  
🎨 **Tailwind & shadcn-style UI** – Clean, consistent design with fast styling  
🛠 **Offline-Ready & Gamified** – Keeps users engaged, even without internet  
📦 **Scalable & Reusable** – Easy to build on after the hackathon  
🚀 **Deploy Fast with EAS** – App Store & Play Store in one go

---

To do:
- `nativewind` for Tailwind-style styling  
- `react-navigation` and sample routes  
- `AsyncStorage` for local data  
- A shadcn-inspired UI setup?
