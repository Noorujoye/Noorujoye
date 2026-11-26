<h1 align="center">Noorain Warsi</h1>

<p align="center">
  Java backend developer. I build REST APIs, auth, and approval workflows with Spring Boot and PostgreSQL.<br/>
  B.Tech CSE (2027) · Indore, India · Looking for a Software Engineering / Backend internship
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/noorainwarsi/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:joyenooru@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://leetcode.com/Noorain_Warsi"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <!-- TODO: add your resume link, e.g. a PDF in a repo or Google Drive -->
  <a href="RESUME_LINK_HERE"><img src="https://img.shields.io/badge/Resume-111111?style=for-the-badge&logo=readme&logoColor=white" alt="Resume" /></a>
</p>

---

## About

- Final-year B.Tech student (Computer Science and Engineering, RGPV) at Chameli Devi Institute of Professional Studies, Indore.
- I like backend problems where the rules matter: who is allowed to do what, in which order, and what gets recorded.
- Built a vendor invoice approval system for the Indore Municipal Corporation (IMC) as a live project.
- Solve DSA problems on LeetCode to keep my fundamentals sharp.

## Experience

**Java Backend Developer Intern, Indore Municipal Corporation** · Dec 2025 – Jan 2026
- Built a three-stage invoice approval workflow (Creator → Verifier → Approver) with server-side validation of every state transition.
- Implemented stateless JWT authentication with Spring Security and BCrypt, including access and refresh tokens.
- Added GST calculation (9% CGST + 9% SGST) and a multipart upload service with a 5 MB limit.

**Backend Developer Intern, TruckHai** · Jan 2026 – Feb 2026 · Remote
- Debugged REST API integration issues in a microservices setup by tracing request/response serialization mismatches with Postman.
- Worked in an Agile/Scrum team and helped improve backend error-handling responses.

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,postgres,azure,git,github,maven,postman&perline=8" alt="Backend and tools" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind,js&perline=8" alt="Frontend" />
</p>

Spring MVC · Spring Data JPA · Hibernate · Spring Security · JWT · REST APIs · SQL · Microsoft Azure · Axios · i18next

## Featured project

### [IMC Vendor Management and Invoice Approval System](https://github.com/Noorujoye/Indore-Muncipal-Corporation-website)
`Java 21` `Spring Boot` `PostgreSQL` `React 19` `Vite` `Spring Security` `JWT` `Azure`

A full-stack platform for a municipal procurement use case.

- **Approval state machine:** a vendor invoice moves through Creator → Verifier → Approver → Paid. The backend rejects any attempt to skip a stage or act without the right role.
- **Auth:** stateless JWT with a 15-minute access token and 7-day refresh token, BCrypt password hashing, and an Axios interceptor that handles token refresh without racing requests.
- **Data:** PostgreSQL schema with 8 entities, composite unique constraints, automatic GST split, and immutable audit logs. Database hosted on Microsoft Azure.
- **Frontend:** English and Hindi UI, responsive from 360px wide, and email notifications over Brevo SMTP.
- **Testing:** 42 manual QA scenarios, all passing.

<!-- TODO: add a live demo link and 1-2 screenshots of the approval flow -->
<!-- Example: [Live demo](https://your-demo-link) · [Architecture diagram](link) -->

### Modular AI Conversational Agent Service
`Spring Boot 3` `RestClient` `Strategy Pattern` `React`

A backend that can switch between third-party LLM providers through the Strategy pattern, with a response pipeline that renders formatted Markdown in the React frontend.

<!-- TODO: add the repo link -->

## Currently working on

- Containerizing the IMC project with Docker
- Setting up a GitHub Actions pipeline (build, test, deploy)
- Writing JUnit and Mockito tests for the approval workflow
- Adding Swagger/OpenAPI docs to the APIs

## Certifications

- Oracle Cloud Infrastructure (OCI) Developer Professional, 2025
- Java Programming and Data Structures, GeeksforGeeks, 2025

---

## GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Noorujoye&show_icons=true&hide_border=true&theme=dark&bg_color=00000000" />
    <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Noorujoye&show_icons=true&hide_border=true&theme=default&bg_color=00000000" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Noorujoye&layout=compact&hide_border=true&theme=dark&bg_color=00000000" />
    <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Noorujoye&layout=compact&hide_border=true&theme=default&bg_color=00000000" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Noorujoye&theme=dark&hide_border=true&background=00000000" />
    <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=Noorujoye&theme=default&hide_border=true&background=00000000" />
  </picture>
</p>

## LeetCode

<p align="center">
  <a href="https://leetcode.com/Noorain_Warsi">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://leetcard.jacoblin.cool/noorain_warsi?theme=dark&font=Inter" />
      <img alt="LeetCode stats" src="https://leetcard.jacoblin.cool/noorain_warsi?theme=light&font=Inter" />
    </picture>
  </a>
</p>

## Contribution graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Noorujoye/Noorujoye/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Noorujoye/Noorujoye/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

<p align="center">
  Open to internships. Email me at <a href="mailto:joyenooru@gmail.com">joyenooru@gmail.com</a>
</p>
