<!--
  LEARNING NOTES (safe to delete before committing)

  1. This file must live in a repo named exactly like your username
     (r0hitgit/r0hitgit) for it to show on your profile page.
  2. HTML comments like this one are invisible on GitHub, so they are
     a good place to leave notes for yourself.
  3. Most visuals here are images loaded from third-party services via
     URL query parameters. Changing the URL changes the image, so you
     can tweak colours and text without any design tool.
-->

<!-- ============ HEADER BANNER ============ -->
<!-- capsule-render draws the gradient wave. Key parameters:
     type=waving   -> wave shape (others: venom, soft, rect, cylinder)
     color=0:..    -> gradient stops written as position:hexcolor
     text=         -> main title (%20 is a space, %2C is a comma)
     desc=         -> subtitle line
     animation=fadeIn -> simple load animation -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:A78BFA,100:EC4899&height=220&section=header&text=Hi%2C%20I'm%20Rohit%20Verma&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Full%20Stack%20Developer%20%7C%20Java%20%2B%20Spring%20Boot%20%2B%20React&descAlignY=58&descSize=18&descColor=ffffff&animation=fadeIn" width="100%" alt="Header banner"/>
</div>

<!-- ============ TYPING ANIMATION ============ -->
<!-- The lines= parameter is separated by semicolons; each one is typed
     out in turn. Plus signs encode spaces. -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=700&lines=Java+Full+Stack+Developer;Spring+Boot+%2B+React+Builder;NexHire+is+live+at+nexhire.me;GenericMeds-AI+%7C+Generic+medicine+price+finder;Open+to+SDE+Internships" alt="Typing SVG" />
  </a>
</div>

<br/>

<!-- ============ QUICK LINKS ============ -->
<!-- shields.io "for-the-badge" style. Format: /badge/<label>-<colour>
     The logo= value comes from the simple-icons catalogue. -->
<div align="center">
  <a href="https://r0hithiside.vercel.app"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/r0hitin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://nexhire.me"><img src="https://img.shields.io/badge/NexHire-EC4899?style=for-the-badge&logo=googlechrome&logoColor=white" alt="NexHire"/></a>
  <a href="https://genericmeds-ai.vercel.app"><img src="https://img.shields.io/badge/GenericMeds--AI-A78BFA?style=for-the-badge&logo=googlechrome&logoColor=white" alt="GenericMeds-AI"/></a>
</div>

<br/>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=r0hitgit&color=8B5CF6&style=for-the-badge&label=PROFILE+VIEWS)
![GitHub followers](https://img.shields.io/github/followers/r0hitgit?color=EC4899&style=for-the-badge&logo=github)
![GitHub stars](https://img.shields.io/github/stars/r0hitgit?color=A78BFA&style=for-the-badge&logo=github)

</div>

---

## About Me

<!-- A two-column table is a common trick: left cell holds text,
     right cell holds a visual. GitHub strips most CSS, so tables
     and align attributes are the reliable layout tools. -->
<table>
<tr>
<td width="62%" valign="top">

- B.Tech CSE (AI & ML) '27 at **NIET**, Greater Noida
- I build end to end: backend APIs, frontend UI and the deployment pipeline
- Shipped **[NexHire](https://nexhire.me)**, a production job portal, and **[GenericMeds-AI](https://genericmeds-ai.vercel.app)**, an AI-assisted generic medicine finder
- Sharpening **DSA in Java** and exploring **System Design**
- Looking for **SDE internship opportunities**
- Fun fact: when I start building, the world disappears. I don't stop until it works.

</td>
<td width="38%" valign="top" align="center">

<!-- A small "terminal card" written in a fenced code block.
     The language tag (java) gives it syntax colours. -->

```java
public class Rohit {
  String role  = "Full Stack Dev";
  String stack = "Spring Boot + React";
  String goal  = "SDE Internship";

  void build() {
    while (!works) { keepGoing(); }
  }
}
```

</td>
</tr>
</table>

---

## Featured Projects

<!-- Three project cards in one table row. Each cell is its own card.
     Keeping descriptions to 2-3 lines keeps the row readable on mobile. -->

<table>
<tr>
<td width="33%" valign="top">

### NexHire
**Production full-stack job portal**

Role-based platform for candidates, recruiters and admins with JWT auth, email OTP, resume uploads and interview scheduling.

`Spring Boot` `React` `MySQL` `Docker` `JWT`

[Live Site](https://nexhire.me) | [Repo](https://github.com/r0hitgit/NexHire)

</td>
<td width="33%" valign="top">

### GenericMeds-AI
**Generic medicine and PMBJP price comparison**

Indexes 1,800+ Jan Aushadhi formulations and 10,000+ kendras, with a bilingual (English and Hindi) AI assistant and a geospatial Kendra Locator.

`React` `FastAPI` `Gemini API` `SQLite` `Vercel`

[Live Site](https://genericmeds-ai.vercel.app) | [Repo](https://github.com/r0hitgit/genericmeds-ai)

</td>
<td width="33%" valign="top">

### Developer Portfolio
**Terminal-themed personal site with an admin CMS**

Spring Boot backend and React frontend with a terminal-style UI. Content is managed through a JWT-protected admin panel instead of being hardcoded.

`Spring Boot` `React` `JWT` `Vercel`

[Live Site](https://r0hithiside.vercel.app) | [Repo](https://github.com/r0hitgit/portFolio)

</td>
</tr>
</table>

### NexHire at a glance

<!-- GitHub renders Mermaid diagrams natively inside a fenced block
     tagged "mermaid". "LR" means left-to-right layout. -->

```mermaid
flowchart LR
    A[React + Vite<br/>Netlify] -->|REST + JWT| B[Spring Boot<br/>Docker on Render]
    B --> C[(MySQL<br/>Clever Cloud)]
    B --> D[Brevo<br/>Email API]
    A --> E[Cloudinary<br/>Resume uploads]
```

---

## Tech Stack

<!-- skillicons.dev builds one icon strip from a comma-separated list.
     perline= controls the wrap point. Icon ids must match their catalogue
     (for example "spring", "fastapi", "py"). -->
<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,react,vite,py,fastapi,mysql,sqlite,docker,git,github,html,css,js,postman,vscode,vercel,netlify&perline=9" alt="Tech stack icons"/>
</div>

<br/>

<!-- <details> makes a collapsible section so the README stays short
     but still lists everything for recruiters who want detail. -->
<details>
<summary><b>Full skill breakdown</b></summary>

<br/>

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Database, AI and DevOps**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</details>

---

## Achievements

<!-- Only claims you can back up with a certificate or a ranking.
     Recruiters do click through, so accuracy matters more than hype. -->

- **NCET Plus SDE (Java) Certification**: Grade O (Outstanding), 88.44%, August 2026
- **AI Hackathon at AURIX 2026** (IILM University): Software Track, qualified for Round 2 and ranked 2nd among the Top 15 teams
- **Dataverse Hackathon**: reached the pre-final round at NSUT, Delhi, 2024
- **150+ DSA problems** solved on LeetCode

---

## GitHub Stats

<!-- FIX NOTES
     The old github-readme-stats cards came from the shared public
     instance (github-readme-stats.vercel.app), which is often over its
     GitHub API limit and then returns a broken image. They are removed.

     What replaced them, and why each is more dependable:
     1. shields.io badges: shields caches results, so they rarely break.
     2. streak-stats (demolab): this one was already rendering for you.
     3. ghchart.rshah.org: a plain SVG of your contribution graph, with
        the hex colour in the URL path set to your purple. -->
<div align="center">

![Last Commit](https://img.shields.io/github/last-commit/r0hitgit/NexHire?label=LAST%20COMMIT&color=8B5CF6&style=for-the-badge&logo=github)
![Followers](https://img.shields.io/github/followers/r0hitgit?label=FOLLOWERS&color=EC4899&style=for-the-badge&logo=github)
![Commits NexHire](https://img.shields.io/github/commit-activity/t/r0hitgit/NexHire?label=NEXHIRE%20COMMITS&color=A78BFA&style=for-the-badge&logo=git&logoColor=white)

</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=r0hitgit&theme=radical&hide_border=true" alt="GitHub streak"/>
</div>

<br/>

<div align="center">
  <img src="https://ghchart.rshah.org/8B5CF6/r0hitgit" alt="Contribution graph" width="90%"/>
</div>

---

## Let's Connect

<div align="center">

I'm actively looking for **SDE internships**. If you are hiring, or just want to talk about Java, Spring Boot or building things, reach out.

<a href="https://r0hithiside.vercel.app"><img src="https://img.shields.io/badge/Visit_Portfolio-8B5CF6?style=for-the-badge" alt="Visit Portfolio"/></a>
<a href="https://www.linkedin.com/in/r0hitin"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-EC4899?style=for-the-badge" alt="LinkedIn"/></a>

</div>

<!-- Footer wave: same capsule-render service with section=footer and
     reversed=true so the gradient mirrors the header. -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:A78BFA,100:EC4899&height=120&section=footer&reversed=true" width="100%" alt="Footer"/>
</div>
