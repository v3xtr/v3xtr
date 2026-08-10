<h1 align="center">Nikita Kuznetsov (@v3xtr)</h1>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=00A86B&center=true&vCenter=true&width=600&lines=Self-Taught+Backend+Engineer;TypeScript+to+Java+in+5+months;Building+distributed+systems+solo" />
</div>

> 23 months in backend overall, switched from TypeScript to Java/Spring Boot ~5 months ago and rebuilt a multi-service platform (12+ microservices) solo, from event-driven architecture down to Kubernetes deployment.

---

## Cybersecurity Achievement

![](https://tryhackme-badges.s3.amazonaws.com/v3xtr.png)

**Top 8% worldwide on TryHackMe** — applying an offensive-security mindset to backend development.

---

## Connect
<div align="center">
  <a href="https://linkedin.com/in/nikita-kuznetsov-a25636312/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://t.me/linux_backend_coder" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="mailto:smirnoffa675@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://tryhackme.com/p/v3xtr" target="_blank">
    <img src="https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe" />
  </a>
</div>

---

## Tech Stack

**Backend & Architecture**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=Apache-Kafka&logoColor=white)

**Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

**DevOps & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)

**Monitoring & Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elastic&logoColor=white)

---

## Technical Expertise

**Data Management & Storage**

- PostgreSQL — primary relational database, system of record for all writes
- PgBouncer — connection pooling in front of PostgreSQL for efficient concurrent connections
- Redis — in-memory caching, session storage, real-time features
- MongoDB — document storage for unstructured data
- Elasticsearch — full-text/faceted search, chosen over Postgres full-text/vector search for better performance at scale, kept in sync via CQRS
- AWS S3 — object storage for media and static assets

**DevOps & Infrastructure**

Containerizing applications with Docker, orchestrating with Kubernetes, setting up CI/CD pipelines with GitHub Actions. On Kubernetes clusters, using Nginx as the edge proxy in front of a Traefik ingress controller.

**Monitoring & Observability**

Comprehensive monitoring with Prometheus and Grafana, log analysis with the Elastic Stack (ELK) and Kibana dashboards, plus Loki + Promtail for log aggregation on Kubernetes.

**Distributed Systems Patterns**

Designing multi-service architectures with event-driven communication over Kafka, including the transactional outbox pattern for reliable event publishing (no lost events on broker outages), CQRS (Postgres for writes, Elasticsearch for search/reads), and retry-with-backoff + dead-letter queues for consumers that can't yet process a message (e.g. a referenced entity hasn't landed in the database).

**Security Mindset**

Ranked top 8% worldwide on TryHackMe — apply that offensive-security mindset as a habit: routinely auditing my own services for OWASP Top 10 issues like broken object-level authorization, rather than assuming JWT auth alone is enough.

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/v3xtr/v3xtr/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/v3xtr/v3xtr/output/github-snake.svg" />
    <img alt="github-contribution-grid-snake" src="https://raw.githubusercontent.com/v3xtr/v3xtr/output/github-snake.svg" />
  </picture>
</div>
