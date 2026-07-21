<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,50:111827,100:0ea5e9&text=Jesús%20Adolfo%20Márquez%20Trejo&fontColor=ffffff&fontSize=38&fontAlignY=38&desc=Full%20Stack%20Engineer%20with%20a%20Frontend%20Soul&descAlignY=58&animation=fadeIn"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=800&color=38BDF8&center=true&vCenter=true&width=900&lines=I+build+digital+products+that+solve+real+problems;React+on+the+front%2C+Node.js+on+the+back;Government+platforms%2C+automation+and+clean+architecture;Always+learning.+Always+shipping." alt="Typing SVG" />

<br/>

<a href="https://github.com/Jesusmarq">
  <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/jamt17/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:jesus.marquez170701@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

## About me

```ts
const jesus = {
  role: "Full Stack Software Engineer",
  location: "Pachuca, Hidalgo, México",
  frontendSoul: true,
  experience: "3+ years",
  currentFocus: [
    "Enterprise applications",
    "Digital government",
    "Clean architecture",
    "AI-powered products"
  ],
  favoriteStack: ["React", "Node.js", "PostgreSQL"],
  mindset: "Build useful things. Make them look good. Leave the code better."
};
```

I design and build complete web platforms, from the database and APIs to the final user experience.

My sweet spot is **frontend engineering**, but I also work across backend, databases, integrations, infrastructure and deployment. Most of my experience comes from building institutional systems that automate real processes, generate documents, integrate external services and support day-to-day operations.

---

## My stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=react,vite,js,ts,html,css,bootstrap,tailwind,figma&perline=9" alt="Frontend technologies" />

### Backend & Data

<img src="https://skillicons.dev/icons?i=nodejs,express,python,django,symfony,postgres,mongodb&perline=7" alt="Backend and database technologies" />

<br/>

<img src="https://img.shields.io/badge/Flask-111827?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />

### Tools & Cloud

<img src="https://skillicons.dev/icons?i=git,github,postman,vscode,linux,aws,docker,nginx&perline=8" alt="Tools and cloud technologies" />

</div>

---

## What I build

<table>
<tr>
<td width="50%" valign="top">

### Oficina Virtual

Institutional platform used to manage more than **50 government services**.

**Highlights**

- Dynamic workflows and forms
- Electronic signature integration
- Automated PDF and Excel generation
- Audit logs and request tracking
- INEGI, payroll and institutional API integrations
- React, Node.js, Express, PostgreSQL and Sequelize

</td>
<td width="50%" valign="top">

### Social Service Platform

End-to-end platform for students completing social service, internships and professional stays.

**Highlights**

- Multi-level approval flows
- Electronic signatures
- QR document validation
- Automated acceptance and completion letters
- Student records and accumulated hours
- React, Flask, Python and PostgreSQL

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Fusion Studio

Platform for managing indoor cycling classes, reservations, memberships and trainers.

**Highlights**

- Reservations and schedules
- Membership management
- Multi-site vision
- Operational dashboards
- Responsive interfaces

</td>
<td width="50%" valign="top">

### Other systems

I've also contributed to platforms for:

- Medical appointments
- Vehicle verification centers
- Institutional requisitions
- Inventory and asset control
- Internal administrative processes

</td>
</tr>
</table>

---

## Engineering mindset

<div align="center">

> **Good software should solve the problem, survive new requirements and remain understandable for the next developer.**

</div>

```bash
$ philosophy

✓ User experience matters
✓ Clean architecture matters
✓ Documentation matters
✓ Shipping matters
✓ Learning never stops
```

---

## Currently exploring

```text
AI applications        ███░░░░░░░░░░░░ 20%
LLMs & RAG             ██░░░░░░░░░░░░░ 15%
Docker                 ██░░░░░░░░░░░░░ 15%
Cloud architecture     ████░░░░░░░░░░░ 25%
Backend design         █████████░░░░░░ 60%
English / TOEFL        █████░░░░░░░░░░ 35%
```

---

## GitHub analytics

<div align="center">

<img
  height="165"
  src="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/main/profile-summary-card-output/github_dark/3-stats.svg"
  alt="GitHub statistics"
/>

<img
  height="165"
  src="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/main/profile-summary-card-output/github_dark/1-repos-per-language.svg"
  alt="Top languages by repository"
/>

<br/>

<img
  width="100%"
  src="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/main/profile-summary-card-output/github_dark/0-profile-details.svg"
  alt="GitHub profile details"
/>

</div>

---

## Contribution snake

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/gh-pages/github-contribution-grid-snake-dark.svg"
  >
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/gh-pages/github-contribution-grid-snake.svg"
  >
  <img
    src="https://raw.githubusercontent.com/Jesusmarq/Jesusmarq/gh-pages/github-contribution-grid-snake.svg"
    alt="Contribution snake animation"
  >
</picture>

</div>

<details>
<summary><strong>Snake animation workflow</strong></summary>

Create this file:

```text
.github/workflows/snake.yml
```

```yml
name: Generate contribution snake

on:
  schedule:
    - cron: "0 */24 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Publish snake to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
          branch: output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

<div align="center">

### Let's build something useful.

<img src="https://komarev.com/ghpvc/?username=Jesusmarq&label=Profile%20views&color=0ea5e9&style=flat-square" alt="Profile views" />

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0ea5e9,50:111827,100:0f172a"/>

</div>
