<h1 align="center">Hi, I'm Vitalii 👋</h1>
<p align="center">
  <b>Java Backend Developer</b> · Lviv, Ukraine 🇺🇦
</p>

<p align="center">
  I build backend systems in Java &amp; Spring Boot — and I like getting the hard parts right:
  <br/>
  clean architecture, event-driven design, and services that actually hold up under real traffic.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white" alt="Kafka"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker"/>
</p>

---

### 🧭 About me

- 🎯 Backend developer focused on **Java 17 + Spring Boot 3**, working toward a strong Middle level.
- 🏗️ I care about **architecture** — hexagonal / clean layering, CQRS, and event-driven patterns done properly rather than as buzzwords.
- 🤖 I've shipped **real-world Telegram bots** for businesses, so I know what it takes to run something people actually depend on.
- 📚 Always learning in public — I build in small vertical slices and keep my repos readable.

---

### 🚀 Featured project — SpaceFlow

An **event-driven booking backend** for shared spaces (coworking desks, meeting rooms). I built it
to implement the patterns I care about end-to-end, so the whole system runs with a single
`docker compose up`.

- **Transactional Outbox** — a booking and its event are written in one DB transaction, then relayed to Kafka (at-least-once, published only after broker ack).
- **CQRS** — writes go to PostgreSQL with optimistic locking; reads are served from a Redis read model kept up to date by a Kafka consumer.
- **Idempotent projections**, a scheduled outbox relay, Flyway migrations, OpenAPI, Prometheus/Grafana, and a full Docker stack.

<p>
  <a href="https://github.com/firemoraster/spaceflow"><img src="https://img.shields.io/badge/Repo-SpaceFlow-181717?logo=github&logoColor=white" alt="SpaceFlow repo"/></a>
  <img src="https://img.shields.io/github/actions/workflow/status/firemoraster/spaceflow/ci.yml?label=build" alt="build"/>
  <img src="https://img.shields.io/github/last-commit/firemoraster/spaceflow" alt="last commit"/>
  <img src="https://img.shields.io/github/languages/top/firemoraster/spaceflow" alt="top language"/>
</p>

➡️ **[Read the full write-up and architecture diagram →](https://github.com/firemoraster/spaceflow)**

---

### 🛠️ Other things I've built

| Project | What it is | Stack |
|---------|------------|-------|
| [**Euromet-bot**](https://github.com/firemoraster/Euromet-bot) | Telegram bot for an agribusiness company — order intake, sales and pricing automation | Java, TelegramBots API |
| [**Kycify**](https://github.com/firemoraster/Kycify) | Multilingual Telegram bot for crypto-exchange KYC services (cart, orders, payments) | Java |
| [**JavaCorePractice**](https://github.com/firemoraster/JavaCorePractice) · [**LeetCode-practice**](https://github.com/firemoraster/LeetCode-practice) | Ongoing Java core & algorithm practice | Java |

---

### 🧰 Tech I work with

**Languages** · Java, SQL, JavaScript, Bash
**Backend** · Spring Boot (Web, Data JPA, Security, Actuator), REST, OpenAPI
**Messaging & Data** · Apache Kafka, PostgreSQL, Redis, MongoDB
**Infra & Tooling** · Docker, docker-compose, GitHub Actions, Git, Maven, Linux (Ubuntu VPS)
**Practices** · Hexagonal / Clean Architecture, CQRS, Transactional Outbox, Testcontainers

---

### 📊 On GitHub

<p align="center">
  <img src="https://img.shields.io/github/followers/firemoraster?label=Followers&style=social" alt="followers"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Focus-Java%20%2F%20Spring%20Backend-6DB33F" alt="focus"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Currently-Event--driven%20%26%20CQRS-blue" alt="currently"/>
</p>

---

### 📬 Get in touch

<p align="left">
  <a href="mailto:vitalyplemiannyk@gmail.com"><img src="https://img.shields.io/badge/Email-vitalyplemiannyk@gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://t.me/mooneiko"><img src="https://img.shields.io/badge/Telegram-@mooneiko-26A5E4?logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://www.linkedin.com/in/your-profile"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

<sub>💼 Open to Java backend opportunities — feel free to reach out.</sub>
