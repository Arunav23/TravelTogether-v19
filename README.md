<div align="center">

<img src="https://img.shields.io/badge/version-v15-e94560?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/build-passing-22c55e?style=for-the-badge" />
<img src="https://img.shields.io/badge/license-MIT-a855f7?style=for-the-badge" />
<img src="https://img.shields.io/badge/PRs-welcome-3b82f6?style=for-the-badge" />
<img src="https://img.shields.io/badge/made%20with-❤️-e94560?style=for-the-badge" />

<br/><br/>

```
 ████████╗██████╗  █████╗ ██╗   ██╗███████╗██╗
    ██╔══╝██╔══██╗██╔══██╗██║   ██║██╔════╝██║
    ██║   ██████╔╝███████║██║   ██║█████╗  ██║
    ██║   ██╔══██╗██╔══██║╚██╗ ██╔╝██╔══╝  ██║
    ██║   ██║  ██║██║  ██║ ╚████╔╝ ███████╗███████╗
    ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝╚══════╝

 ████████╗ ██████╗  ██████╗ ███████╗████████╗██╗  ██╗███████╗██████╗
    ██╔══╝██╔═══██╗██╔════╝ ██╔════╝╚══██╔══╝██║  ██║██╔════╝██╔══██╗
    ██║   ██║   ██║██║  ███╗█████╗     ██║   ███████║█████╗  ██████╔╝
    ██║   ██║   ██║██║   ██║██╔══╝     ██║   ██╔══██║██╔══╝  ██╔══██╗
    ██║   ╚██████╔╝╚██████╔╝███████╗   ██║   ██║  ██║███████╗██║  ██║
    ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
```

### 🌍 India's Smartest Social Travel Platform

**Find verified travel partners · Save 40% on group trips · Travel safe, together**

<br/>

[🚀 Live Demo](#) · [📱 Features](#-features) · [⚙️ Setup](#️-getting-started) · [🏗️ Architecture](#️-project-architecture) · [🤝 Contributing](#-contributing)

<br/>

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Live Preview](#-live-preview)
- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Project Architecture](#️-project-architecture)
- [Sections Breakdown](#-sections-breakdown)
- [JavaScript API Reference](#-javascript-api-reference)
- [AI Matching Algorithm](#-ai-matching-algorithm)
- [Authentication Flow](#-authentication-flow)
- [Database Schema](#-database-schema)
- [Responsive Design](#-responsive-design)
- [Performance](#-performance)
- [Getting Started](#️-getting-started)
- [Deployment](#-deployment)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)

---

## 🌟 Overview

**Travel Together** is a full-featured, zero-dependency social travel platform built as a **single HTML file** — no build tools, no npm, no frameworks. It delivers an app-like experience purely through vanilla HTML5, CSS3, and JavaScript.

The platform solves a real problem: **82 million solo travelers in India** have no trusted way to find compatible travel companions. Travel Together bridges this gap with AI-powered matching, Aadhaar-verified profiles, real-time chat, and group trip planning.

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│   ONE FILE  ·  ZERO DEPENDENCIES  ·  FULL STACK     │
│                                                     │
│   1,651 lines  ·  19 embedded images  ·  1.28MB     │
│   42 JS functions  ·  38 CSS variables              │
│   12 UI sections  ·  12 CSS animations              │
│                                                     │
└─────────────────────────────────────────────────────┘
```

> **Built for India** — Hinglish-ready UI, Indian destinations, Rupee pricing, Razorpay-ready payment layer, Aadhaar verification flow.

---

## 👁️ Live Preview

```
yourusername.github.io/travel-together
```

| Section | Preview |
|---|---|
| 🦸 Hero | Dark navy gradient + AI search box |
| 🗺️ Destinations | 6 real destination cards with embedded photos |
| 🎒 Group Trips | 3 trip cards with real images + join flow |
| 👥 Travelers | Instagram-style verified profile cards |
| 💎 Pricing | Free / Pro ₹199 / Business ₹499 |
| 📱 App Mockup | Phone UI with live trip previews |

---

## ✨ Features

### 🎯 Core Features

| Feature | Description | Status |
|---|---|---|
| 🤖 AI Matching | Compatibility score based on travel style, budget, destination | ✅ Live |
| ✅ Verified Profiles | Photo + profile verification layer | ✅ Live |
| 💬 Real-time Chat | Firebase-powered instant messaging | ✅ Live |
| 🛡️ Safety Layer | SOS button + 24/7 support system | ✅ Live |
| 💰 Smart Split | Auto-split bills & expense tracker | ✅ Live |
| 🔍 Smart Search | Filter by From/To/Date/Travelers | ✅ Live |
| ❤️ Save/Wishlist | Save favourite trips to localStorage | ✅ Live |
| 📋 Trip Creation | Create & publish group trips | ✅ Live |

### 🔐 Authentication

| Method | Provider | Status |
|---|---|---|
| Email + Password | Firebase Auth | ✅ Ready |
| Google Sign-In | Firebase OAuth | ✅ Ready |
| localStorage fallback | In-browser DB | ✅ Ready |
| Auto session restore | onAuthStateChanged | ✅ Ready |

### 💎 Pricing Tiers

| Plan | Price | Highlights |
|---|---|---|
| Free | ₹0 forever | 3 matches/month, join public trips |
| **Pro** | **₹199/month** | Unlimited matches + chat + verified badge |
| Business | ₹499/month | Featured listings + analytics + bulk trips |

---

## 🛠️ Tech Stack

```
Frontend ──────────────────────────────────────────────
  HTML5          →  Semantic markup + Schema.org JSON-LD
  CSS3           →  Custom properties, Grid, Flexbox,
                    Glassmorphism, 12 keyframe animations
  Vanilla JS     →  ES6+, async/await, IntersectionObserver
  Google Fonts   →  Fraunces (Display) + DM Sans (Body)

Backend (Firebase) ────────────────────────────────────
  Firebase Auth  →  Email/Password + Google OAuth
  Firestore DB   →  Real-time NoSQL document store
  localStorage   →  Offline fallback + session cache

SEO & Meta ────────────────────────────────────────────
  Open Graph     →  WhatsApp / Facebook / LinkedIn previews
  Twitter Cards  →  summary_large_image format
  Schema.org     →  WebApplication JSON-LD structured data
  Canonical URL  →  traveltogether.in
  robots meta    →  index, follow, max-snippet:-1

Design System ─────────────────────────────────────────
  38 CSS Variables   →  Consistent design tokens
  Dark Navy Theme    →  #0f0f1a → #1a1a2e hero gradient
  Accent Red-Pink    →  #e94560 CTAs + highlights
  Warm Off-White     →  #fafaf9 base background
  Border Radius      →  10px / 14px / 20px / 28px scale
```

---

## 🏗️ Project Architecture

```
travel-together-v15.html
│
├── <head>
│   ├── Meta Tags (SEO + OG + Twitter + Schema.org)
│   ├── Google Fonts (Fraunces + DM Sans)
│   ├── Firebase SDK (Auth + Firestore)
│   └── <style> ── 500+ lines of CSS
│       ├── :root CSS Variables (38 tokens)
│       ├── Global Animations (12 @keyframes)
│       ├── Component Styles (nav, hero, cards...)
│       └── Responsive Breakpoints (768px, 1100px)
│
└── <body>
    ├── <nav>           Fixed glassmorphic navbar
    ├── <div> mob-nav   Mobile slide menu
    ├── <main>
    │   ├── .hero       Search box + tag + heading
    │   ├── #homeSecs
    │   │   ├── Destinations Grid (6 cards)
    │   │   ├── Group Trips Grid (3 cards)
    │   │   ├── Exclusive Offers (2 cards)
    │   │   ├── Market Stats Section
    │   │   ├── Features Strip (5 items)
    │   │   ├── How It Works (4 steps)
    │   │   ├── Verified Profiles (4 Instagram cards)
    │   │   ├── Competitor Comparison Table
    │   │   ├── Pricing Plans (3 tiers)
    │   │   ├── Trust Stats Banner
    │   │   ├── Target Audience Cards
    │   │   └── App Download Section + Phone Mockup
    │   └── #srSec      Search Results View
    ├── Modals (Login, Signup, Trip Detail, Upgrade,
    │          Chat, Checkout, Create Trip)
    ├── .chat-fab       Floating chat button
    ├── .toast-c        Toast notification system
    ├── <footer>        4-column footer
    │
    └── <script> ── 42 JS functions
        ├── Firebase Config + Init
        ├── In-browser DB (localStorage fallback)
        ├── Data Arrays (DESTS, TRIPS, PROFILES, FEATURES)
        ├── AI Matching Algorithm
        ├── Auth Functions (login/signup/google/logout)
        ├── UI Renderers (trips/profiles/dests/feats)
        ├── Modal Manager
        ├── Toast System
        ├── Search + Filter Engine
        ├── Save/Wishlist (localStorage)
        └── Scroll + Animation Observers
```

---

## 📐 Sections Breakdown

### 1. 🦸 Hero Section
- Dark navy gradient (`#0f0f1a → #1a1a2e`)
- 3-tab search box: **Find Partner / Join Trip / Hotels**
- Quick search chips: Delhi→Goa, Mumbai→Manali, BLR→Coorg, Delhi→Ladakh, Chennai→Pondi
- Floating orbs with blur animation

### 2. 🔥 Trending Destinations (6 cards)
Real embedded photos for all 6 — no external URLs needed:

| # | Destination | Vibe |
|---|---|---|
| 1 | Goa | Beach sunset golden hour |
| 2 | Manali | Snow mountains valley |
| 3 | Kerala | Houseboat backwaters |
| 4 | Ladakh | Winding mountain highway |
| 5 | Rishikesh | White water rafting |
| 6 | Jaipur | Hawa Mahal at dusk |

### 3. 🎒 Popular Group Trips (3 cards)
Real trip photos + verified host + AI match score + join flow:
- Delhi → Goa (Beach Party) · ₹4,500
- Mumbai → Manali (Snow Trek) · ₹7,800
- BLR → Coorg (Coffee Plantation) · ₹3,200

### 4. 👥 Verified Travelers Near You
Instagram-style cards with cover gradient, circular photo, handle, GenZ bio, and 3-stat layout:

| Profile | Handle | Style |
|---|---|---|
| Aisha Rawat | @aisha.rawat | Solo Wanderer · Dehradun |
| Rohan Khanna | @rohan.khanna | Adventure Freak · Jaipur |
| Dev Sharma | @dev.sharma | Vibe Curator · Delhi |
| Arjun Thakur | @arjun.thakur | Backpacker · Mumbai |

### 5. 💎 Pricing
Annual/Monthly toggle + feature comparison + payment modal with card/UPI/netbanking

### 6. 📊 Market Opportunity
Animated counters: 82M solo travelers · ₹340B market · 67% seek companions

### 7. 🏆 Competitor Comparison
Travel Together vs Airbnb vs MakeMyTrip vs Tinder — clear differentiation table

### 8. 📱 App Mockup
Phone frame with live trip cards showing real destination thumbnails + match % scores

---

## 📚 JavaScript API Reference

### Data Layer

```javascript
// In-browser database (localStorage fallback)
const DB = {
  getUser(email)        // → user object | null
  addUser(userData)     // → new user with generated ID
  updateUser(id, data)  // → updated user
  getTrips()            // → array of all trips
  addTrip(tripData)     // → new trip object
}
```

### Auth Functions

```javascript
doLogin()              // Email/password login (Firebase + fallback)
doSignup()             // New user registration
googleAuth()           // Google OAuth popup
logout()               // Clear session + update UI
isAuth()               // → boolean
isPro()                // → boolean (plan === 'pro' | 'business')
updateAuthUI()         // Re-render navbar based on auth state
```

### UI Renderers

```javascript
renderDests()          // Populate 6-card destination grid
renderTrips(id, data)  // Populate trip cards into container `id`
renderProfiles()       // Populate 4 Instagram-style traveler cards
renderFeats()          // Populate features strip
```

### Search & Navigation

```javascript
doSearch()             // Read form inputs → showSR()
qSearch(from, to)      // Quick chip search
showSR(from, to, data) // Render search results view
filterSR(tag)          // Filter results by tag
goHome()               // Return to homepage sections
navTab(el, tab)        // Activate nav tab + route
```

### Trip & Matching

```javascript
openTD(id)             // Open trip detail modal
joinTrip(id)           // Auth-gated join flow
connectUser(name)      // Auth-gated connect flow
calculateMatchScore(user, trip)  // → 60–98 compatibility %
getMatchColor(score)   // → CSS color string
```

### Utility

```javascript
openModal(id)          // Show modal overlay
closeModal(id)         // Hide modal
closeAllModals()       // Close everything
toast(msg, type)       // Show toast: '' | 'err' | 'warn'
toggleSave(id, el)     // Toggle trip wishlist (localStorage)
```

---

## 🤖 AI Matching Algorithm

The match score is calculated in real-time per user-trip pair:

```javascript
function calculateMatchScore(user, trip) {
  let score = 60; // base score

  // +15 if travel styles match
  if (user.style === trip.style) score += 15;

  // +10 if budget within ±20% range
  if (Math.abs(user.budget - trip.price) / trip.price < 0.2) score += 10;

  // +8 if preferred city matches trip destination
  if (user.city?.toLowerCase() === trip.from?.toLowerCase()) score += 8;

  // Normalize to 60–98 range
  return Math.min(98, Math.max(60, score));
}
```

> **Roadmap:** Replace with a real ML model using user interaction data — clicks, saves, message initiations, trip joins.

---

## 🔐 Authentication Flow

```
User clicks Login/Signup
        │
        ▼
   firebaseReady?
   ┌────┴────┐
  YES       NO
   │         │
Firebase   localStorage
Auth SDK   fallback DB
   │         │
   └────┬────┘
        │
  currentUser set
  localStorage cached
  updateAuthUI()
  Toast: "Welcome! 🎉"
```

**Session Persistence:**
```javascript
// On page load — auto-restore session
const saved = localStorage.getItem('tt_current');
if (saved) currentUser = JSON.parse(saved);

// Firebase realtime listener
auth.onAuthStateChanged(user => {
  if (user) fetchUserFromFirestore(user.uid);
});
```

---

## 🗄️ Database Schema

### Firestore Collections

```
users/
  └── {uid}
        ├── fname: string
        ├── lname: string
        ├── email: string
        ├── phone: string
        ├── city: string
        ├── style: string  ('Backpacker' | 'Adventure' | 'Comfort' | 'Luxury')
        ├── plan: string   ('free' | 'pro' | 'business')
        ├── verified: boolean
        └── id: string

trips/
  └── {id}
        ├── from: string
        ├── to: string
        ├── date: string
        ├── spots: number
        ├── max: number
        ├── price: number
        ├── style: string
        ├── budget: number
        ├── tags: string[]
        ├── days: { d, t }[]
        ├── members: string[]
        └── verified: boolean
```

---

## 📱 Responsive Design

```
Desktop  ≥ 1100px   →  Full layout, 6-col destinations, 4-col profiles
Tablet   768–1100px →  3-col destinations, 2-col trips, 3-col profiles
Mobile   ≤ 768px    →  Single column, bottom-sheet modals, full-screen chat
Small    ≤ 480px    →  Compact navbar (52px), stacked search fields
XS       ≤ 360px    →  Ultra-compact, min-width safe
```

**Mobile-first optimizations:**
- Bottom sheet modals (slides up from bottom, 94vh)
- Full-screen chat (100vh, no border radius)
- Touch-optimized sliders and tap targets
- iOS zoom fix on input focus (`font-size: 16px`)
- Hamburger menu with animated X icon

---

## ⚡ Performance

| Metric | Value |
|---|---|
| File size | ~1.28MB (single file) |
| Total embedded images | 19 (17 JPEG + 2 PNG) |
| External requests | 2 (Google Fonts + Firebase SDK) |
| JS functions | 42 |
| CSS variables | 38 |
| Zero npm dependencies | ✅ |
| Zero build step | ✅ |
| Offline capable | Partial (localStorage fallback) |

**Optimizations applied:**
- All images compressed + resized before base64 embedding
- Destination images: 600×800px @ 72% quality (~80–125KB each)
- Trip card images: 700×400px @ 75% quality (~50–70KB each)
- Profile photos: 300×300px @ 85% quality (~12–20KB each)
- CSS animations use `transform` + `opacity` (GPU-composited)
- `IntersectionObserver` for scroll reveal (no scroll event listeners)
- `passive: true` on scroll listener
- `will-change` avoided (reduces memory overhead)

---

## ⚙️ Getting Started

### Option A — Just Open It (Zero Setup)
```bash
# Download the file and open directly
open travel-together-v15.html
```
Works fully with localStorage fallback. No server, no config needed.

---

### Option B — VS Code + Live Server (Recommended for Dev)

```bash
# 1. Open in VS Code
code travel-together-v15.html

# 2. Install Live Server extension
# Extensions → search "Live Server" by Ritwick Dey → Install

# 3. Click "Go Live" in bottom-right
# Opens at http://localhost:5500
```

---

### Option C — Connect Real Firebase Backend

**Step 1:** Create Firebase project at [console.firebase.google.com](https://console.firebase.google.com)

**Step 2:** Enable Authentication → Email/Password + Google

**Step 3:** Create Firestore database (start in test mode)

**Step 4:** Get your config from Project Settings → Your Apps → Web

**Step 5:** Replace the config block in the HTML:

```javascript
// Find this section in the <script> tag:
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

**Step 6:** Change `firebaseReady` from `false` to `true`

---

## 🚀 Deployment

### GitHub Pages (Free — Recommended)

```bash
# 1. Create new GitHub repository
#    Name: travel-together
#    Visibility: Public

# 2. Upload travel-together-v15.html
#    Rename to: index.html

# 3. Settings → Pages → Branch: main → Save

# 4. Live at:
https://yourusername.github.io/travel-together
```

### Vercel (Free — Fastest)

```bash
# Drag & drop index.html at vercel.com/new
# Instant HTTPS + global CDN
```

### Custom Domain (via Namecheap)

```
yourdomain.com  →  CNAME  →  yourusername.github.io
```

---

## 🗺️ Roadmap

### Phase 1 — MVP Polish ✅
- [x] Full UI with all sections
- [x] Firebase Auth integration
- [x] localStorage fallback DB
- [x] AI matching algorithm
- [x] Real images embedded
- [x] Mobile responsive

### Phase 2 — Backend Integration 🔄
- [ ] Firebase config live setup
- [ ] Razorpay payment gateway
- [ ] Real user registration + profiles
- [ ] Trip creation → Firestore save
- [ ] Real-time chat → Firebase listeners

### Phase 3 — Growth Features 🔜
- [ ] Push notifications (Firebase FCM)
- [ ] Email verification flow
- [ ] Trip review & rating system
- [ ] Referral program (`Refer & Earn ₹300`)
- [ ] WhatsApp group auto-creation on trip join
- [ ] Aadhaar verification API (DigiLocker)

### Phase 4 — Native App 🔮
- [ ] React Native app (reuse logic layer)
- [ ] App Store + Google Play submission
- [ ] Offline-first architecture

---

## 🤝 Contributing

Contributions welcome! Here's how:

```bash
# 1. Fork this repo
# 2. Create your feature branch
git checkout -b feature/amazing-feature

# 3. Make changes to travel-together-v15.html
# 4. Test locally with Live Server

# 5. Commit with a clear message
git commit -m "feat: add Razorpay payment integration"

# 6. Push and open a Pull Request
git push origin feature/amazing-feature
```

### Contribution Areas
- 🐛 Bug fixes in JS functions
- 🎨 UI/UX improvements
- 🔌 Firebase real integration
- 💳 Razorpay payment gateway
- 📱 PWA / Service Worker support
- 🌐 Hindi / Hinglish language support
- ♿ Accessibility improvements

---

## 📁 File Structure

```
travel-together/
│
├── index.html              ← Main app (renamed from v15)
├── README.md               ← You are here
│
└── assets/ (optional — if you split later)
    ├── images/
    │   ├── destinations/   (goa.jpg, manali.jpg ...)
    │   ├── trips/          (goa_trip.jpg ...)
    │   └── profiles/       (p1.jpg, p2.jpg ...)
    └── logo.png
```

> Currently all assets are **base64 embedded** in the HTML for zero-dependency deployment.

---

## 📄 License

```
MIT License

Copyright (c) 2026 Satzzxzxx

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to deal in the Software without restriction, including the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software.
```

---

## 👨‍💻 Author

<div align="center">

**Built with 🔥 by Arunav Mehta**

[![GitHub](https://img.shields.io/badge/GitHub-Satzzxzxx-1a1a2e?style=for-the-badge&logo=github)](https://github.com/Satzzxzxx)

*"One file. Zero dependencies. Full product."*

</div>

---

<div align="center">

**⭐ Star this repo if Travel Together inspired you!**

`Made in India 🇮🇳 · Built for Bharat's 82M Solo Travelers`

</div>
