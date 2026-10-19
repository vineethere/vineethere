<h1 align="center">Vineet Arora</h1>
<p align="center">
  <b>Full-Stack Software Engineer @ Jio Platforms</b><br/>
  React &amp; TypeScript on the front &middot; Node.js &amp; Express behind it &middot; Mumbai, India
</p>

<p align="center">
  <a href="https://linkedin.com/in/vineet-arora-tech"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:vineetarora2001@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### What I do

I ship **production web applications end to end** - from the React interface a customer touches, down through the REST layer, to the data behind it.

At **Jio Platforms** I build for **Jio.com** and **MyJio**, where "works on my machine" does not count because it has to hold up across SIT, replica and prod for real customers at national scale. Reusable component systems, API contract design with backend teams, Core Web Vitals, accessibility that actually matters, and Next.js where SSR earns its place.

Alongside that I build and ship my own **Node.js and Express services** - REST API design, JWT authentication, role-based access control, MongoDB - the same way I ship frontends: understanding every line, not just prompting one into existence.

---

### How I build

```mermaid
flowchart LR
    subgraph FE["Frontend - React / TypeScript"]
        UI[Component library<br/>design system]
        ST[State<br/>Redux Toolkit]
        PF[Performance<br/>LCP - CLS - INP]
    end
    subgraph API["API - Node.js / Express"]
        RT[Routes]
        MW[Middleware<br/>auth - RBAC - validation]
        CT[Controllers]
    end
    subgraph DATA["Data"]
        DB[(MongoDB<br/>schema - indexes)]
    end
    UI --- ST --- PF
    FE -->|REST| RT
    RT --> MW --> CT --> DB
    CT -->|JSON| FE
```

---

### Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend &amp; Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Testing &amp; Delivery**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### Shipped at Jio

| Product | What I built | Scale |
|---|---|---|
| **Opinio Surveys** | In-house survey &amp; analytics platform - owned UX design, survey builder, response pipeline and real-time dashboards, end to end | 30+ teams &middot; 200K+ interactions |
| **Jio Devices storefront** | E-commerce catalog - dynamic pricing, discount rendering, category filtering, JioMart checkout | 6.3M+ visitors |
| **Jio AirFiber booking** | Built from scratch, including third-party integrations (Google Maps) | MyJio - 500M+ installs |
| **JioFiber Home Move** | Fiber relocation journey - serviceability lookup, appointment booking, request tracking | Jio.com |

---

### Building now

- **[Virtual Event Management Backend](https://github.com/vineethere/Backend-System-for-a-Virtual-Event-Management-Platform)** - Express REST API with JWT auth, role-based access control, event CRUD and async email notifications
- **[FinEdge](https://github.com/vineethere/FinEdge-NodeJs-Backend)** - Node.js + Express backend for a personal finance application
- **[DSA in JavaScript](https://github.com/vineethere/DSA-JavaScript-)** - daily problem solving

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vineethere&layout=compact&hide_border=true&langs_count=6&hide=java,cmake,c%2B%2B,scss,makefile,batchfile&theme=default" height="150" alt="Top languages"/>
  <img src="https://streak-stats.demolab.com?user=vineethere&hide_border=true&theme=default" height="150" alt="Streak"/>
</p>

<p align="center"><i>Top 100 India &mdash; Snapchat AR Hackathon &nbsp;&middot;&nbsp; Top Performer &mdash; Coding Ninjas DSA (96%+)</i></p>
