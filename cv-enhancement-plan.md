# CV Enhancement Plan — Frontend & React Native

**Target roles:** Senior Frontend (React/Next.js), React Native / Cross-Platform Mobile
**Date:** 2026-04-16

---

## 1. Professional Summary

**Problem:** Generic opener, no numbers, no scale.

**Rewrite opening sentence to:**

> Senior Frontend Developer with 8+ years of experience building high-performance e-commerce and social platforms at scale — including a React/Next.js web platform and cross-platform React Native app serving **58K+ monthly active users** across Singapore and Taiwan.

---

## 2. Technical Skills

Add missing tools from current HipVan stack:

- **ReactJS Ecosystem:** add `Tailwind CSS 4`, `Recharts`
- **React Native:** add `Firebase (Crashlytics, Auth)`, `MMKV`
- **Add new section — Monitoring & Analytics:** `AWS Athena`, `Sentry`, `Core Web Vitals / PageSpeed`

---

## 3. HipVan — Senior Frontend Engineer (Apr 2019 – Dec 2022)

**Problem:** Zero metrics. Biggest gap in the entire CV.

**Add these bullets (replace or supplement existing):**

- Led frontend performance optimization initiative, reducing LCP by **32% (3.1s → 2.1s)** and TTFB by **48% (1.3s → 674ms)** — meeting 4 of 5 Core Web Vitals targets for desktop (LCP, INP, FCP, TTFB); CLS at 0.17, improving toward 0.1 target
- Achieved **INP of 96ms** against 200ms OKR target (52% below goal) and **FCP of 1.8s** exactly meeting the target
- Maintained **94.6% sprint delivery rate** (peak) against 80% OKR target across bi-weekly Agile sprints

---

## 4. HipVan — Senior Mobile Engineer (Dec 2024 – Present)

**Problem:** "99% crash-free rate, <400ms app launch time" is vague — no user scale, no trend data.

**Replace existing metrics bullet and add:**

- Maintained cross-platform React Native app serving **58K+ monthly active users** across iOS and Android in 2 markets (Singapore + Taiwan) with **3,500+ DAU**
- Drove **5,000+ weekly installs** across all platforms; reduced **bug rate in sprint from 34.9% to 11.7%** over 15 sprints
- Achieved **99.87% crash-free rate** (iOS) with Firebase Crashlytics monitoring and proactive crash triage process
- Achieved **271ms app launch time** on iOS — 32% below the 400ms OKR target — through startup optimization and lazy loading of non-critical modules
- Implemented high-performance local storage using **MMKV**, replacing AsyncStorage for significantly faster read/write operations

---

## 5. HipVan — Mobile Engineer (Oct 2022 – Dec 2024)

**Problem:** 2+ years of work reduced to 1 generic line.

**Expand to:**

- Built and maintained e-commerce, social media, and analytics/tracking features for the Hipvan iOS & Android app in React Native — covering Collection Detail, Product Detail, Order & Checkout, and Search & Recommendations
- Contributed to growing the app user base to **11.5K+ MAU** on Android (SG) and **23K+ MAU** on iOS (SG)
- Collaborated with iOS and Android native teams to implement platform-specific bridges for features requiring native modules

---

## 6. Config — No Changes Needed

`config.yaml` already correctly targets both roles:

| Search name | Keywords |
|---|---|
| `senior-react-frontend` | React, Frontend, Front-end |
| `react-native` | React Native |

---

## Checklist

- [ ] Update Professional Summary with MAU figure
- [ ] Add Tailwind CSS 4, Recharts, Firebase, MMKV, AWS Athena to Technical Skills
- [ ] Add 4 metric bullets to HipVan Senior Frontend Engineer (2019–2022)
- [ ] Replace vague metrics in Senior Mobile Engineer (2024–Present) with specifics
- [ ] Expand Mobile Engineer (2022–2024) from 1 bullet to 3
