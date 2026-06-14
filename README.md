<!-- ==================== ANIMATED HEADER ==================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Kushagra%20Srivastava&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Backend%20Engineer%20%7C%20Gen%20AI%20%7C%20Agentic%20AI&descAlignY=55&descSize=18" />

</div>

<!-- ==================== TYPING ANIMATION ==================== -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&multiline=false&width=700&lines=🚀+Backend+Engineer+%7C+Problem+Solver;🤖+Gen+AI+%26+Agentic+AI+Builder;⚡+LLMs+%7C+AI+Agents+%7C+Multi-step+Pipelines;🔧+Turning+Ideas+into+Scalable+Systems;🧠+Building+Autonomous+AI+Workflows;💡+The+Backend+Nobody+Sees%2C+Everyone+Feels)](https://git.io/typing-svg)

</div>

---

<!-- ==================== ABOUT ME ==================== -->
## 💫 About Me

🚀 **Backend Engineer | Gen AI & Agentic AI Enthusiast**

I build the systems that power real-world products — robust APIs, scalable architectures, and intelligent backends that don't just work, they **perform under pressure**.

💡 **What I do:**
```
→ Design & develop production-grade backend systems
→ Solve complex, real-world engineering challenges
→ Build & deploy Generative AI solutions into live products
→ Create Agentic AI workflows — autonomous systems that think, decide & act
→ Bridge the gap between raw ML models and real-world applications
```

🤖 Currently deep in the world of **LLMs**, **AI agents**, and **multi-step reasoning pipelines**. I'm not just following the AI wave — I'm building on top of it.

⚡ I believe great backend engineering is **invisible** — it's the foundation users never see but always feel.

🔧 Always open to collaborating on backend systems, AI integrations, and anything that solves a meaningful problem.

---

<!-- ==================== SOCIALS ==================== -->
## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kushagra-srivastava-114132373/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kushagrasrivastava025@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kushagra901)

</div>

---

<!-- ==================== GITHUB STATS ==================== -->
## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.shion.dev/api?username=Kushagra901&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github" />
<img width="49%" src="https://streak-stats.demolab.com/?user=Kushagra901&theme=tokyonight&hide_border=true" />

<img width="40%" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Kushagra901&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />

</div>

---

<!-- ==================== CONTRIBUTION SNAKE ==================== -->
## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kushagra901/Kushagra901/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kushagra901/Kushagra901/output/github-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/Kushagra901/Kushagra901/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

> ⚙️ **Setup the Snake:** Add this GitHub Action to `.github/workflows/snake.yml` in your profile repo to auto-generate the snake animation ↓

<details>
<summary>📋 Click to copy snake.yml workflow</summary>

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

<!-- ==================== PAC-MAN ==================== -->
## 👾 Pac-Man Munching Through My Contributions

<div align="center">

[![pacman contribution graph](https://raw.githubusercontent.com/Kushagra901/Kushagra901/output/github-contribution-grid-pacman-dark.svg)](https://github.com/Kushagra901)

</div>

> ⚙️ **Setup Pac-Man:** Add this to your snake.yml workflow outputs section:

<details>
<summary>📋 Click to copy Pac-Man output config</summary>

```yaml
outputs: |
  dist/github-snake.svg
  dist/github-snake-dark.svg?palette=github-dark
  dist/github-contribution-grid-pacman.svg?renderer=pacman
  dist/github-contribution-grid-pacman-dark.svg?renderer=pacman&palette=github-dark
```

</details>

---

<!-- ==================== BACKEND ANIMATION ==================== -->
## ⚡ What Happens Behind Every API Call

<div align="center">

```
  CLIENT REQUEST
       │
       ▼
  ┌─────────────┐     Rate Limit     ┌─────────────┐
  │   API GW    │ ◄────────────────► │    Redis    │
  │  (FastAPI)  │                    │   Cache ⚡  │
  └──────┬──────┘                    └─────────────┘
         │
    Auth / JWT
         │
         ▼
  ┌─────────────┐    Task Queue      ┌─────────────┐
  │  Business   │ ──────────────────►│    Kafka    │
  │   Logic     │                    │  Broker 📨  │
  └──────┬──────┘                    └──────┬──────┘
         │                                  │
    DB Query                         Worker Consume
         │                                  │
         ▼                                  ▼
  ┌─────────────┐                    ┌─────────────┐
  │  PostgreSQL │                    │  AI Agent   │
  │  MongoDB    │                    │  Pipeline   │
  │  Neo4j  🗄️  │                    │    🤖       │
  └─────────────┘                    └─────────────┘
```

</div>

---

<!-- ==================== AI PIPELINE ANIMATION ==================== -->
## 🧠 My Agentic AI Pipeline Architecture

<div align="center">

```
  USER QUERY
      │
      ▼
  ┌──────────────────────────────────────────┐
  │           🤖  ORCHESTRATOR AGENT         │
  │         (Plans · Decides · Delegates)    │
  └────┬─────────────┬──────────────┬────────┘
       │             │              │
       ▼             ▼              ▼
  ┌─────────┐  ┌──────────┐  ┌──────────────┐
  │ 🔍 RAG  │  │ 🛠️ Tool  │  │ 💾 Memory    │
  │ Agent   │  │  Agent   │  │   Agent      │
  │(Retrieve│  │(Execute  │  │(Short+Long   │
  │& Embed) │  │ Actions) │  │  term)       │
  └────┬────┘  └────┬─────┘  └──────┬───────┘
       │             │               │
       └─────────────┴───────────────┘
                     │
                     ▼
  ┌──────────────────────────────────────────┐
  │       📊  LLM REASONING LAYER            │
  │  (GPT-4 / Claude / Gemini / Local LLM)  │
  └──────────────────────────────────────────┘
                     │
                     ▼
               FINAL RESPONSE ✅
```

</div>

---

<!-- ==================== TECH STACK ORGANIZED ==================== -->
## 💻 Tech Arsenal

### 🗣️ Languages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---

### ⚙️ Backend Frameworks
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)

---

### 🎨 Frontend Frameworks
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![EJS](https://img.shields.io/badge/ejs-%23B4CA65.svg?style=for-the-badge&logo=ejs&logoColor=black)
![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)

---

### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Snowflake](https://img.shields.io/badge/snowflake-%2329B5E8.svg?style=for-the-badge&logo=snowflake&logoColor=white)
![CrateDB](https://img.shields.io/badge/CrateDB-009DC7?style=for-the-badge&logo=CrateDB&logoColor=white)

---

### 🤖 AI / ML / Data Science
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)

---

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Fastlane](https://img.shields.io/badge/fastlane-%2382bd4e.svg?style=for-the-badge&logo=fastlane&logoColor=black)

---

### 🛠️ Tools & Others
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)
![Meta](https://img.shields.io/badge/Meta-%230467DF.svg?style=for-the-badge&logo=Meta&logoColor=white)
![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)

---

### 🎨 Design Tools
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)
![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)
![Adobe Creative Cloud](https://img.shields.io/badge/Adobe%20Creative%20Cloud-DA1F26.svg?style=for-the-badge&logo=Adobe%20Creative%20Cloud&logoColor=white)
![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)

---

<!-- ==================== TROPHIES ==================== -->
## 🏆 GitHub Trophies

<div align="center">

![](https://github-profile-trophy.vercel.app/?username=Kushagra901&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7)

</div>

---

<!-- ==================== TOP REPOS ==================== -->
## 🔝 Top Contributed Repositories

<div align="center">

![](https://github-contributor-stats.vercel.app/api?username=Kushagra901&limit=5&theme=tokyonight&combine_all_yearly_contributions=true)

</div>

---

<!-- ==================== ACTIVITY GRAPH ==================== -->
## 📈 Contribution Activity

<div align="center">

[![Kushagra's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Kushagra901&theme=tokyo-night&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<!-- ==================== FOOTER ==================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" />

[![](https://komarev.com/ghpvc/?username=Kushagra901&style=for-the-badge&color=blueviolet&label=PROFILE+VIEWS)](https://github.com/Kushagra901)

**⭐ Star my repos if you find them useful | Let's build something amazing together! 🚀**

</div>

<!-- Proudly crafted with ❤️ by Kushagra Srivastava | Enhanced with Claude -->
