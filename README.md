<a name="top"></a>

<div align="center">

<a href="https://github.com/b-fame"><img src="https://komarev.com/ghpvc/?username=b-fame&label=Profile%20Views&color=2563eb&style=flat" alt="Profile views" /></a>

<br><br>

# Blaise Serge Rutayisire

**Software Engineer &nbsp;•&nbsp; AI Enthusiast &nbsp;•&nbsp; Cybersecurity Learner &nbsp;•&nbsp; Gamer**

`@b-fame` &nbsp;—&nbsp; Kigali, Rwanda

<br>

I build full-stack web applications end to end — from relational schema design and
REST APIs to session-based authentication and role-based access control. My work
lives at the intersection of shipping reliable software and understanding how it
fails, so **security and AI sit beside the product, not after it.**

</div>

<br>

```text
const bFame = {
  name:   "Blaise Serge Rutayisire",
  handle: "@b-fame",
  role:   "Software Engineer",
  based:  "Kigali, Rwanda",
  focus:  ["Full-Stack Engineering", "AI", "Cybersecurity"],
  stack:  ["React", "Node.js", "Express", "MySQL"]
};
```

<br>

<div align="center">

### Navigation

[About](#about) &nbsp;·&nbsp; [Stack](#stack) &nbsp;·&nbsp; [Projects](#projects) &nbsp;·&nbsp;
[Spotlight](#spotlight) &nbsp;·&nbsp; [Focus](#focus) &nbsp;·&nbsp; [Activity](#activity) &nbsp;·&nbsp;
[Connect](#connect)

</div>

---

<a name="about"></a>

## About

I'm a software engineer working primarily in the **JavaScript** ecosystem, building
full-stack applications with **React** on the front end and **Node.js / Express**
with **MySQL** on the back end.

My main project — a wash-bay payment management system — is a complete operational
tool rather than a demo: it models a real business flow (vehicle entry, timed
pricing, cash-out, reporting) and enforces **three-tier role-based access control**
(`admin`, `manager`, `cashier`) with hashed credentials and a full audit trail.
That project taught me that the difference between software that runs and software
you can trust lives in the unglamorous parts: input validation, authorization
checks on every route, and logging what actually happened.

Outside of building, I'm drawn to **artificial intelligence** and
**cybersecurity** — understanding how systems are attacked is what makes me a
better engineer about how they're built. I'm a gamer, too. Competitive
multiplayer has trained the same instinct that good engineering demands:
iterate fast, read the feedback, adapt.

<br>

<a name="stack"></a>

## Tech Stack

Everything listed here is either used in my own code or is part of my daily workflow.

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | <img src="https://img.shields.io/badge/React-1F2937?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/JavaScript-1F2937?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/HTML5-1F2937?style=for-the-badge&logo=html5&logoColor=E34F26" alt="HTML5"> <img src="https://img.shields.io/badge/CSS3-1F2937?style=for-the-badge&logo=css3&logoColor=1572B6" alt="CSS3"> <img src="https://img.shields.io/badge/Tailwind_CSS-1F2937?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS"> <img src="https://img.shields.io/badge/Bootstrap-1F2937?style=for-the-badge&logo=bootstrap&logoColor=7952B3" alt="Bootstrap"> |
| **Backend** | <img src="https://img.shields.io/badge/Node.js-1F2937?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js"> <img src="https://img.shields.io/badge/Express-1F2937?style=for-the-badge&logo=express&logoColor=FFFFFF" alt="Express"> <img src="https://img.shields.io/badge/REST_API-1F2937?style=for-the-badge&logo=swagger&logoColor=85EA2D" alt="REST API"> <img src="https://img.shields.io/badge/Session_Auth-1F2937?style=for-the-badge&logo=passport&logoColor=FFFFFF" alt="Session Auth"> <img src="https://img.shields.io/badge/bcrypt-1F2937?style=for-the-badge&logo=bcrypt&logoColor=F97316" alt="bcrypt"> |
| **Database** | <img src="https://img.shields.io/badge/MySQL-1F2937?style=for-the-badge&logo=mysql&logoColor=4479A1" alt="MySQL"> <img src="https://img.shields.io/badge/MariaDB-1F2937?style=for-the-badge&logo=mariadb&logoColor=003545" alt="MariaDB"> <img src="https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=sql&logoColor=FFFFFF" alt="SQL"> |
| **Tools** | <img src="https://img.shields.io/badge/Git-1F2937?style=for-the-badge&logo=git&logoColor=F05032" alt="Git"> <img src="https://img.shields.io/badge/GitHub-1F2937?style=for-the-badge&logo=github&logoColor=FFFFFF" alt="GitHub"> <img src="https://img.shields.io/badge/VS_Code-1F2937?style=for-the-badge&logo=visualstudiocode&logoColor=0098FF" alt="VS Code"> <img src="https://img.shields.io/badge/Postman-1F2937?style=for-the-badge&logo=postman&logoColor=FF6C37" alt="Postman"> |

<br>

<a name="projects"></a>

## Projects

All public repositories on this account.

| Project | What It Is | Stack | Links |
| :--- | :--- | :--- | :--- |
| **Car Wash Bay Payment Management System** | Full-stack system for running a car wash: vehicle entry/exit, time-based pricing, payments, role-based access, audit logs and reports. | React · Tailwind CSS · Express · MySQL | [Source](https://github.com/b-fame/car-wash-bay-payements) |
| **School Management System** *(fork)* | A fork of the open-source `Volunteer-Tech` project that I keep as a **reference implementation** — I have not contributed code to it. | React · Node.js · Express | [My fork](https://github.com/b-fame/school-management-system-in-react-node-js-and-express-js) · [Upstream](https://github.com/Volunteer-Tech/school-management-system-in-react-node-js-and-express-js) |
| **b-fame** | This profile repository. | — | [Source](https://github.com/b-fame/b-fame) |

<br>

<a name="spotlight"></a>

## Featured Project

<div align="center">

### Car Wash Bay Payment Management System

**Repository →** [github.com/b-fame/car-wash-bay-payements](https://github.com/b-fame/car-wash-bay-payements)

</div>

**The problem.** A wash bay runs on a simple loop — a car arrives, a service is
selected, time passes, money changes hands — but doing that with paper and
memory means no accuracy, no accountability, and no idea what the business
actually earned. This system turns that loop into a tracked, auditable workflow.

**What it does**

- **Vehicle entry / exit** — register a vehicle, prevent duplicate plates in the
  bay, and record exit time automatically on payment
- **Dynamic pricing engine** — base fee is derived from vehicle size × package
  (Basic / Special / VIP), with a **20% surcharge per additional hour** parked
- **Package management** — full CRUD on service packages, restricted to admins
- **Authentication** — registration and login with **bcrypt**-hashed passwords
  and server-side **sessions** (8-hour expiry, `httpOnly` cookies)
- **Role-based access control** — three tiers enforced per route:
  `cashier` (operations) · `manager` (reports) · `admin` (users, packages, audit)
- **Audit trail** — every meaningful action (login, payment, vehicle edit,
  deletion) is written to `activity_logs` with actor, details, IP and timestamp
- **Reporting** — daily revenue by size and package, monthly revenue trends, and
  fleet statistics, built with grouped SQL rather than application-side loops
- **Operations dashboard** — vehicles, revenue, and payments currently in the bay

**Architecture**

```text
┌─────────────────────────────┐        ┌──────────────────────────────┐
│  frontend/  React 18 SPA    │  HTTP  │  backend/  Express API      │
│  Tailwind CSS · Axios       │ ─────► │  express-session · bcrypt    │
│  localhost:3000             │ ◄───── │  localhost:8000              │
└─────────────────────────────┘  JSON  └──────────────┬───────────────┘
                                                      │ mysql2
                                            ┌─────────▼─────────┐
                                            │  MySQL / MariaDB  │
                                            │  users · vehicles │
                                            │  packages ·        │
                                            │  payments · logs   │
                                            └───────────────────┘
```

<details>
<summary><b>API surface — 26 REST endpoints, access-controlled per route</b></summary>

| Method | Endpoint | Access |
| :--- | :--- | :--- |
| `POST` | `/api/auth/register` | Public |
| `POST` | `/api/auth/login` | Public |
| `POST` | `/api/auth/logout` | Public |
| `GET` | `/api/auth/session` | Public |
| `GET` | `/api/auth/me` | Authenticated |
| `GET` | `/api/vehicles` | Authenticated |
| `GET` | `/api/vehicles/active` | Authenticated |
| `POST` | `/api/vehicles` | Authenticated |
| `POST` | `/api/vehicles/:id/exit` | Authenticated |
| `PUT` | `/api/vehicles/:id` | Manager · Admin |
| `DELETE` | `/api/vehicles/:id` | Admin |
| `GET` | `/api/packages` | Authenticated |
| `POST` | `/api/packages` | Admin |
| `PUT` | `/api/packages/:id` | Admin |
| `DELETE` | `/api/packages/:id` | Admin |
| `POST` | `/api/payments` | Authenticated |
| `GET` | `/api/payments` | Authenticated |
| `GET` | `/api/reports/daily` | Manager · Admin |
| `GET` | `/api/reports/monthly` | Manager · Admin |
| `GET` | `/api/reports/vehicles` | Manager · Admin |
| `GET` | `/api/users` | Admin |
| `POST` | `/api/users` | Admin |
| `PUT` | `/api/users/:id` | Admin |
| `DELETE` | `/api/users/:id` | Admin |
| `GET` | `/api/activity-logs` | Admin |
| `GET` | `/api/stats` | Authenticated |

<br>

**Database — 5 tables**, InnoDB / `utf8mb4`:
`users` · `vehicles` · `packages` · `payments` · `activity_logs`
with foreign keys `payments → vehicles · packages · users` and
`activity_logs → users`, plus `ON DELETE CASCADE` on vehicle removal.

</details>

<br>

**Engineering notes.** The pricing logic lives on the server, not the client —
a browser that never computes the fee is a browser that can't be edited to pay
one. Authorization is enforced with `checkRole()` middleware on the route itself
rather than hidden buttons in the UI. Activity logging is centralised in a single
helper, so auditing isn't something a future endpoint can quietly forget to do.

<br>

<a name="focus"></a>

## Currently Exploring

<div align="center">

**Artificial Intelligence** &nbsp;•&nbsp; **Cybersecurity** &nbsp;•&nbsp;
**System Design** &nbsp;•&nbsp; **Modern Web Applications**

</div>

- **Artificial Intelligence** — moving from interest to practice; understanding
  where models genuinely help a product versus where they're just overhead
- **Cybersecurity** — authentication, authorization, and secure defaults as a
  design concern rather than a last-minute patch
- **System design** — how a monolithic Express API should be decomposed when it
  outgrows a single service
- **Applied security in practice** — taking the auth and access-control patterns
  from my main project and hardening them

<br>

<a name="activity"></a>

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=b-fame&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=false" alt="GitHub stats" width="330" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=b-fame&theme=tokyonight&hide_border=true" alt="Contribution streak" width="330" />

</div>

<br>

<div align="center">

<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs?username=b-fame&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Most used languages" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=b-fame&theme=tokyonight" alt="Profile details" width="330" />

</div>

<br>

> Statistics are pulled live from the GitHub API and refresh automatically.
> Contribution data reflects **public repositories only** — private work never
> appears here.

<br>

<a name="philosophy"></a>

## Engineering Philosophy

<div align="center">

> ### Build it. Break it. Harden it. Ship it.

</div>

Understand how a system fails before you claim it works. Security isn't a phase
at the end — it's an access-control check on every route. And a feature that
isn't measured, logged, and testable is just a guess with a UI.

<br>

<a name="connect"></a>

## Connect With Me

<div align="center">

<a href="https://github.com/b-fame"><img src="https://img.shields.io/badge/GitHub-b--fame-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
&nbsp;
<a href="https://instagram.com/__rutayisire"><img src="https://img.shields.io/badge/Instagram-__rutayisire-111827?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
&nbsp;
<a href="mailto:blaisefam5242@gmail.com"><img src="https://img.shields.io/badge/Email-blaisefam5242@gmail.com-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br><br>

**Open to software engineering opportunities, collaborations, and interesting problems.**

<!--
  OPTIONAL CONTACTS — uncomment any line below and drop in your real URL.
  Nothing here is rendered until you uncomment it, so there are no dead links.

  <br><br>
  <a href="https://linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-YOUR_HANDLE-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/YOUR-HANDLE"><img src="https://img.shields.io/badge/X-YOUR_HANDLE-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://YOUR-DOMAIN.com"><img src="https://img.shields.io/badge/Portfolio-YOUR-DOMAIN.com-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
-->

</div>

---

<div align="center">

<sub>
Blaise Serge Rutayisire &nbsp;·&nbsp; <a href="https://github.com/b-fame">@b-fame</a>
&nbsp;·&nbsp; <a href="#top">Back to top ↑</a>
</sub>

</div>
