
<div id="header" align="center">
  <img src="https://media.giphy.com/media/836HiJc7pgzy8iNXCn/giphy.gif" width="230" />
</div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/michael-ocasio/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://twitter.com/Michael_Ocasio1">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=MikeOcasio&style=flat-square&color=blue" alt=""/>
</div>

<h1 align="center">
  Hey There! I'm Mike Ocasio! 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"/>
</h1>

<br>

<div style="display:flex; flex-wrap: wrap; justify-content: center; gap: 6px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white">
  <img src="https://img.shields.io/badge/Alembic-6BA539?style=for-the-badge&logo=alembic&logoColor=white">
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white">
  <img src="https://img.shields.io/badge/Rails-D30001?style=for-the-badge&logo=rubyonrails&logoColor=white">
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white">
  <img src="https://img.shields.io/badge/AutoHotkey-334455?style=for-the-badge&logo=autohotkey&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

---

## 🚀 About Me
**10-year Army veteran** turned software developer — I swore I'd never work that hard again, and then I discovered production bugs at 2 AM.

I build in two worlds: **full-stack web apps** (Rails, Next.js, GraphQL) and **data infrastructure** (Python pipelines, automation tooling, cloud plumbing). Most days I'm writing backend Python with **FastAPI, Celery, and SQLAlchemy** on top of AWS (ECS Fargate, S3, RabbitMQ) — designing systems that pull data from third-party APIs, validate and transform it, and feed it into ML/analytics pipelines downstream.

When I'm not in Python land, I'm shipping **Rails + GraphQL** web apps, or building **Windows automation tooling** (AutoHotkey) that drives legacy desktop software the rest of us would rather pretend doesn't exist.

I care a lot about **data integrity, audit trails, and debuggability** — because future-me (or some poor on-call engineer) is going to need to figure out what went sideways at 2 AM, and I'd like that person to have a fighting chance.

---

### 🔧 What I've Been Up To

#### **Loghatch (Personal Project)**
I built **Loghatch** because existing tools didn't do what I actually needed for biological research logging. Whether you're tracking ants, insects, or your neighbor's suspiciously large garden gnome collection — this thing's got you covered. Custom logbooks & templates, timeline view, collaborator invites + comments, and public/private privacy controls. Stack: **Next.js + Prisma + Node.js + PostgreSQL**, with Prisma handling type-safe queries and schema evolution.

---

#### **Data Pipeline Architecture (Professional)**
Designed and built a multi-stage ingest pipeline that pulls data from third-party APIs, validates it against configurable rule sets, transforms it across multiple formats, and lands it in S3 for downstream ML consumption. Includes audit trail snapshots with per-run metadata, force-rerun capability, and automatic deduplication. Copy-on-write worklist versioning for command management. **Python, FastAPI, Celery, PostgreSQL, S3.**

---

#### **Command Validation & Normalization Engine (Professional)**
Built a TDD validation engine that checks domain-specific query commands against 10+ normalization rules before they hit production — catches syntax issues, type mismatches, and semantic errors that would otherwise silently corrupt data. Includes batch update support, RESTful CRUD endpoints, and an inference layer that determines command types from report metadata so operators don't need to know the internals.

---

#### **Desktop Automation Platform (Professional)**
Built a Windows automation system (**AutoHotkey v2**) that drives legacy desktop software through GUI automation, processes large-scale datasets, and uploads results to cloud storage. Handles multi-site batch orchestration, error recovery, Excel COM interop, and auto-elevation for privileged processes. Runs on distributed customer hardware across multiple locations.

---

#### **Infrastructure & DevOps (Professional)**
ECS Fargate deployments with **OpenTofu**, CI/CD with GitHub Actions, Docker multi-stage builds, ALB with OIDC auth, AmazonMQ (RabbitMQ) for task queuing. Immutable Alembic migration strategy with manual deploy controls — because auto-migrating production is a great way to learn new things about yourself.

---

#### **Agent Service (Professional, In Progress)**
Designing a lightweight polling-based agent that runs on remote Windows machines to execute scheduled jobs (data validation, config pulls, historical report generation). Communicates with a central API over authenticated HTTP. **Python, runs as a native Windows service.**

---

### 🛠️ My Current Toolbox
**Primary:** Python, FastAPI, Celery, SQLAlchemy, PostgreSQL, Ruby on Rails, GraphQL, Docker, AWS, OpenTofu/Terraform
**Active:** Polars, Alembic, Next.js, React, Node.js, Prisma, AutoHotkey v2, GitHub Actions

---

### 🌟 Sometimes I Play With
**Go, Dash (Plotly), WebSockets, gRPC, Windows service development** (and whatever else seems interesting at 11 PM)

---

### ⚡ Fun Fact
I spent 10 years in the Army as a Wheeled Vehicle Technician 🚛, which taught me two things: how to troubleshoot anything under pressure, and that systems thinking applies to way more than just engines. These days I've traded rebuilding transmissions for rebuilding data pipelines — and honestly, the transmissions were less temperamental.

---

If you're curious about **Loghatch**, check it out — it's still early, but it's the project I'm most excited about. Otherwise, you'll probably find me deep in a Python pipeline, wrestling with a Rails engine, or explaining to AutoHotkey why clicking the button *should* have worked.

<div id="footer" >
  <img src="https://raw.githubusercontent.com/trinib/trinib/82213791fa9ff58d3ca768ddd6de2489ec23ffca/images/footer.svg"/>
</div>
