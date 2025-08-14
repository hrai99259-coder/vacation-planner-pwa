# VacayPlan – Vacation Planner (PWA, React, Tailwind)

Multi‑page vacation planner demo using React + Tailwind + Vite with PWA support (installable on phones), dark mode, mobile‑first UI, sticky bottom nav, and animated AI banners.

## Quickstart (Local)
```bash
npm i
npm run dev
```
Open http://localhost:5173

## Deploy (Vercel)
1. Push this folder to a GitHub repo.
2. Go to https://vercel.com → New Project → Import the repo → Deploy.
3. Visit your URL (e.g., https://vacation-planner-demo.vercel.app).

## Install on Phone (as an App)
- Open the URL on mobile.
- Android/Chrome: ⋮ → Add to Home screen.
- iOS/Safari: Share → Add to Home Screen.

## Build as APK (Optional)
```bash
npm i @capacitor/core @capacitor/cli
npx cap init vacayplan com.example.vacayplan --web-dir=dist
npm run build
npx cap add android
npx cap open android
```
Build and run from Android Studio.

## Where to Plug Real APIs
- Replace mock arrays in `src/App.jsx` (HOTELS, TRAINS, BUSES, RENTALS, RESTAURANTS) with `fetch` calls.
- Swap LocalStorage bookings with Firebase Firestore when you’re ready.
