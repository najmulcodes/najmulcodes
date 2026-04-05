<div align="center">

# Najmul Hasan

### Full Stack Developer · MERN Stack · Next.js

I architect and ship production-ready web applications built on the JavaScript ecosystem.  
My work spans role-based systems, real-time infrastructure, payment pipelines, and AI integrations —  
with a consistent focus on clean architecture, maintainable code, and real organizational impact.

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://najmul-portfolio-six.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/najmulcodes/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:najmulhasanshahin@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/najmulcodes)

</div>

<br/>

---

## About

Full Stack Developer with a track record of delivering complete, deployed web systems — not prototypes. My background in Accounting & Finance (BBA) shaped how I think about software: requirements come from real workflows, data has business meaning, and systems need to be trustworthy before they go live.

I build across the full stack: React and Next.js for the frontend, Node.js and Express for the backend, MongoDB as the primary database. I've integrated Stripe payments, Socket.IO real-time sync, JWT/Firebase authentication, Cloudinary media management, and the Anthropic Claude API across production projects.

Currently focusing on backend architecture, API design, and scalable system patterns.

<br/>

---

## Tech Stack

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Database**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Integrations & Services**

![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Claude API](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=flat-square&logoColor=white)

**Tooling & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

<br/>

---

## Projects

> Ordered by architectural complexity, real-world impact, and system depth.

<br/>

### Badar Uddin Welfare — Production Charity Management System

[![Badar Uddin Welfare](./preview/badaruddin.png)](https://badaruddinwelfareorg.vercel.app/)

A live, organization-facing platform built to replace manual fund-tracking and approval workflows for a real charitable organization. The system implements role-based access across Admin and Member tiers, a full donation request lifecycle with admin approval gates, and Cloudinary-backed document and media handling. Designed with operational reliability as the primary constraint — data integrity and audit trails take precedence over feature surface area.

**Stack** — `React` `Node.js` `Express` `MongoDB` `JWT` `Cloudinary`

[Live Site](https://badaruddinwelfareorg.vercel.app/) · [Source Code](https://github.com/najmulcodes/badaruddinwelfare-client)

<br/>

---

### MicroTask Platform — Multi-Role Freelance Marketplace

[![MicroTask Platform](./preview/microtask.png)](https://microtask-client-iota.vercel.app)

A complete task marketplace architected around three distinct user roles: Workers, Buyers, and Admins — each with isolated dashboards, permissions, and data views. The platform handles the full task lifecycle from posting through submission and approval, integrates Stripe for a coin-based payment system, and uses Google OAuth alongside JWT for layered authentication. Role resolution happens at the API level, not just the UI, ensuring backend authorization integrity.

**Stack** — `React` `Node.js` `Express` `MongoDB` `Stripe` `JWT` `Firebase Auth`

> **Demo access** — `admin@microtask.com` / `Admin123` (Admin role)

[Live Site](https://microtask-client-iota.vercel.app) · [Source Code](https://github.com/najmulcodes/microtask-client)

<br/>

---

### LiveCollab — Real-Time Team Collaboration Platform

[![LiveCollab](./preview/livecollab.png)](https://livecollab-rho.vercel.app/)

A full-stack Kanban collaboration system with sub-100ms drag-and-drop sync across all connected clients via Socket.IO. The architecture uses rooms scoped per workspace to minimize broadcast surface, optimistic UI updates with server-side reconciliation for conflict resolution, and heartbeat-based presence tracking to handle unexpected disconnects cleanly. Workspaces support invite-code-based onboarding, member management, and a persistent timestamped activity log.

**Stack** — `React` `Vite` `Tailwind CSS` `Zustand` `React Query` `Node.js` `Express` `Socket.IO` `MongoDB` `JWT`

[Live Site](https://livecollab-rho.vercel.app/) · [Source Code](https://github.com/najmulcodes/livecollab-client)

<br/>

---

### DevFolio Analyzer — AI-Powered GitHub Profile Analysis

[![DevFolio Analyzer](./preview/devfolio-analyzer.png)](https://devfolio-analyzer.vercel.app/)

A full-stack analytics platform that fetches live GitHub profile data via the REST API, applies a deterministic scoring model across six weighted dimensions (repository volume, stars, follower count, activity cadence, profile completeness, and portfolio signal), then layers Anthropic Claude API-generated insights on top. The scoring pipeline runs independently of the AI layer, ensuring consistent results with graceful fallback when the API is unavailable. Authenticated users receive persistent history with score-over-time charting via Recharts; guests get immediate analysis with no friction.

**Stack** — `React` `Node.js` `Express` `MongoDB` `JWT` `GitHub REST API` `Anthropic Claude API` `Recharts`

[Live Site](https://devfolio-analyzer.vercel.app/) · [Source Code](https://github.com/najmulcodes/devfolio-analyzer)

<br/>

---

### Care.xyz — Care Service Booking Platform

[![Care.xyz](./preview/care.xyz.png)](https://care-xyz-baby-sitting-elderly-care.vercel.app)

A Next.js booking platform for professional caregivers built with cascading location selectors that filter availability by district and sub-district, a dynamic pricing engine that adjusts based on service type and duration, and Firebase-backed authentication with protected booking routes enforced at both the page and API level. The architecture prioritizes the booking flow UX — reducing steps between service discovery and confirmed booking.

**Stack** — `Next.js` `React` `Firebase` `Tailwind CSS`

[Live Site](https://care-xyz-baby-sitting-elderly-care.vercel.app) · [Source Code](https://github.com/najmulcodes/Care.xyz---Baby-Sitting-Elderly-Care-Service-Platform)

<br/>

---

### Gatherly — Community Discovery Platform

[![Gatherly](./preview/gatherly.png)](https://gatherly-navy.vercel.app/)

A Next.js 14 App Router platform that connects people with local communities across Bangladesh. Implements dual-provider authentication via NextAuth.js (credential-based and Google OAuth), a searchable and filterable community catalog, protected organizer routes enforced at the edge via Next.js middleware, and a community management dashboard with inline validation. Built mobile-first with a responsive layout designed for real-world browsing patterns.

**Stack** — `Next.js 14` `NextAuth.js` `Custom CSS` `localStorage`

[Live Site](https://gatherly-navy.vercel.app/) · [Source Code](https://github.com/najmulcodes/Gatherly)

<br/>

---

### ClubSphere — Club Membership & Event Management

[![ClubSphere](./preview/clubsphere.png)](https://clubsphere-client1.netlify.app/)

A MERN-stack club management system with role-scoped dashboards for administrators and members, a membership approval workflow, and event lifecycle management. Authorization is enforced at the API layer via JWT middleware — route access is determined server-side, not inferred from the client state.

**Stack** — `React` `Node.js` `Express` `MongoDB` `JWT`

[Live Site](https://clubsphere-client1.netlify.app/) · [Source Code](https://github.com/najmulcodes/clubsphere-client)

<br/>

---

### BookHub — Book Management Platform

[![BookHub](./preview/bookhub.png)](https://bookhub-heaven.surge.sh)

A full-stack CRUD platform for managing book records, demonstrating clean REST API design with Express, MongoDB document modeling, and React state management with real-time UI feedback on create, update, and delete operations. A focused project built to validate core full-stack integration patterns.

**Stack** — `React` `Node.js` `Express` `MongoDB`

[Live Site](https://bookhub-heaven.surge.sh) · [Source Code](https://github.com/najmulcodes/bookhub-client)

<br/>

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=najmulcodes&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
&nbsp;&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=najmulcodes&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=najmulcodes&theme=github-dark-blue&hide_border=true" />

<br/><br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=najmulcodes&theme=github-compact&hide_border=true&area=true&color=58a6ff&line=58a6ff&point=ffffff)](https://github.com/najmulcodes)

</div>

<br/>

---

## Currently Studying

- Backend architecture patterns — service layers, repository pattern, dependency injection
- System design — database indexing, caching strategies, horizontal scalability
- TypeScript in depth — generics, conditional types, strict-mode codebases
- Open source contribution workflow and maintaining public packages

<br/>

---

## Contact

**Email** — [najmulhasanshahin@gmail.com](mailto:najmulhasanshahin@gmail.com)  
**Portfolio** — [najmul-portfolio-six.vercel.app](https://najmul-portfolio-six.vercel.app)  
**LinkedIn** — [linkedin.com/in/najmulcodes](https://www.linkedin.com/in/najmulcodes/)  
**GitHub** — [github.com/najmulcodes](https://github.com/najmulcodes)

<br/>

---

<div align="center">
<sub>Available for full-time roles and freelance engagements · Dhaka, Bangladesh · Open to remote</sub>
</div>
