<h1 align="center">Hi, I'm Bohdan Bats 👋</h1>

<p align="center">
  <b>Full Stack Developer · 5 years of experience · .NET & React & Flutter · AI Product Owner</b><br/>
  Lviv, Ukraine 🇺🇦
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bohdan-bats-6611a11b7/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Bohdan%20Bats-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:batsbohdan@gmail.com">
    <img src="https://img.shields.io/badge/Email-batsbohdan@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://principles.top" target="_blank">
    <img src="https://img.shields.io/badge/Principles-principles.top-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About Me

.NET developer with 5+ years of commercial experience building multithreading and scalable backend, desktop, web, and mobile applications using ASP .NET Core, .NET MAUI, PostgreSQL, Python, React.js, Vue.js, Azure, WPF, and Flutter. Experienced in migrating legacy systems to modern frameworks, implementing CI/CD processes, and deploying large-scale production applications. Focused on integrating AI capabilities and automation into production systems. Experience spans fintech, productivity, file-sharing, and edtech domains.

Alongside full-time development work, personally designed, built, and shipped **Principles** — an AI-powered productivity app — as Founder and Tech Lead (Flutter production client, ASP.NET Core API, React marketing site; previously .NET MAUI). Currently teach software engineering and programming at the college level, combining product ownership, engineering, and mentorship.

---

## 🛠️ Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Platforms**

![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MS SQL](https://img.shields.io/badge/MS%20SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Cloud & DevOps**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)

---

## 🚀 Featured Projects

### 🧠 [Principles: Habits for Goals](https://principles.top) - *AI-powered productivity product*
> An AI assistant for building habits, tracking goals, and managing tasks. **Production client is Flutter** (iOS, Android & macOS) with real users and revenue. Designed and shipped end-to-end as solo founder + tech lead.

Four repositories make up the product:

| Layer | Repo | Role |
|-------|------|------|
| 📱 **Flutter client** *(production)* | [flutter-frontend-of-principles](https://github.com/bob-byte/flutter-frontend-of-principles) | Current store / production app (iOS, Android, macOS): MVVM, offline SQLite + incremental sync, home-screen widgets, deep links, local notifications, AI Helper chat, EN/UK l10n |
| ⚙️ **Backend API** | [backend-of-principles-app](https://github.com/bob-byte/backend-of-principles-app) | ASP.NET Core 10 WebAPI: JWT auth (email / Apple / Google), goals · habits · tasks, bootstrap + incremental sync, AI chat & recommendations, reminders, FCM silent sync push, PostgreSQL + EF Core |
| 📲 **.NET MAUI client** | [maui-frontend-of-principles](https://github.com/bob-byte/maui-frontend-of-principles) | Earlier native Android/iOS client: encrypted SQLite, sync queue, MVVM, AdMob, local notifications — kept for reference and API/behavior parity |
| 🌐 **Marketing site** | [website-of-principles-app](https://github.com/bob-byte/website-of-principles-app) | React + Vite landing, legal pages, EN/UK i18n, themes, SEO, and account-deletion flow at [principles.top](https://principles.top) |

- **Stack:** Flutter (production) · ASP.NET Core · React · .NET MAUI (legacy client) · PostgreSQL · EF Core · SQLite · OpenAI / Azure OpenAI · Docker · FCM · MVVM
- Offline-first sync across devices (bootstrap + `/sync/changes`, tombstones, multi-device catch-up)
- AI Helper, habit/goal recommendations, and profile text suggestions with server-side API keys and cost-aware prompting

---

### 🔍 [Discovery Service](https://github.com/bob-byte/DiscoveryService) - *P2P local network node discovery*
> Finds nodes in a local network, runs periodic information updates, and enables file downloads from contacts.

- **Stack:** C# · WPF · .NET Framework · Multithreading · Docker · SOLID · Design Patterns

---

### 🛒 [Shop](https://github.com/bob-byte/Shop) - *E-commerce REST API*
> A backend e-commerce application with clean architecture.

- **Stack:** ASP.NET Web API · Entity Framework · .NET Framework · SQL Server

---

## 📚 Education & Certifications

### Education
- 🎓 **Master of Computer Science** - National Forestry University of Ukraine *(2022–2024)*
- 🎓 **Bachelor of Computer Science** - Ivan Franko National University of Lviv *(2018–2022)*

### Technical certifications
- 📜 **The Complete Flutter Guide: Build Android, iOS and Web apps** - Udemy *(May 2026)*
- 📜 **The Complete Course of .NET MAUI** - Udemy *(Jan 2026)*
- 📜 **Entity Framework in Depth: The Complete Guide** - Udemy *(Oct 2020)*
- 📜 **Advanced Windows Presentation Foundation (WPF)** - Udemy *(Jan 2021)*
- 📜 **Artificial Intelligence Technologies 2021 Summer School** - Ivan Franko National University of Lviv × GlobalLogic *(Jul 2021 · 120 h / 4 ECTS)*
- 📜 **Data Engineering and Security 2022 (DES 2022)** - Winter School, Ivan Franko National University of Lviv *(Feb 2022 · 120 h / 4 ECTS)*
- 📜 **Data Engineering and Security 2021 (DES 2021)** - Winter School, Ivan Franko National University of Lviv *(Feb 2021 · 120 h / 4 ECTS)*

### Soft skills
- 📜 **Depth 2.0** - Oleshko.pro *(Jan 2025 – Jan 2026)* - goals, values, internal motivation
- 📜 **Open Your Mouth - Online** - Oleshko.pro *(Oct–Nov 2024)* - public speaking, charisma, leadership communication

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bob-byte&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&hide=contribs" height="165" />
  <img src="https://streak-stats.demolab.com/?user=bob-byte&theme=tokyonight&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bob-byte&layout=compact&theme=tokyonight&hide_border=true&hide=html,c%2B%2B,python" height="165" />
</p>

---

<p align="center">
  <i>Open to Senior .NET / Flutter roles with AI integration. Let's build something great together.</i><br/>
  <a href="mailto:batsbohdan@gmail.com">batsbohdan@gmail.com</a> · <a href="https://www.linkedin.com/in/bohdan-bats-6611a11b7/">LinkedIn</a> · <a href="https://principles.top">principles.top</a>
</p>
