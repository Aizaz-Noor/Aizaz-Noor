<!--
╔══════════════════════════════════════════════════════════════╗
║              SETUP GUIDE — READ BEFORE USING                ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  1. SNAKE ANIMATION (highly recommended)                     ║
║     • Go to your Aizaz-Noor/Aizaz-Noor repo                ║
║     • Create: .github/workflows/snake.yml                   ║
║     • Paste the following YAML exactly:                      ║
║                                                              ║
║     name: Generate Snake                                     ║
║     on:                                                      ║
║       schedule: [{cron: "0 0 * * *"}]                       ║
║       workflow_dispatch:                                     ║
║     jobs:                                                    ║
║       snake:                                                 ║
║         runs-on: ubuntu-latest                               ║
║         steps:                                               ║
║           - uses: Platane/snk@v3                             ║
║             with:                                            ║
║               github_user_name: Aizaz-Noor                  ║
║               outputs: |                                     ║
║                 dist/snake.svg                               ║
║                 dist/snake-dark.svg?palette=github-dark      ║
║           - uses: crazy-max/ghaction-github-pages@v4         ║
║             with:                                            ║
║               target_branch: output                          ║
║               build_dir: dist                                ║
║             env:                                             ║
║               GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}      ║
║                                                              ║
║     • Settings → Actions → General                           ║
║       → Workflow permissions → Read & Write → Save           ║
║     • Then go to Actions tab and run the workflow manually   ║
║                                                              ║
║  2. ACTIVITY GRAPH — works automatically, no setup needed    ║
║                                                              ║
║  3. Replace YOUR_FACEBOOK in social section below            ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0c4a6e,100:0891b2&height=180&section=header&text=Aizaz%20Noor%20Khuwaja&fontSize=52&fontColor=e0f2fe&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20Student%20%7C%20Builder%20%7C%20Problem%20Solver&descAlignY=62&descSize=17&descColor=7dd3fc" alt="Header"/>

</div>

<div align="center">

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=680&lines=🎓+Software+Engineering+%40+COMSATS+University;💡+Building+real+solutions+to+real+problems;🧠+DSA+%7C+OOP+%7C+System+Design+%7C+SaaS;🐧+Linux+first%2C+everything+else+second;🚀+Open+to+internships+%26+entry-level+roles" alt="Typing SVG"/>
</a>

<br/><br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Aizaz-Noor&color=0891b2&style=flat-square&label=Profile+Views)](https://github.com/Aizaz-Noor)&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/Aizaz-Noor?style=flat-square&color=0891b2&labelColor=1e293b&label=Followers)](https://github.com/Aizaz-Noor?tab=followers)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aizaz-noor)

</div>

---

## 👋 About Me

I'm a **Software Engineering student at COMSATS University, Pakistan**, with a genuine passion for building things that work and understanding *why* they work.

My day-to-day revolves around sharpening problem-solving skills through **Data Structures & Algorithms**, exploring the fundamentals of **Digital Logic Design**, and thinking seriously about how to build **scalable SaaS products**. I run Ubuntu as my primary OS because I believe engineers should understand their tools down to the metal.

- **Currently focused on:** DSA mastery, LeetCode, SaaS ideation
- **Building toward:** A software career at a company that ships meaningful products
- **Learning:** Python scripting, Bash automation, Vim workflows
- **Open to:** Internships, entry-level roles, open-source collaboration
- **Reach me:** [aizaznoorkhuwaja@gmail.com](mailto:aizaznoorkhuwaja@gmail.com)

---

##  Tech Stack & Skills

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=java,cpp,c,python&theme=dark&perline=8)](https://skillicons.dev)

**Environment & Tools**

[![Tools](https://skillicons.dev/icons?i=linux,ubuntu,bash,vim,git,github&theme=dark&perline=8)](https://skillicons.dev)

</div>

<br/>

| Category | Technologies | Proficiency |
|----------|-------------|-------------|
| **Primary Languages** | Java, javascript, C++, C | ⭐⭐⭐⭐ strong |
| **Scripting** | Python, Bash | ⭐⭐⭐ Building |
| **CS Fundamentals** | OOP, Data Structures, DLD | ⭐⭐⭐⭐ intermediate |
| **Environment** | Ubuntu Linux, CLI tooling | ⭐⭐⭐⭐⭐ Daily Driver |
| **Version Control** | Git, GitHub | ⭐⭐⭐⭐ Comfortable |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎮 Newton's Glitch
**A physics-based platformer inspired by Flappy Bird**

Built entirely in **Java + JavaFX**, this game features a custom character navigating through objects under real Newtonian gravity mechanics. Focused on OOP design patterns, game loop architecture, and rendering performance.

**What I learned:** Game physics modeling, JavaFX rendering pipeline, clean class hierarchy design

`Java` · `JavaFX` · `OOP` · `Physics Engine`

</td>
<td width="50%" valign="top">

### 🔭 What's Next
**Something SaaS-shaped is forming...**

Currently researching real problems worth solving — where software can automate, simplify, or eliminate unnecessary friction. Exploring ideas at the intersection of developer tooling and business automation.

**Goal:** Ship a product that real people use

`TBD` · `Research Phase` · `Problem-First Thinking`

</td>
</tr>
</table>

> 💡 *More projects in progress check my [repositories →](https://github.com/Aizaz-Noor?tab=repositories)*

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=Aizaz-Noor&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=0891b2&text_color=94a3b8&border_radius=10&include_all_commits=true&count_private=true" height="165" alt="GitHub Stats"/>
&nbsp;
<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Aizaz-Noor&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8&layout=compact&border_radius=10&langs_count=8" height="165" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://readme-stats-fast.vercel.app/api/streak/?username=Aizaz-Noor&theme=tokyonight&hide_border=true&background=0d1117&stroke=0891b2&ring=38bdf8&fire=0891b2&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b&border_radius=10" alt="GitHub Streak"/>

</div>

<br/>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aizaz-Noor&bg_color=0d1117&color=38bdf8&line=0891b2&point=7dd3fc&area=true&area_color=0c4a6e&hide_border=true&radius=8" width="95%" alt="Contribution Graph"/>

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aizaz-Noor/Aizaz-Noor/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aizaz-Noor/Aizaz-Noor/output/snake.svg"/>
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/Aizaz-Noor/Aizaz-Noor/output/snake.svg"/>
</picture>

</div>

---

## Achievements

<div align="center">

<img src="https://github-profile-trophy-kappa.vercel.app/?username=Aizaz-Noor&theme=tokyonight&no-frame=true&column=7&margin-w=8&margin-h=8&no-bg=true" alt="GitHub Trophies"/>

</div>

---

## Competitive Programming

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-aizaz__khuwaja-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=1a1a2e)](https://leetcode.com/u/aizaz_khuwaja)&nbsp;&nbsp;
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-aizaz__khuwaja-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=1a1a2e)](https://www.geeksforgeeks.org/user/aizaz_khuwaja)

</div>

---

## Current Focus & Roadmap

```
2025 Roadmap  ·  The Foundation Phase
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 ✅  Master core DSA — Arrays, Linked Lists, Trees, Graphs
 ✅  OOP patterns and SOLID principles in Java
 🔄  LeetCode — targeting 200+ problems solved
 🔄  Python for scripting and automation
 📌  Build and deploy one complete SaaS project
 📌  First open-source contribution (PR in progress)
 📌  Land a software engineering internship
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## Connect & Collaborate

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aizaz%20Noor-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1a2e)](https://www.linkedin.com/in/aizaz-noor)&nbsp;
[![Email](https://img.shields.io/badge/Email-aizaznoorkhuwaja%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a2e)](mailto:aizaznoorkhuwaja@gmail.com)&nbsp;
[![Instagram](https://img.shields.io/badge/Instagram-aizaz__khuwaja-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=1a1a2e)](https://www.instagram.com/aizaz_khuwaja/)

</div>

---

## 💼 For Recruiters & Hiring Managers

> [!IMPORTANT]
> **I'm actively seeking internships and entry-level software engineering roles.**
>
> I bring strong CS fundamentals, a Linux-native development mindset, and genuine curiosity about how software systems work at scale. I'm a fast learner who takes code quality and documentation seriously.
>
>  **[View / Download My Resume →](./Aizaz_Noor_cv.pdf)**
>
> **What I'm looking for:** Backend · Systems · Fullstack · Internship or Junior Engineer · Remote or Lahore, PK
>
> *I respond to all messages within 24 hours.*

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0891b2,50:0c4a6e,100:0d1117&height=120&section=footer" alt="Footer"/>

**Aizaz Noor Khuwaja** · Software Engineering Student · COMSATS University, Pakistan

*Building skills. Building products. Building a career worth having.*

</div>
