<div align="center">
 
<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Tahmid%20Islam&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Robotics%20Engineer%20%7C%20Social%20Impact%20Builder&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>
 
<!-- Profile Views + Social Badges -->
<p>
  <a href="https://github.com/Tahmidd2">
    <img src="https://komarev.com/ghpvc/?username=Tahmidd2&label=Profile%20Views&color=302b63&style=flat-square" alt="profile views"/>
  </a>
  <a href="https://github.com/Tahmidd2?tab=followers">
    <img src="https://img.shields.io/github/followers/Tahmidd2?label=Followers&style=flat-square&color=302b63&labelColor=0f0c29" alt="followers"/>
  </a>
  <a href="https://github.com/Tahmidd2?tab=repositories">
    <img src="https://img.shields.io/badge/Repos-5-302b63?style=flat-square&labelColor=0f0c29" alt="repos"/>
  </a>
  <a href="https://www.linkedin.com/in/tahmid-islam-720a37307/">
    <img src="https://img.shields.io/badge/LinkedIn-Tahmid%20Islam-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
  <img src="https://img.shields.io/badge/Open%20To%20Work-Yes-24243e?style=flat-square&labelColor=0f0c29&color=57f542" alt="open to work"/>
</p>
 
---
 
### *"Code that creates opportunity. Software that solves real problems."*
 
</div>
 
---
 
## 🧭 Table of Contents
 
- [👋 About Me](#-about-me)
- [🚀 Featured Projects](#-featured-projects)
  - [🔍 Internyl — Opportunity Discovery Platform](#-internyl--opportunity-discovery-platform)
  - [⚡ Volta NYC — Nonprofit Website](#-volta-nyc--nonprofit-website)
  - [🤖 StuyPulse FRC Robotics — Aunt Mary (2025)](#-stuypulse-frc-robotics--aunt-mary-2025)
  - [🤖 StuyPulse FRC Robotics — Tribecbot (2026)](#-stuypulse-frc-robotics--tribecbot-2026)
  - [🌐 Volta Higher Learning Website](#-volta-higher-learning-website)
- [🛠️ Tech Stack](#️-tech-stack)
- [📊 GitHub Stats](#-github-stats)
- [🗺️ Roadmap & Goals](#️-roadmap--goals)
- [🤝 Contributing](#-contributing)
- [📬 Contact](#-contact)
 
---
 
## 👋 About Me
 
Hi, I'm **Tahmid Islam** — a developer who builds things that matter. I've shipped production web apps serving real users, written robot control code that competed at the highest levels of FIRST Robotics, and helped launch nonprofit platforms designed to level the playing field for students from underrepresented backgrounds.
 
I care about code that's **clean, purposeful, and accessible** — whether that's a TypeScript frontend reaching thousands of students, a Next.js site powering a nonprofit's mission, or a Java swerve drive commanding a 120-lb competition robot.
 
> 🏫 Stuyvesant High School &nbsp;|&nbsp; 🏙️ New York City &nbsp;|&nbsp; 🤝 Member of [internyl-dev](https://github.com/internyl-dev), [Volta-NYC](https://github.com/Volta-NYC), [StuyPulse](https://github.com/StuyPulse)
 
<details>
<summary>📌 <strong>A little more about me...</strong></summary>
<br/>
 
- 🛠️ I've contributed **221+ commits** to a production web app (Internyl) and **523+ commits** to FRC robot code
- 🤖 My robotics team, StuyPulse, competes at the FIRST Robotics Championship — I helped write the 2025 *and* 2026 robot control code
- 🌱 I'm passionate about making opportunity equitable — Internyl was built specifically for students from underrepresented backgrounds
- 💡 I love the intersection of design and engineering: clean UIs backed by solid architecture
- 🏆 GitHub achievements: Pair Extraordinaire × 2, Pull Shark × 2, YOLO
 
</details>
 
---
 
## 🚀 Featured Projects
 
---
 
### 🔍 Internyl — Opportunity Discovery Platform
 
<div align="center">
 
[![Internyl Repo](https://img.shields.io/badge/Repo-internyl--frontend-302b63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/internyl-dev/internyl-frontend)
[![Live Site](https://img.shields.io/badge/Live-internyl.org-24243e?style=for-the-badge&logo=vercel&logoColor=white)](https://internyl.org)
[![Stars](https://img.shields.io/github/stars/internyl-dev/internyl-frontend?style=for-the-badge&color=302b63&labelColor=0f0c29)](https://github.com/internyl-dev/internyl-frontend/stargazers)
[![License](https://img.shields.io/badge/License-AGPL--3.0-302b63?style=for-the-badge)](https://github.com/internyl-dev/internyl-frontend/blob/main/LICENSE.md)
[![TypeScript](https://img.shields.io/badge/TypeScript-99.8%25-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/internyl-dev/internyl-frontend)
 
</div>
 
> *One platform. Hundreds of opportunities. Zero paywalls.*
 
Internyl is a web app that **scrapes the internet for extracurricular opportunities** — internships, programs, and more — and presents them in a clean, intelligent, filterable interface. Built with a custom AI system that surfaces the most relevant opportunities for each student. Free and accessible to all, with a specific focus on students from **underrepresented backgrounds**.
 
#### ✨ Key Features
 
| Feature | Description |
|---|---|
| 🧠 AI Recommendation Engine | Smart suggestions based on saved items and browsing behavior |
| 🔎 Advanced Filters | Filter by subject, cost, eligibility, due date, duration, and more |
| ✅ Eligibility Checklist | Step-by-step checklist for each program's requirements |
| 📊 User Dashboard | Track saved opportunities and application progress |
| 🐛 Report Page | Community-driven bug and data quality reporting |
| 🔐 Auth & Persistence | Firebase Authentication + Firestore for personalized experiences |
 
<details>
<summary>🗂️ <strong>Project Structure</strong></summary>
 
```
internyl/
├── public/
└── src/
    ├── app/
    │   ├── pages/          # about, account, internships, login, signup...
    │   └── api/
    └── lib/
        ├── components/     # Navbar, InternshipCard, SearchBar, Footer...
        ├── hooks/          # useRecommendationEngine, useAdminCheck
        ├── modules/        # dateUtils, scoreInternship, toggleBookmark...
        └── types/          # internshipCard, userPreferences, report
```
 
</details>
 
<details>
<summary>⚙️ <strong>Installation & Running Locally</strong></summary>
 
```bash
# Clone the repository
git clone https://github.com/internyl-dev/internyl-frontend.git
cd internyl-frontend
 
# Install dependencies
npm install
 
# Set up Firebase config
cp .env.example .env.local
# Fill in your Firebase credentials in .env.local
 
# Start the development server
npm run dev
```
 
Open [http://localhost:3000](http://localhost:3000) 🎉
 
</details>
 
**Tech Stack:** `Next.js` · `TypeScript` · `Tailwind CSS` · `Firebase Auth` · `Firestore` · `React`
 
**Other Internyl Repos:**
- [`data-augmentor-agent`](https://github.com/internyl-dev/data-augmentor-agent) — AI data enrichment pipeline
- [`program-discovery-agent`](https://github.com/internyl-dev/program-discovery-agent) — Web scraping + discovery agent
- [`data-acquisition-pipeline`](https://github.com/internyl-dev/data-acquisition-pipeline) — Data ingestion system
 
---
 
### ⚡ Volta NYC — Nonprofit Website
 
<div align="center">
 
[![Volta NYC Repo](https://img.shields.io/badge/Repo-voltanyc-302b63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Volta-NYC/voltanyc)
[![Live Site](https://img.shields.io/badge/Live-voltanyc.org-24243e?style=for-the-badge&logo=vercel&logoColor=white)](https://voltanyc.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-95%25-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/Volta-NYC/voltanyc)
 
</div>
 
> *Volta NYC — connecting local businesses with NYC student talent.*
 
The official website for **Volta's New York City branch** — a nonprofit that pairs student consultants with local businesses and BIDs (Business Improvement Districts). Built with Next.js 14 App Router, deployed to Vercel, with custom Tailwind color tokens, Framer Motion animations, and integrated contact/application forms.
 
#### ✨ Key Features
 
| Feature | Description |
|---|---|
| 🎨 Custom Design System | Brand colors (`v-green`, `v-blue`, `v-bg`, `v-ink`) via Tailwind config |
| 🌀 Framer Motion Animations | Scroll-reveal sections and animated number counters |
| 📝 Student Application Flow | Google Forms integration → automatic Google Sheets tracking |
| 💼 Business Inquiry Form | Formspree-powered contact form → team email |
| 🗺️ Showcase Page | BID partners + business clients portfolio |
| 🔀 Domain Redirects | Automatic 301 redirects from legacy domains |
| 🗂️ Auto Sitemap & Robots | Generated at build-time from `NEXT_PUBLIC_SITE_URL` |
 
<details>
<summary>⚙️ <strong>Running Locally</strong></summary>
 
```bash
git clone https://github.com/Volta-NYC/voltanyc.git
cd voltanyc
npm install
npm run dev
# Open http://localhost:3000
```
 
</details>
 
**Tech Stack:** `Next.js 14` · `TypeScript` · `Tailwind CSS` · `Framer Motion` · `Formspree` · `Vercel`
 
---
 
### 🤖 StuyPulse FRC Robotics — Aunt Mary (2025)
 
<div align="center">
 
[![Aunt Mary Repo](https://img.shields.io/badge/Repo-Aunt--Mary-302b63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StuyPulse/Aunt-Mary)
[![Stars](https://img.shields.io/github/stars/StuyPulse/Aunt-Mary?style=for-the-badge&color=302b63&labelColor=0f0c29)](https://github.com/StuyPulse/Aunt-Mary/stargazers)
[![Forks](https://img.shields.io/github/forks/StuyPulse/Aunt-Mary?style=for-the-badge&color=24243e&labelColor=0f0c29)](https://github.com/StuyPulse/Aunt-Mary/forks)
[![License](https://img.shields.io/badge/License-MIT-302b63?style=for-the-badge)](https://github.com/StuyPulse/Aunt-Mary/blob/main/LICENSE)
[![Java](https://img.shields.io/badge/Java-100%25-f89820?style=for-the-badge&logo=java&logoColor=white)](https://github.com/StuyPulse/Aunt-Mary)
 
</div>
 
> *523 commits. 20 stars. One robot that made it to Championship.*
 
**Aunt Mary** is StuyPulse Team 694's competition robot for the **2025 FIRST Robotics Competition season** — *Reefscape*. A highly capable robot featuring swerve drive, Limelight-based vision, a multi-stage elevator+arm, and multiple scoring mechanisms for coral and algae game pieces.
 
#### 🦾 Mechanisms & Systems
 
| System | Description |
|---|---|
| 🔄 Swerve Drive | Field-relative drive with full odometry |
| 👁️ Limelight Vision | AprilTag-based field localization and auto-align |
| 🏗️ Elevator + Arm | Multi-position coral scoring (L1–L4) |
| 🪸 Coral Funnel | Intake and channeling mechanism |
| 🎯 Shooter | Barge-to-L4 scoring subsystem |
| 🐸 Froggy | L1 and processor-level scoring mechanism |
| 🧗 Deep Climb | End-game cage climb mechanism |
| 💡 LEDs | Driver feedback and state indication |
 
**Released at:** Regional → District Championship → **FIRST Championship (Champs)**
 
**Tech Stack:** `Java` · `WPILib` · `Gradle` · `Limelight` · `NetworkTables` · `Shuffleboard`
 
---
 
### 🤖 StuyPulse FRC Robotics — Tribecbot (2026)
 
<div align="center">
 
[![Tribecbot Repo](https://img.shields.io/badge/Repo-Tribecbot-302b63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StuyPulse/Tribecbot)
[![Stars](https://img.shields.io/github/stars/StuyPulse/Tribecbot?style=for-the-badge&color=302b63&labelColor=0f0c29)](https://github.com/StuyPulse/Tribecbot/stargazers)
[![Forks](https://img.shields.io/github/forks/StuyPulse/Tribecbot?style=for-the-badge&color=24243e&labelColor=0f0c29)](https://github.com/StuyPulse/Tribecbot/forks)
[![Java](https://img.shields.io/badge/Java-100%25-f89820?style=for-the-badge&logo=java&logoColor=white)](https://github.com/StuyPulse/Tribecbot)
 
</div>
 
> *The next evolution. Currently in active development for the 2026 season.*
 
**Tribecbot** is StuyPulse's 2026 competition robot, actively under development. Building on the lessons from Aunt Mary with improved subsystem architecture and autonomous capabilities.
 
---
 
### 🌐 Volta Higher Learning Website
 
<div align="center">
 
[![Higher Learning Repo](https://img.shields.io/badge/Repo-higher--learning--website-302b63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Volta-NYC/higher-learning-website)
[![TypeScript](https://img.shields.io/badge/TypeScript-primary-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/Volta-NYC/higher-learning-website)
 
</div>
 
A dedicated web presence for Volta's Higher Learning initiative — expanding the nonprofit's reach into education-focused programming.
 
---
 
## 🛠️ Tech Stack
 
<div align="center">
 
### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-f89820?style=for-the-badge&logo=openjdk&logoColor=white)
 
### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
 
### Backend & Data
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Firestore-FF6F00?style=for-the-badge&logo=firebase&logoColor=white)
 
### Robotics
![WPILib](https://img.shields.io/badge/WPILib-1B3A5C?style=for-the-badge&logo=java&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Limelight](https://img.shields.io/badge/Limelight_Vision-lime?style=for-the-badge)
 
### Tooling & Deployment
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
 
</div>
 
---
 
## 📊 GitHub Stats
 
<div align="center">
 
<img src="https://github-readme-stats.vercel.app/api?username=Tahmidd2&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=a78bfa&icon_color=818cf8&text_color=e2e8f0&ring_color=7c3aed" width="49%" alt="Tahmid's GitHub Stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Tahmidd2&theme=tokyonight&hide_border=true&background=0f0c29&ring=7c3aed&fire=818cf8&currStreakLabel=a78bfa" width="49%" alt="Tahmid's Streak"/>
 
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tahmidd2&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f0c29&title_color=a78bfa&text_color=e2e8f0&langs_count=6" width="49%" alt="Top Languages"/>
 
</div>
 
<div align="center">
 
### 🏆 GitHub Achievements
 
[![Pair Extraordinaire](https://img.shields.io/badge/🤝_Pair_Extraordinaire-×2-7c3aed?style=flat-square)](https://github.com/Tahmidd2?achievement=pair-extraordinaire&tab=achievements)
[![Pull Shark](https://img.shields.io/badge/🦈_Pull_Shark-×2-7c3aed?style=flat-square)](https://github.com/Tahmidd2?achievement=pull-shark&tab=achievements)
[![YOLO](https://img.shields.io/badge/🎲_YOLO-7c3aed?style=flat-square)](https://github.com/Tahmidd2?achievement=yolo&tab=achievements)
 
</div>
 
---
 
## 🗺️ Roadmap & Goals
 
```
2025 ──────────────────────────────────────────────────────────────────── 2026+
  │                                                                          │
  ✅ Shipped Internyl v1 (Next.js + Firebase + AI Recommendations)          │
  ✅ Built Volta NYC website (live at voltanyc.org)                          │
  ✅ Wrote FRC 2025 robot code → competed at FIRST Championship              │
  ✅ Contributing to Tribecbot (2026 FRC season)                             │
  🔄 Internyl 2.0 — Scholarships directory + school org portals             │
  🔄 Internal dashboard for Volta (Supabase auth + db layer)                │
  🎯 Expand AI agents: program-discovery + data-augmentor pipelines         │
  🎯 Open source contributions beyond team/org repos                        │
  🎯 Building in public more                                                 │
```
 
---
 
## 🤝 Contributing
 
All of my active org repositories welcome contributions! Here's how to get involved:
 
```bash
# 1. Fork the repo you want to contribute to
# 2. Create a feature branch
git checkout -b feature/your-feature-name
 
# 3. Make your changes
# 4. Commit with a clear message
git commit -m "feat: add your feature description"
 
# 5. Push and open a Pull Request
git push origin feature/your-feature-name
```
 
Please follow the existing code style and include meaningful commit messages. For major changes, open an issue first to discuss what you'd like to change.
 
---
 
## 📬 Contact
 
<div align="center">
 
| Platform | Link |
|---|---|
| 🐙 GitHub | [@Tahmidd2](https://github.com/Tahmidd2) |
| 💼 LinkedIn | [Tahmid Islam](https://www.linkedin.com/in/tahmid-islam-720a37307/) |
| 🌐 Internyl | [contactinternyl@gmail.com](mailto:contactinternyl@gmail.com) |
| 🌍 Volta NYC | [voltanyc.org](https://voltanyc.org) |
| 🔍 Internyl | [internyl.org](https://internyl.org) |
 
</div>
 
---
 
<div align="center">
 
<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Tahmidd2&bg_color=0f0c29&color=a78bfa&line=7c3aed&point=818cf8&area=true&hide_border=true" width="95%" alt="Activity Graph"/>
 
---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>
 
*Built with ☕, curiosity, and a healthy respect for clean architecture.*
 
**⭐ If any of my projects helped you, a star goes a long way!**
 
</div>
