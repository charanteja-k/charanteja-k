<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=280&section=header&text=Charan%20Teja&fontSize=60&fontColor=b19cd9&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%2FML%20Builder%20%7C%20Full%20Stack%20Developer&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+intelligent+products+end-to-end;AI%2FML+%7C+Full+Stack+%7C+Product+Engineering;Turning+hackathon+ideas+into+production+systems;Currently+shipping+PADO+%E2%80%94+an+adaptive+interview+AI" alt="Typing SVG" />

<br/>

[![University](https://img.shields.io/badge/University-JNTUH-6D28D9?style=flat-square&logo=googlescholar&logoColor=white)](#)
[![Regulation](https://img.shields.io/badge/Program-CSE%20%7C%20R22-7C3AED?style=flat-square&logo=readthedocs&logoColor=white)](#)
[![Location](https://img.shields.io/badge/Based%20in-Telangana%2C%20India-8B5CF6?style=flat-square&logo=googlemaps&logoColor=white)](#)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=A78BFA)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](#)
[![Gmail](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=A78BFA)](#)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=A78BFA)](#)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=charanteja-k&style=flat-square&color=6D28D9&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/charanteja-k?style=flat-square&color=7C3AED&label=Followers&logo=github)
![Stars](https://img.shields.io/github/stars/charanteja-k?style=flat-square&color=8B5CF6&label=Total+Stars&logo=github)

</div>

<br/>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Sparkling%20Heart.png" width="28"/> About Me

<div align="center">
<table>
<tr>
<td>

Computer Science and Engineering (Artificial Intelligence & Machine Learning) undergraduate with hands-on experience in **full-stack web development**, **AI-powered application development**, and **cybersecurity**. I've built AI-powered and full-stack software solutions through internships and independent projects, transforming ideas into practical applications using modern technologies. Driven to solve real-world problems by developing secure, intelligent, and user-centric software while continuously strengthening software engineering fundamentals.

</td>
</tr>
</table>
</div>

```yaml
Open To:
  - Software Engineering Internships (Full Stack / AI-ML)
  - Cybersecurity / Network Security Roles
  - AI-Powered Product Development
  - Hackathons & Collaborative Builds
```

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="28"/> Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,js,ts,java,cpp,c,php&theme=dark" />

<br/><br/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,html,css,tailwind,js,vite&theme=dark" />

<br/><br/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,express,php,mysql,postgres,mongodb&theme=dark" />

<br/><br/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,docker,git,github,linux,vscode,postman,figma&theme=dark" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Robot.png" width="28"/> AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Classical ML — XGBoost** | ⭐⭐⭐⭐☆ | Hyperparameter-tuned XGBoost model (via RandomizedSearchCV) used in PADO to predict placement probability from DSA, Aptitude, Communication, and CGPA signals |
| **Local LLM Orchestration**  | ⭐⭐⭐⭐☆ |  Privacy-first local LLM used in PADO to parse resumes, extract skills, and generate personalized weekly study roadmaps — zero data leakage, no reliance on paid APIs |
| **Audio / Speech Processing** | ⭐⭐⭐☆☆ | Whisper for transcription and Librosa for audio-based confidence scoring in PADO's mock interview flow |
| **AI Integration & Prompt Engineering** | ⭐⭐⭐⭐☆ | Practical integration of Gemini API, OpenAI, and OpenRouter API (NVIDIA Nemotron VL, Gemma, Mistral) across multiple projects |
| **AI Image Analysis** | ⭐⭐⭐⭐☆ | Vision-model-based marine pollution detection in Samudra-Netra using OpenRouter's free-tier vision models |

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" width="28"/> Featured Projects

<details>
<summary><b>🧠 PADO — Placement Assessment and Development Orchestrator</b></summary>
<br/>

Next-generation AI placement preparation ecosystem featuring an adaptive mock interview agent driven by a dynamic **Thought → Action → Observation** loop, built as a hackathon project.

| Aspect | Details |
|---|---|
| **Stack** | Next.js, React, TypeScript, Tailwind CSS, GSAP, FastAPI (Python), SQLite, NextAuth.js, XGBoost, Scikit-learn, OpenAI, Whisper, Librosa |
| **Architecture** | Split into `pado-web` (Next.js/React frontend with GSAP-driven interview UI) and `backend` (FastAPI, hosting the XGBoost model and orchestrating the local LLM) |
| **Core Feature** | The interview agent queries the candidate's last-answered question history to dynamically branch subsequent questions |
| **Performance** | Hyperparameter-tuned XGBoost model (RandomizedSearchCV) predicts placement probability (0–100%) from DSA, Aptitude, Communication, and CGPA |
| **Security** | Local LLM orchestration keeps resume parsing and roadmap generation on-device — zero data leakage, no dependency on paid external APIs |
| **Audio Pipeline** | Librosa for confidence scoring, Whisper for transcription |
| **Repository** | [View Repository](https://github.com/charanteja-k/pado) |

</details>

<details>
<summary><b>🌊 Samudra-Netra (Ocean's Eye) — AI Marine Pollution Detection Platform</b></summary>
<br/>

An AI-powered ocean conservation platform built for **SDG Goal 14: Life Below Water** — upload ocean images to detect pollution, chat with the marine conservation assistant "Pruthvi," and track environmental impact within a community of ocean guardians.

| Aspect | Details |
|---|---|
| **Stack** | Next.js 16 (App Router), Tailwind CSS 4, OpenRouter API (NVIDIA Nemotron VL, Gemma, Mistral), Firebase Firestore, Firebase Auth (Google + Email), Cloudinary, GNews.io API |
| **Scale** | Full platform with dashboard, community feed, chatbot, and news integration |
| **Security** | All API keys stored as environment variables (never in source); server-side keys (`OPENROUTER_API_KEY`, `FIREBASE_PRIVATE_KEY`, `CLOUDINARY_API_SECRET`) are only accessible inside API routes; only `NEXT_PUBLIC_` prefixed variables are exposed client-side; `.env` excluded via `.gitignore` |
| **Impact** | Combines AI pollution detection with community reporting to support environmental monitoring and awareness |
| **Deployment** | Vercel |
| **Repository** | [View Repository](https://github.com/charanteja-k/samudranetra) · [Live Demo](https://samudranetra.vercel.app/) |

</details>

<details>
<summary><b>💬 Charcha — WhatsApp-Inspired Messaging Web App</b></summary>
<br/>

A messaging web application inspired by WhatsApp's UX, deliberately built on a lean, framework-free stack.

| Aspect | Details |
|---|---|
| **Stack** | XAMPP, Apache, PHP, MySQL, Vanilla JavaScript, GSAP, Tailwind CSS (CDN) |
| **Scale** | Full messaging application — no build tools, no frameworks |
| **Performance** | Lightweight delivery via CDN-based styling and vanilla JS interactivity |
| **Security** | Server-side PHP/MySQL request handling |
| **Impact** | Complete PRD + master UI/UX overhaul prompt targeting an Apple/Stripe-grade aesthetic |
| **Repository** | [View Repository](https://github.com/charanteja-k/charcha_xampp) |

Charcha proves that constraint-driven engineering — no frameworks, no build pipeline — can still produce a polished, animated, production-feel messaging experience through disciplined use of GSAP and a full design token system.

</details>

<details>
<summary><b>📋 disAPPear — Productivity Companion with AI Study Hub</b></summary>
<br/>

A dark glassmorphic productivity web app combining core task management with an AI-powered Study Hub.

| Aspect | Details |
|---|---|
| **Stack** | Next.js 16 (App Router), TypeScript, SQLite via Prisma ORM, NextAuth.js v5 (Credentials), Google Gemini API, Framer Motion, Canvas API, Mermaid.js, Recharts |
| **Core Features** | Dashboard, Tasks & Todos, Reminders, Daily Planner, Analytics |
| **AI Study Hub** | AI Notes (Q&A), Summarizer (summaries, key concepts, questions, key terms), AI Study Planner, Quiz Maker (MCQs with scoring & explanations), AI-generated Mermaid.js flowcharts |
| **UI Detail** | Animated login screen with a cursor-tracking sun and meteor particle background |
| **Security** | NextAuth.js v5 session encryption via `AUTH_SECRET`; registration restricted to `@gmail.com` addresses only |
| **Repository** | [View Repository](#) |

</details>

<details>
<summary><b>🔍 Netscan v7 — AI-Powered Network Scanner</b></summary>
<br/>

A desktop network scanning application inspired by Zenmap, built during an internship, with more efficient TCP connect scans.

| Aspect | Details |
|---|---|
| **Stack** | Python, PyQt, Nmap |
| **Performance** | Completes a full scan in under a minute using variable scan speeds, with a double-check pass in fast scan mode |
| **Configurability** | Each scan mode uses a different thread timeout and thread count |
| **Interface** | Interactive GUI with multiple scanning modes for host discovery, port scanning, and network analysis |
| **Repository** | [View Repository](#) |

</details>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Briefcase.png" width="28"/> Experience

<div align="center">

### Hackers Gurukul

</div>

**Cybersecurity Intern**
- Worked with Kali Linux and cybersecurity tools including Nmap, Wireshark, and Burp Suite for network analysis and security assessment
- Developed Python-based cybersecurity utilities while strengthening practical knowledge of networking, vulnerability assessment, and ethical hacking

**Research & Development Intern**
- Developed AI-powered software prototypes and full-stack web applications using modern frameworks and AI-assisted development workflows
- Contributed to research and development initiatives exploring software architecture, automation, and practical AI integration

`Python` `Kali Linux` `Nmap` `Wireshark` `Burp Suite` `AI Integration` `Full Stack Development`

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activity/Trophy.png" width="28"/> Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 Hack-the-Matrix 1st Place Winner of Domain Multi AI | Technidhi 2026 — Built PADO, an adaptive AI interview agent, in a 14-hour sprint |
| 🏆 First Prize — Coding Competition | Won a cash-prize coding competition at TKR College |
| 🇮🇳 Smart India Hackathon | Participant |
| 🎤 Event Organization | Led the organization of Freshers, Codeathon, and Prompt Detective events |
| 💻 Sreyas Developers Conference (SDC) | Participant |

</div>

---


## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Direct%20Hit.png" width="28"/> Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=FFA116)](https://leetcode.com/u/charanteja_k/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-000000?style=for-the-badge&logo=geeksforgeeks&logoColor=2F8D46)](#)
[![HackerRank](https://img.shields.io/badge/HackerRank-000000?style=for-the-badge&logo=hackerrank&logoColor=2EC866)](https://www.hackerrank.com/profile/charanteja_kond1)
[![CodeChef](https://img.shields.io/badge/CodeChef-000000?style=for-the-badge&logo=codechef&logoColor=A78BFA)](https://www.codechef.com/users/super_swan_79)

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="28"/> GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=charanteja-k&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=charanteja-k&theme=radical&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" />

<br/>

<img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=charanteja-k&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activity/Military%20Medal.png" width="28"/> GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=charanteja-k&theme=radical&no-frame=true&no-bg=true&margin-w=15&column=7" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activity/Chart%20Increasing.png" width="28"/> Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=charanteja-k&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C4B5FD" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Nature/Snake.png" width="28"/> Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/charanteja-k/charanteja-k/main/github-contribution-grid-snake-dark.svg" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Direct%20Hit.png" width="28"/> Current Focus

```yaml
Learning:
  - Advanced Agentic AI Architectures
  - Distributed Systems Fundamentals
  - Cloud-Native Deployment Patterns

Building:
  - PADO — Adaptive AI Interview Agent (Thought-Action-Observation loop)
  - Samudra-Netra — AI Marine Pollution Detection Platform

Strengthening:
  - Cybersecurity fundamentals (Kali Linux, Nmap, Wireshark, Burp Suite)
  - Full-stack + AI-integrated product development

Open To:
  - Software Engineering Internships
  - Cybersecurity Roles
  - Collaborative Hackathon Builds
```

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" width="28"/> Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-000000?style=for-the-badge&logo=gmail&logoColor=A78BFA)](mailto:kondakallacharanteja@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://linkedin.com/in/charanteja22)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=A78BFA)](https://github.com/charanteja-k)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=A78BFA)](#)

</div>

---

<div align="center">

*"Ship it like it's production, even when it's a class assignment."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=150&section=footer" width="100%"/>

</div>
