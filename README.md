<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b27,100:326CE5&height=200&section=header&text=José%20Moura&fontSize=52&fontColor=c0caf5&fontAlignY=38&desc=DevOps%20Engineer%20%E2%80%A2%20Platform%20%E2%80%A2%20Backend&descAlignY=58&descSize=18&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://github.com/mouradev1">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=640&lines=kubectl+apply+-f+reliability.yaml;Infra+as+Code+%E2%80%A2+GitOps+%E2%80%A2+Observability;From+commit+to+production%2C+fully+automated;PHP+%2F+Laravel+%2B+Go+on+top+of+Kubernetes" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/josemouradev"><img src="https://img.shields.io/badge/LinkedIn-josemouradev-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-S%C3%A3o%20Lu%C3%ADs%2C%20BR%20(Remote)-1a1b27?style=flat-square&logo=googlemaps&logoColor=7aa2f7" />
  <img src="https://img.shields.io/badge/Experience-8%2B%20years-1a1b27?style=flat-square&logo=clockify&logoColor=9ece6a" />
  <img src="https://img.shields.io/badge/Microsoft%20Certified-AZ--900-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://komarev.com/ghpvc/?username=mouradev1&color=326CE5&style=flat-square&label=profile+views" />
</p>

---

## `$ whoami`

```yaml
apiVersion: engineer/v1
kind: DevOpsEngineer
metadata:
  name: jose-moura
  location: São Luís, MA, Brazil 🇧🇷   # working remote
  labels:
    role: devops-platform-engineer
    hybrid: backend-developer          # I ship the code AND the platform it runs on
spec:
  experience: "8+ years"
  certifications:
    - AZ-900 Microsoft Azure Fundamentals ✅
  focus:
    - Kubernetes platforms (multi-env, multi-tenant)
    - CI/CD & GitOps pipelines (GitLab CI, GitHub Actions, ArgoCD)
    - Infrastructure as Code (Terraform)
    - Observability (metrics, logs, alerts that actually matter)
    - Secrets & certificate management (Infisical, cert-manager, TLS)
    - Event-driven scaling (KEDA, ScaledJobs, batch workloads)
  backend:
    languages: [PHP 8+, Go, TypeScript, C#]
    frameworks: [Laravel, Node.js, .NET]
  mindset:
    - "If you do it twice, automate it."
    - "No dashboard, no production."
    - "Cost is a feature."
status:
  currentlyLearning: [Platform Engineering, Internal Developer Platforms, eBPF]
  openTo: [DevOps, Platform/SRE, Senior Backend (PHP/Go) roles]
```

---

## 🏗️ How I build things

```mermaid
flowchart LR
    DEV([👨‍💻 git push]) --> CI[CI Pipeline<br/>lint • test • SAST • build]
    CI --> REG[(Container<br/>Registry)]
    CI --> GITOPS[GitOps Repo<br/>Helm values]
    GITOPS --> ARGO{{ArgoCD}}
    ARGO --> K8S[☸️ Kubernetes<br/>homolog → production]
    SEC[🔐 Infisical<br/>secrets + TLS] --> K8S
    TF[Terraform] --> CLOUD[☁️ AWS • Azure • DigitalOcean]
    CLOUD --> K8S
    K8S --> OBS[📊 Prometheus • Grafana<br/>Datadog • Elastic]
    OBS --> ALERT[🚨 Alerts<br/>Telegram • Teams]
```

---

## ⚡ Tech Stack

<table>
  <tr>
    <td align="center" width="140"><b>☁️ Cloud & IaC</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,azure,linux,bash&theme=dark" /> &nbsp;
      <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white" height="28" />
      <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" height="28" /></td>
  </tr>
  <tr>
    <td align="center"><b>☸️ Containers</b></td>
    <td><img src="https://skillicons.dev/icons?i=kubernetes,docker,nginx&theme=dark" /> &nbsp;
      <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" height="28" />
      <img src="https://img.shields.io/badge/KEDA-326CE5?style=flat-square&logo=kubernetes&logoColor=white" height="28" /></td>
  </tr>
  <tr>
    <td align="center"><b>🔄 CI/CD & GitOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=gitlab,githubactions,jenkins,git&theme=dark" /> &nbsp;
      <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" height="28" /></td>
  </tr>
  <tr>
    <td align="center"><b>📊 Observability</b></td>
    <td><img src="https://skillicons.dev/icons?i=grafana,prometheus,elasticsearch&theme=dark" /> &nbsp;
      <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" height="28" /></td>
  </tr>
  <tr>
    <td align="center"><b>🔐 Security</b></td>
    <td><img src="https://img.shields.io/badge/Infisical-000000?style=flat-square&logo=infisical&logoColor=white" height="28" />
      <img src="https://img.shields.io/badge/cert--manager-326CE5?style=flat-square&logo=letsencrypt&logoColor=white" height="28" />
      <img src="https://img.shields.io/badge/DevSecOps-SAST%20%7C%20Image%20Scan-1a1b27?style=flat-square&logo=snyk&logoColor=white" height="28" /></td>
  </tr>
  <tr>
    <td align="center"><b>💻 Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=php,laravel,go,ts,nodejs,dotnet&theme=dark" /></td>
  </tr>
  <tr>
    <td align="center"><b>🗄️ Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,redis,mongodb&theme=dark" /></td>
  </tr>
</table>

---

## 🚀 Featured Projects

| Project | Stack | What it does |
|---|---|---|
| ☸️ **KubeMonitor** | `Go` `Kubernetes` | Watches Kubernetes clusters and fires alerts to **Telegram** and **Microsoft Teams** — pod crashes, restarts and unhealthy workloads before users notice. |
| 📮 **Consulta de CEPs** | `Go` `Node.js` `Redis` `MongoDB` `Nginx` | Dual-implementation microservice (Go vs Node) with Redis caching, MongoDB persistence and Nginx load balancing. |
| 🔗 **[LinkBambu](https://linkbambu.com)** | `Laravel` `Docker` `CI/CD` | Bio-link platform in production with access metrics and customization — built and operated end to end. |
| 💰 **DinDin Planejado** | `Laravel 12` `TailwindCSS` | Personal finance goals platform with charts and objective planning. |

---

## 🧠 What I actually do in production

- **Kubernetes operations** — multi-environment clusters (homolog / production), Ingress + TLS, node labeling & scheduling, KEDA `ScaledJob`s for batch and report workloads.
- **Secrets done right** — Infisical Operator syncing secrets and TLS certificates straight into Kubernetes, no plaintext in repos.
- **Pipelines** — GitLab CI / GitHub Actions / Jenkins with build, tests, security scan and GitOps promotion via ArgoCD.
- **Automation & tooling** — scripts that crawl hundreds of GitLab repos to audit dependencies (e.g. Maven `pom-parent` versions) and feed upgrade plans.
- **Backend** — PHP 8+/Laravel APIs, microservices, queues and messaging; Go services and CLIs for infra.
- **FinOps** — rightsizing, autoscaling and cleaning up what nobody was using.

---

## 🎓 Certifications & Education

<p>
  <img src="https://img.shields.io/badge/AZ--900-Azure%20Fundamentals-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker%20%26%20Kubernetes-Certified-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/GitOps%20Fundamentals-ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
</p>

🎓 **Systems Analysis & Development** — Uniasselvi *(in progress)*

---

## 📈 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=mouradev1&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mouradev1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mouradev1&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=mouradev1&theme=tokyo-night&hide_border=true&area=true" />
</p>

---

## 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/josemouradev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/mouradev1"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://linkbambu.com"><img src="https://img.shields.io/badge/LinkBambu-2E7D32?style=for-the-badge&logo=linktree&logoColor=white" /></a>
</p>

```bash
$ echo "Engineering reliable systems. Automating complexity. Building what comes next."
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:326CE5,50:1a1b27,100:0d1117&height=110&section=footer" />
</p>
