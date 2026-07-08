<h1 align="center">Vitalii · Java Backend Developer</h1>

<p align="center">
  I turn messy, real-world business processes into <b>backends, bots, and automations that just work.</b>
</p>

<p align="center">
  🇺🇦 Lviv, Ukraine · came up through tech support, now building the tools I used to wish existed
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white" alt="Kafka"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

---

### What I do

**🏗️ Backend systems** — Java 17 & Spring Boot 3, designed properly: hexagonal architecture, CQRS, event-driven flows with Kafka, PostgreSQL/Redis, Docker.

**🤖 Bots & automation** — Telegram bots and integrations that quietly run real businesses: sales intake, multilingual KYC, pricing, support ticketing.

**🛠️ From support to shipping** — I started in tech support / helpdesk. I've felt the pain of manual work, tickets and SLAs first-hand — so I build software that respects the people who have to operate it.

---

### 🚀 Flagship — SpaceFlow

An **event-driven booking backend** for shared spaces, built to implement the patterns I care about
end-to-end. The whole system comes up with a single `docker compose up`.

- **Transactional Outbox** → booking + event committed in one DB transaction, then relayed to Kafka (at-least-once).
- **CQRS** → writes on PostgreSQL with optimistic locking; reads served from a Redis read model kept in sync by a Kafka consumer.
- Idempotent projections, Flyway migrations, OpenAPI, Prometheus/Grafana, GitHub Actions CI.

<p>
  <a href="https://github.com/firemoraster/spaceflow"><img src="https://img.shields.io/badge/Repo-SpaceFlow-181717?logo=github&logoColor=white" alt="SpaceFlow repo"/></a>
  <img src="https://img.shields.io/github/actions/workflow/status/firemoraster/spaceflow/ci.yml?label=build" alt="build"/>
  <img src="https://img.shields.io/github/last-commit/firemoraster/spaceflow" alt="last commit"/>
  <img src="https://img.shields.io/github/languages/top/firemoraster/spaceflow" alt="top language"/>
</p>

➡️ **[Read the architecture write-up →](https://github.com/firemoraster/spaceflow)**

---

### 🧩 Selected work

**Bots & automation for real companies**
- 🌾 [**Euromet-bot**](https://github.com/firemoraster/Euromet-bot) — Telegram bot for an agribusiness: order intake, sales and price calculation. *(Java)*
- 🔐 [**Kycify**](https://github.com/firemoraster/Kycify) — multilingual KYC bot for crypto exchanges (Bybit, OKX, Binance…): service cart, orders, payments, rules. *(Java)*
- 🎫 **helpdesk-bot-mvp** — Telegram ticketing MVP: collect tickets, manage statuses. *(private · JavaScript)*

**Business tools & reporting**
- 📈 **SAMI-Reports** / **project-sami** — reporting & dashboard tooling. *(private · TypeScript / Vue)*
- 🌸 [**peony-catalog**](https://github.com/firemoraster/peony-catalog) — e-commerce catalog with an admin panel and drag-and-drop gallery. *(JavaScript)*

**Craft & fundamentals**
- ☕ [**JavaCorePractice**](https://github.com/firemoraster/JavaCorePractice) · [**LeetCode-practice**](https://github.com/firemoraster/LeetCode-practice) — keeping Java core and algorithms sharp.

---

### 🧭 How I work

- Ship in **small vertical slices**, keep repos readable, commit history clean.
- Prefer **boring, correct** solutions — reach for complexity only when the problem earns it.
- **Design for failure**: idempotency, retries and observability from day one, not bolted on later.
- Having run software in production, I build with the **operator in mind**.

---

### 🧰 Tech I work with

**Languages** · Java · TypeScript · JavaScript · SQL · Python · Bash
**Backend** · Spring Boot (Web, Data JPA, Security, Actuator) · REST · OpenAPI · Node.js
**Messaging & data** · Apache Kafka · PostgreSQL · Redis · MongoDB
**Frontend touch** · Vue · HTML/CSS/JS
**Infra & tooling** · Docker · docker-compose · GitHub Actions · Git · Maven · Linux (Ubuntu VPS)
**Practices** · Hexagonal / Clean Architecture · CQRS · Transactional Outbox · Testcontainers

---

<p align="center">
  <img src="https://img.shields.io/github/followers/firemoraster?label=Followers&style=social" alt="followers"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Focus-Java%20%2F%20Spring%20Backend-6DB33F" alt="focus"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Currently-Event--driven%20%26%20CQRS-blue" alt="currently"/>
</p>

### 📬 Get in touch

<p align="left">
  <a href="mailto:vitalyplemiannyk@gmail.com"><img src="https://img.shields.io/badge/Email-vitalyplemiannyk@gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://t.me/mooneiko"><img src="https://img.shields.io/badge/Telegram-@mooneiko-26A5E4?logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://www.linkedin.com/in/your-profile"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

<sub>💼 Open to Java backend roles — bots, automations and real-world backends are my comfort zone. Let's talk.</sub>
