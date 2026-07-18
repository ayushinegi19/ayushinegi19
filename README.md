<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,100:4c1d95&height=200&section=header&text=Ayushi%20Negi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20Security-Focused%20Backend%20Engineer&descAlignY=55&descSize=18)

<a href="https://github.com/ayushinegi19">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=Final-Year+Computer+Engineering+Student;Building+Production+Systems+for+Real+Clients;Security+%26+Backend+Systems+Enthusiast" alt="Typing SVG" />
</a>

<br/>

![Location](https://img.shields.io/badge/📍-Mumbai,_India-4c1d95?style=flat-square)
![Status](https://img.shields.io/badge/🎓-Final_Year_B.E._Computer_Engineering-6D28D9?style=flat-square)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-8B5CF6?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayushinegi)
[![Email](https://img.shields.io/badge/Email-Contact-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:negiayushij@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-4c1d95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ayushinegi19)

![Profile Views](https://komarev.com/ghpvc/?username=ayushinegi19&color=8B5CF6&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/ayushinegi19?style=flat-square&color=6D28D9&label=Followers)

</div>

---

### About Me

I'm a final-year Computer Engineering student who builds full-stack systems end to end — from gathering requirements with a real client through to production deployment and maintenance. My flagship project, **VaultKey**, implements envelope encryption, fail-closed RBAC, and audit logging in a backend secrets manager — I care about building systems that are secure by design, not just functional.

Outside of that, I've independently designed, built, and now maintain **IGKA**, a full-stack management system for a real institute client, handling everything from CORS and JWT debugging to ongoing feature requests.

**Currently focused on:** deepening data structures & algorithms, and strengthening backend system design.

---

### Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-6D28D9?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-4c1d95?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-8B5CF6?style=flat-square&logo=javascript&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-6D28D9?style=flat-square&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-4c1d95?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-8B5CF6?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Databases**
![Node.js](https://img.shields.io/badge/Node.js-6D28D9?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-4c1d95?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-8B5CF6?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-6D28D9?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-4c1d95?style=flat-square&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-8B5CF6?style=flat-square&logo=mongodb&logoColor=white)

**Cloud & Tooling**
![Vercel](https://img.shields.io/badge/Vercel-6D28D9?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-4c1d95?style=flat-square&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-8B5CF6?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-6D28D9?style=flat-square&logo=postman&logoColor=white)

---

### Featured Projects

<details open>
<summary><b>🔐 VaultKey — Secrets Management System</b></summary>
<br/>

Backend secrets manager built to explore secure-by-design system architecture.

| | |
|---|---|
| **Stack** | Node.js, Express, raw PostgreSQL (no ORM) |
| **Security** | AES-256-GCM envelope encryption, fail-closed RBAC, append-only audit logging |
| **Scope** | 6 REST API endpoints — identity, auth, secret storage/retrieval, policy management, audit access |
| **Verification** | Automated test suite covering login, encryption, access control, and audit logging |

Every secret is encrypted with its own data key, which is itself encrypted by a master key. Access policies map (role, resource, action) to allow/deny, with no matching policy defaulting to deny — access is denied unless explicitly permitted.

🔗 [Repository](https://github.com/ayushinegi19/VAULTKEY)

</details>

<details>
<summary><b>🥋 IGKA — Karate Institute Management System</b></summary>
<br/>

Full-stack management system independently designed and built for a real institute client — from requirement gathering through phased delivery to launch.

| | |
|---|---|
| **Stack** | React/Vite (Vercel), Node.js/Express (Render), Supabase |
| **Scope** | Authentication, role-based permissions, CRUD across students, events, galleries, and announcements |
| **Ownership** | Full client relationship — feedback cycles, deployment, and independent production debugging (CORS, JWT, environment config, route ordering) |

*This repository is private (active client project). Happy to walk through the architecture directly — reach out via email or LinkedIn.*

</details>

<details>
<summary><b>📚 Prepify — AI-Powered Study Material Generator</b></summary>
<br/>

| | |
|---|---|
| **Stack** | JWT auth, MongoDB, NLP pipeline |
| **AI/NLP** | spaCy, KeyBERT, Sentence Transformers for automated content structuring |
| **Reliability** | API fallback handling to maintain uptime during model/API failures |

🔗 [Repository](https://github.com/ayushinegi19/PREPIFY)

</details>

<details>
<summary><b>📰 PulseFeed — Personalized News Aggregator</b></summary>
<br/>

| | |
|---|---|
| **Stack** | Flask backend, category-based filtering |
| **Features** | Article recommendation, bookmarking, infinite scroll, responsive layout |

🔗 [Repository](https://github.com/ayushinegi19/PULSEFEED)

</details>

---

### Experience

**Independent Developer** — IGKA (Karate Institute Client) · *Apr 2026 – Present*
Volunteered to design, build, and deploy a full-stack system for a real client, owning the relationship end to end — requirements, delivery, and ongoing production maintenance.
`React` `Node.js` `Supabase` `Client Communication`

**Software and Media Intern** — Anvitech Services LLC · *Apr 2026 – May 2026*
Produced scripts and platform-formatted content for company channels under recurring deadlines.
`Content Production` `Deadline Management`

---

### GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ayushinegi19&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=8B5CF6&icon_color=6D28D9&text_color=c9d1d9" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ayushinegi19&theme=tokyonight&hide_border=true&background=1a1b27&stroke=8B5CF6&ring=6D28D9&fire=8B5CF6&currStreakLabel=8B5CF6" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayushinegi19&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=8B5CF6&text_color=c9d1d9" width="48%" />

</div>

---

### Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ayushinegi19&theme=tokyo-night&hide_border=true&bg_color=1a1b27&color=8B5CF6&line=6D28D9&point=c9d1d9" width="95%" />

</div>

---

### Current Focus

```yaml
Learning: Data Structures & Algorithms, System Design fundamentals
Building: Deeper security-focused backend systems
Exploring: Full-stack architecture patterns for production reliability
Open To: Software Engineering internships and full-time roles
```

---

<div align="center">

*"Build it, break it, understand why, fix it properly."*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,100:1e1b4b&height=100&section=footer)

</div>
