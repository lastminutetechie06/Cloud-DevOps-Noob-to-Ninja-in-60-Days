# ☁️🚀 60-Day Cloud Computing + DevOps Series Roadmap

Welcome to my **60-day** learning journey from fundamentals → real-world cloud-native DevOps on Azure.

**What you’ll learn (stack):**

- 🖥️ Linux fundamentals (Basic to Advance)
- 🌐 Networking fundamentals (DNS, HTTPS/TLS, LB, NAT, VPN)
- 🔷 Azure basics → advanced (incl. AKS)
- 🌱 Git + GitHub (PR workflow, collaboration)
- 🐳 Docker (images, Dockerfiles, networking, volumes)
- ☸️ Kubernetes + 🔴 OpenShift
- 🔁 CI/CD with 🧰 Jenkins + ⚙️ GitHub Actions
- 🔄 GitOps with 🧭 Argo CD
- 📈 Monitoring with 🟠 Prometheus + 📊 Grafana
- 🧱 IaC with 🌍 Terraform
- 🔐 Security with 🛡️ RHACS + 🧿 Prisma Cloud

---

## 🎯 How to use this repo

- 📅 One folder per day: `day-01/` … `day-60/`
- ✍️ Each day includes (recommended):
  - `notes.md` → concepts + diagrams + commands
  - `lab.md` → hands-on steps
  - `links.md` → references used in the video
  - `src/` → optional code/manifests/pipelines for that day

```text
.
├── day-01/
│   ├── notes.md
│   ├── lab.md
│   ├── links.md
│   └── src/
├── day-02/
...
└── capstone/
    ├── app/
    ├── infra-terraform/
    ├── k8s-manifests/
    ├── openshift/
    └── argocd/
```

✅ Daily format (simple & repeatable):

- 🧠 Concept (10–15 min)
- 🧪 Demo (15–20 min+)
- 🏁 Assignment (5–10 min)

---

## 🧰 Prerequisites

- 💻 Laptop/Desktop
- 🧑‍💻 Never Giving-up Attitude and Zeal to learn Something New

---

## 🗺️ Roadmap (Day 1 → Day 60)

> Tip: Use the collapsed sections below to keep the README clean.

<details>
<summary><strong>Week 1 (Days 1–7) — Foundation 🧱</strong></summary>

| Day | Topic                                                                                |
| --: | ------------------------------------------------------------------------------------ |
|   1 | What is Cloud History? Let's understanding how cloud came into existence             |
|   2 | Cloud service models: IaaS vs PaaS vs SaaS (with examples)                           |
|   3 | Cloud deployment models: Public vs Private vs Hybrid vs Multi-cloud                  |
|   4 | What is DevOps? Culture, principles, and outcomes                                    |
|   5 | DevOps lifecycle: CI, CD, automation, feedback loops (high level)                    |
|   6 | Linux basics for DevOps (Part 1): essential commands + navigation                    |
|   7 | Linux basics for DevOps (Part 2): permissions + processes + intro to shell scripting |

</details>

<details>
<summary><strong>Week 2 (Days 8–14) — Networking 🌐</strong></summary>

| Day | Topic                                                               |
| --: | ------------------------------------------------------------------- |
|   8 | Networking for DevOps: OSI vs TCP/IP, ports, common protocols       |
|   9 | IP addressing: IPv4, CIDR, subnetting practice                      |
|  10 | DNS deep dive: records, resolution flow, troubleshooting tools      |
|  11 | HTTP/HTTPS: TLS basics, certificates, reverse proxies               |
|  12 | Routing, NAT, VPN concepts (why private networks work)              |
|  13 | Load balancers: L4 vs L7, health checks, sticky sessions            |
|  14 | Hands-on networking lab: traceroute, nslookup/dig, curl, netstat/ss |

</details>

<details>
<summary><strong>Week 3 (Days 15–21) — Azure Basics + Terraform Start 🔷🧱</strong></summary>

| Day | Topic                                                             |
| --: | ----------------------------------------------------------------- |
|  15 | Azure basics: subscriptions, tenants, resource groups, regions    |
|  16 | Azure identity intro: users, groups, RBAC basics (conceptual)     |
|  17 | Azure networking basics: VNet, subnets, NSG, public vs private IP |
|  18 | Azure compute basics: VM concepts, images, extensions             |
|  19 | Azure storage basics: Storage account, Blob, File, access tiers   |
|  20 | Terraform intro: IaC mindset, workflow (init/plan/apply/destroy)  |
|  21 | Terraform core: providers, resources, variables, outputs          |

</details>

<details>
<summary><strong>Week 4 (Days 22–28) — Terraform Core + Git/GitHub 🌍🌱</strong></summary>

| Day | Topic                                                           |
| --: | --------------------------------------------------------------- |
|  22 | Terraform state: state file, drift, remote backend concept      |
|  23 | Terraform modules: module structure, reusability, environments  |
|  24 | Git fundamentals: repo, commits, staging, .gitignore            |
|  25 | Branching strategies: feature branches, trunk-based basics      |
|  26 | Merge vs rebase, resolving conflicts (real examples)            |
|  27 | GitHub essentials: PRs, code review, Issues, branching rules    |
|  28 | GitHub workflows: tags/releases, CODEOWNERS, basic repo hygiene |

</details>

<details>
<summary><strong>Week 5 (Days 29–35) — Docker + Kubernetes Entry 🐳☸️</strong></summary>

| Day | Topic                                                                 |
| --: | --------------------------------------------------------------------- |
|  29 | Docker basics: images vs containers, layers, registries               |
|  30 | Dockerfile essentials: best practices, multi-stage builds             |
|  31 | Docker networking: bridge/host, port mapping, DNS in Docker           |
|  32 | Docker volumes: persistence patterns (dev vs prod)                    |
|  33 | Kubernetes intro: why K8s, cluster architecture (control plane/nodes) |
|  34 | kubectl + YAML: Pods, Deployments, Services (first manifests)         |
|  35 | Core objects: Deployments rollouts/rollbacks + ReplicaSets            |

</details>

<details>
<summary><strong>Week 6 (Days 36–42) — Kubernetes Core + Packaging ☸️📦</strong></summary>

| Day | Topic                                                            |
| --: | ---------------------------------------------------------------- |
|  36 | Services deep dive: ClusterIP/NodePort/LoadBalancer, discovery   |
|  37 | Config management: ConfigMaps vs Secrets (practical patterns)    |
|  38 | Health & scaling: liveness/readiness, requests/limits, HPA intro |
|  39 | Storage basics: PV/PVC, StorageClass, StatefulSets intro         |
|  40 | Ingress basics: ingress controller concept, host/path routing    |
|  41 | Helm fundamentals: charts, values, templating mental model       |
|  42 | Kustomize fundamentals: overlays, patching, env-based configs    |

</details>

<details>
<summary><strong>Week 7 (Days 43–49) — Security Basics + OpenShift + Jenkins 🔐🔴🧰</strong></summary>

| Day | Topic                                                               |
| --: | ------------------------------------------------------------------- |
|  43 | Kubernetes access control: RBAC, ServiceAccounts, least privilege   |
|  44 | Kubernetes network security: NetworkPolicy concepts + patterns      |
|  45 | OpenShift intro: what OpenShift adds over Kubernetes, oc CLI basics |
|  46 | OpenShift core usage: Projects, Routes, image streams (conceptual)  |
|  47 | OpenShift security: SCC basics and “why it blocks containers”       |
|  48 | OpenShift operators: OLM basics, installing platform capabilities   |
|  49 | Jenkins setup: architecture, agents, credentials, plugins basics    |

</details>

<details>
<summary><strong>Week 8 (Days 50–56) — CI/CD + GitOps + Monitoring 🔁🔄📈</strong></summary>

| Day | Topic                                                                  |
| --: | ---------------------------------------------------------------------- |
|  50 | Jenkins Pipeline: Jenkinsfile, stages, artifacts, parameters           |
|  51 | CI/CD pattern: build → test → image build → push → deploy to K8s       |
|  52 | GitHub Actions basics: workflows, runners, secrets, environments       |
|  53 | GitHub Actions CI: build/test + docker build/push pipeline             |
|  54 | Argo CD intro: GitOps model, apps, sync, drift, repo structure         |
|  55 | Argo CD advanced: multi-env, RBAC concepts, rollbacks, app-of-apps     |
|  56 | Monitoring: Prometheus concepts + Grafana dashboards + alerting basics |

</details>

<details>
<summary><strong>Week 9 (Days 57–60) — Azure Advanced + Cloud Security + Capstone 🔷🛡️🏁</strong></summary>

| Day | Topic                                                                |
| --: | -------------------------------------------------------------------- |
|  57 | Azure advanced: AKS overview + cluster design checklist              |
|  58 | Azure advanced: AKS networking (CNI choices) + ingress strategy      |
|  59 | Security: RHACS (policies across build/deploy/runtime + enforcement) |
|  60 | Security + Capstone: Prisma Cloud posture + end-to-end demo flow     |

</details>

---

## 🏁 Capstone goal (by Day 60)

Build one end-to-end project that shows a real production-style flow:

- 🐳 Containerize an app with Docker
- ☸️ Deploy to Kubernetes and/or 🔴 OpenShift
- 🔁 CI with Jenkins and/or GitHub Actions (build + test + push image)
- 🔄 CD with Argo CD (GitOps from a deployment repo)
- 📈 Observability with Prometheus + Grafana (dashboards + alerts)
- 🔐 Security checks with RHACS + Prisma Cloud (policy + posture mindset)
- 🔷 Azure Advanced: run on AKS and explain the networking/ingress decisions

---

## ⭐ Support

If this roadmap helps you:

- ⭐ Star the repo
- 🍴 Fork it and make your own version
- 👍🏻 Subscribe to my Youtube Channel

---

## 📜 License

MIT License

Copyright (c) 2026 LMT

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
