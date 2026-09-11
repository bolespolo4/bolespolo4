# Hi, I'm Boules Hisham Mokhtar 👋

### Senior Flutter Engineer · Mobile Architecture Specialist · CI/CD & DevOps Expert

[![LinkedIn](https://img.shields.io/badge/LinkedIn-boules--engineer-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/boules-engineer/) [![Email](https://img.shields.io/badge/Email-bolespolo4%40gmail.com-D14836?style=flat-square&logo=gmail)](mailto:bolespolo4@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-bolespolo4-181717?style=flat-square&logo=github)](https://github.com/bolespolo4) [![Profile Views](https://komarev.com/ghpvc/?username=bolespolo4&style=flat-square&color=1A56DB)](https://github.com/bolespolo4)

---

## 👨‍💻 About Me

Senior Flutter Engineer with **6+ years** architecting and delivering enterprise-grade, multi-platform mobile applications on Clean Architecture, SOLID principles, and Dart 3 sealed-class type safety.

Currently lead architect of **PAAS** at Qara Digital Solutions — a single-codebase platform powering **20+ live production apps** across the Saudi market, with a self-built multi-flavor CI/CD pipeline, a multi-theme control dashboard, and self-hosted release infrastructure.

Background spans full-stack web (Vue.js, React.js, Node.js, Laravel, Django) from earlier in my career, which now shows up as an advantage — I think about mobile apps in terms of the APIs and systems behind them, not just the UI layer.

```dart
class BoulesHisham {
  final String role     = "Senior Flutter Engineer / Mobile Architect";
  final String location = "Cairo, Egypt 🇪🇬 (Open to Remote / Relocation)";
  final String current  = "Lead Mobile Architect @ Qara Digital Solutions (KSA)";

  final List<String> expertise = [
    "Clean Architecture & SOLID Principles",
    "Dart 3 Sealed Classes & Type Safety",
    "BLoC / Cubit State Management",
    "Multi-Flavor CI/CD & Self-Hosted Runners",
    "Firebase Full-Stack Integration",
    "Full-Stack Background (Node.js, Django, React)",
  ];

  final String philosophy = "Build it right — not just make it work.";
}
```

---

## 🛠️ Tech Stack

### 📱 Mobile
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart_3-0175C2?style=flat-square&logo=dart&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)

### 🧠 Architecture & Patterns
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1A56DB?style=flat-square) ![SOLID](https://img.shields.io/badge/SOLID_Principles-1A56DB?style=flat-square) ![BLoC](https://img.shields.io/badge/BLoC_/_Cubit-1A56DB?style=flat-square) ![Repository Pattern](https://img.shields.io/badge/Repository_Pattern-1A56DB?style=flat-square) ![Sealed Classes](https://img.shields.io/badge/Sealed_Classes_(Dart_3)-1A56DB?style=flat-square)

### 🔥 Firebase
![Firebase Auth](https://img.shields.io/badge/Auth-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Crashlytics](https://img.shields.io/badge/Crashlytics-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![FCM](https://img.shields.io/badge/FCM_Messaging-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Firebase RTDB](https://img.shields.io/badge/Realtime_DB-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Firebase Analytics](https://img.shields.io/badge/Analytics-FFCA28?style=flat-square&logo=firebase&logoColor=black)

### ⚙️ DevOps & CI/CD
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions_(self--hosted)-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Fastlane](https://img.shields.io/badge/Fastlane-0F2000?style=flat-square&logo=fastlane&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![CapRover](https://img.shields.io/badge/CapRover-003366?style=flat-square) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle) ![CocoaPods](https://img.shields.io/badge/CocoaPods-EE3322?style=flat-square&logo=cocoapods&logoColor=white)

### 🌐 Full-Stack
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

### 🗄️ Data & Networking
![ObjectBox](https://img.shields.io/badge/ObjectBox-00C800?style=flat-square) ![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## 🚀 Key Projects

### 🏆 PAAS — Multi-Tenant Mobile Platform
> Flutter · Dart 3 · Firebase · ObjectBox · GitHub Actions

Single shared codebase powering **20+ live production apps** (Android + iOS) across the Saudi market.

- 🏗️ Feature-cluster modular Clean Architecture (`/clusters/`, `/users/`, `/core/`, `/di/`)
- ⚡ Remote Asset System (ObjectBox + Firebase RTDB) — **zero app releases required** for brand/theme updates
- 🔒 Dart 3 sealed-class ImageLoader — compile-time-safe image rendering
- 🔄 Self-hosted CI/CD: GitHub Actions runners on dedicated hardware + VPS, packaging every branded flavor from one codebase
- ✅ Automated CI-integrated QA pipeline (`flutter_test`, `bloc_test`, `mockito`) generating test-status reports on every PR

### 📦 Internal Package Monorepo — qara_widgets / qara_core / qara_auth / scanner
> Flutter · Dart · Package Architecture

4 internal Flutter packages enabling code reuse across the app suite, with strict versioned API boundaries between modules.

### 🛠️ Chameleon CLI — Multi-Environment Developer Tooling
> Node.js · TypeScript · Python · Shell

Production CLI for multi-environment config orchestration with graceful API fallback. Released as **v2.0.0**.

### ⚙️ Model Generator & 🎨 Resources Generator — Flutter/Dart Utilities
> Flutter · Dart · build_runner

Two open-source Flutter dev tools: build-time model code generation, and compile-time-safe access to UI resources (colors, fonts, assets).

### 🤖 AI-Integrated Toolkits — LLM, MCP & Slack Automation
> Node.js · LLM APIs · MCP Protocol

AI developer toolkits integrating LLM APIs and MCP for automated workflows and context-aware Slack notifications.

---

## 💼 Experience

```text
Senior Flutter Engineer — Lead Mobile Architect
Qara Digital Solutions · Sep 2023 – Present · Cairo, Egypt / Remote (KSA)

Head of Mobile Development
CorporateStack Solutions · Mar 2022 – Sep 2023 · Cairo, Egypt

Full-Stack Developer
Ergasti Digital · Oct 2019 – Mar 2022 · Cairo, Egypt
```

---

## 📜 Certifications

- 🎓 **CS50: Introduction to Computer Science** — Harvard University
- 🎓 **CS50: Introduction to Programming with Python** — Harvard University
- 🏅 **Flutter Apprentice** — Google

---

## 📊 GitHub Stats

[![bolespolo4's GitHub Stats](https://github-readme-stats.vercel.app/api?username=bolespolo4&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/bolespolo4)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=bolespolo4&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/bolespolo4)

---

## 🌍 Languages

- 🇪🇬 **Arabic** — Native
- 🇬🇧 **English** — Professional Proficiency
- 🇪🇸 **Spanish** — Beginner

---

## 🤝 Open To

- 💼 Senior Flutter / Mobile Engineer roles
- 🌍 Remote positions worldwide
- ✈️ Relocation opportunities
- 🤝 Open-source collaboration on Flutter packages

---

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/boules-engineer/) [![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bolespolo4@gmail.com)
