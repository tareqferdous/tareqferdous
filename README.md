<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f6e56,100:1D9E75&height=120&section=header&text=Tareq%20Ferdous&fontSize=36&fontColor=ffffff&fontAlignY=65&desc=Full%20Stack%20Developer&descAlignY=85&descSize=16&descColor=d1fae5" />

</div>

<div align="center">

**I build production-grade web apps — from database schema to deployed UI.**

[![Profile Views](https://komarev.com/ghpvc/?username=tareqferdous&color=1D9E75&style=flat&label=Profile+Views)](https://github.com/tareqferdous)
[![Email](https://img.shields.io/badge/Email-tareqferdous10%40gmail.com-1D9E75?style=flat&logo=gmail&logoColor=white)](mailto:tareqferdous10@gmail.com)

</div>

---

## About Me

I'm a **Full Stack Developer** from Bangladesh, currently building production-ready apps with the **MERN stack + Next.js + TypeScript**. I care about clean architecture, type safety, and shipping things that actually work.

- 🔭 Latest build: **AgroLink** — a full-stack agricultural marketplace solving the middleman problem for Bangladeshi farmers
- ⚙️ Currently deepening: **Next.js App Router · TypeScript · PostgreSQL · Stripe integrations**
- 📐 Interested in: system design, role-based auth flows, and real-world payment handling
- 📄 Resume: [View CV](https://drive.google.com/file/d/1yoPRBmas1JsXbB3XM5GmLxIAR57XQlJy/view?usp=sharing)

---

## Tech Stack

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![SASS](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)

**Database & ORM**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat&logo=Prisma&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat&logo=Firebase&logoColor=white)

**Tools & Infra**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white)

---

## Featured Project

### 🌾 AgroLink — Agricultural Market Linkage Platform

> Bangladesh has 16M+ farming households. A multi-layer middleman system captures 60–80% of value between farm and market. AgroLink cuts them out entirely.

**What it does:**
- Farmers list crops → multiple buyers compete with bids → farmer picks the best offer
- Stripe collects payment **upfront** before delivery — farmers can't be cheated
- Payment releases to farmer wallet only after buyer confirms receipt
- Full admin panel: listing approvals, order monitoring, refund management, analytics dashboard

**Stack:** `Next.js 16` · `TypeScript` · `Express.js` · `PostgreSQL (Neon)` · `Prisma` · `Stripe` · `Better Auth` · `Zod` · `Vercel`

**Key engineering challenges solved:**
- `acceptBid` — 5 atomic DB operations using `prisma.$transaction()` (accept bid, reject others, close listing, create order, trigger emails)
- Stripe `return_url` payment confirmation flow — handling charge before order state sync
- RBAC with per-route ownership checks across 3 roles (Farmer / Buyer / Admin)

[![View Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat&logo=github)](https://github.com/tareqferdous)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=tareqferdous&show_icons=true&hide_border=true&count_private=true&theme=vue&bg_color=00000000&title_color=1D9E75&icon_color=1D9E75" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tareqferdous&layout=compact&hide_border=true&theme=vue&bg_color=00000000&title_color=1D9E75" height="165" />

<img src="https://streak-stats.demolab.com/?user=tareqferdous&hide_border=true&ring=1D9E75&fire=0f6e56&currStreakLabel=1D9E75" />

</div>

---

## Get In Touch

- 📧 **Email:** [tareqferdous10@gmail.com](mailto:tareqferdous10@gmail.com)
- 💼 **Resume:** [Google Drive](https://drive.google.com/file/d/1yoPRBmas1JsXbB3XM5GmLxIAR57XQlJy/view?usp=sharing)
- 👥 **Facebook:** [tareq.ferdos.7](https://fb.com/tareq.ferdos.7/)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1D9E75,100:0f6e56&height=80&section=footer" />

</div>
