
Cloud
Claude finished the response

Message collapsed
What visual style do you want for the refreshed profile README?
Clean & professional
Which extra sections should I add beyond the tech stack and links?
Featured projects, Currently working on / learning, Keep GitHub stats cards

Updated tasks, ran 3 commands, searched the web
Updated tasks, ran 3 commands, searched the web
Rewritten as a clean profile README. Key changes from your current one:

Cut the dead image — i.imgur.com/yourimage.png was a placeholder that renders broken.
Fixed stale badge slugs — logo=aws no longer resolves in simple-icons (it's amazonwebservices), same for nodedotjs, vuedotjs, gnubash, githubactions.
Stack reflects what you actually run now — React 19, TypeScript, Firebase/Firestore, Cloud Run, Terraform, Bitbucket Pipelines, n8n promoted to first-class; Vue kept but demoted.
Replaced the emoji category headers with bold labels + badge rows, and swapped for-the-badge for flat-square so the social links don't dominate the page.
Added a "What I'm working on" block, a Featured Projects table, and a profile-view counter.
Stats cards kept with include_all_commits=true&count_private=true added, which matters if most of your work is in private/Bitbucket repos.
Two things need your hand:

The Featured Projects table has three placeholder rows — GitHub's API is repo-scoped in this sandbox and robots.txt blocked the profile page, so I couldn't read your actual repos. Paste the repo list and I'll fill it in.
https://fi-di.xyz/ and the stats hosts couldn't be reached from here (egress allowlist), so confirm your portfolio domain is still live before pushing.
Worth knowing: streak-stats.demolab.com is community-hosted and rate-limits hard on popular profiles — if it starts showing a broken image, self-hosting the streak-stats instance on your own Cloud Run project is a 10-minute job and would fit your setup well.


Readme
Document · MD 




Claude is AI and can make mistakes. Please double-check responses.


Readme · MD
<h1 align="center">Mamun Rahman</h1>
 
<p align="center">
  <b>Cloud Engineer &amp; DevOps Specialist</b> · Louhi Networks Oy · Finland
</p>
<p align="center">
  I build and run production workloads on Google Cloud — multi-tenant SaaS on Cloud Run,
  Firebase backends, and the CI/CD and observability that keeps them healthy.
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/rahmanmamun/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://fi-di.xyz/"><img alt="Website" src="https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="mailto:mamun.rahman@louhi.fi"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=rahman-mamun&style=flat-square&color=0A66C2">
</p>
---
 
## What I'm working on
 
- **Multi-tenant SaaS on GCP** — React 19 + TypeScript frontends, Firebase Auth/Firestore backends, App Check and role-based access control, deployed to Cloud Run via Bitbucket Pipelines.
- **Infrastructure as code** — Terraform-managed GCP projects, reproducible dev/prod environments, secrets kept out of images.
- **Automation** — n8n workflows and Cloud Functions wiring together internal tooling and third-party APIs (Google Workspace, Visma Sign, Pipedrive).
- **Observability** — Cloud Monitoring, Prometheus and Grafana dashboards, SLO-driven alerting.
Currently going deeper on Kubernetes operators, GCP security posture management, and cost optimisation at scale.
 
---
 
## Tech stack
 
**Cloud & Infrastructure**
 
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![UpCloud](https://img.shields.io/badge/UpCloud-7B00FF?style=flat-square&logo=upcloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud%20Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
 
**Containers & Orchestration**
 
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
 
**Languages**
 
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
 
**Frontend**
 
![React](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
 
**Data & Backend Services**
 
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
 
**CI/CD & Automation**
 
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Bitbucket Pipelines](https://img.shields.io/badge/Bitbucket%20Pipelines-0052CC?style=flat-square&logo=bitbucket&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
 
**Monitoring & Observability**
 
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Cloud Monitoring](https://img.shields.io/badge/Cloud%20Monitoring-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Site24x7](https://img.shields.io/badge/Site24x7-00A1E0?style=flat-square&logo=site24x7&logoColor=white)
 
---
 
## Featured projects
 
<!-- Replace the rows below with your own repos. Delete any you don't want shown. -->
 
| Project | What it does | Stack |
| --- | --- | --- |
| **[project-name](https://github.com/rahman-mamun/project-name)** | One line on the problem it solves. | React 19 · TypeScript · Firebase |
| **[project-name](https://github.com/rahman-mamun/project-name)** | One line on the problem it solves. | Terraform · GCP · Cloud Run |
| **[project-name](https://github.com/rahman-mamun/project-name)** | One line on the problem it solves. | Python · Docker · GitHub Actions |
 
---
 
## GitHub activity
 
<p align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=rahman-mamun&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahman-mamun&layout=compact&theme=tokyonight&hide_border=true&langs_count=8">
</p>
<p align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=rahman-mamun&theme=tokyonight&hide_border=true">
</p>
---
 
<p align="center">
  <sub>Open to conversations about cloud architecture, platform engineering, and DevOps practice.</sub>
</p>
 
