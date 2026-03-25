<div align="center">

# Luis Henrique de Barros

**Backend Engineer** — Java · Python · Oracle PL/SQL

[![Website](https://img.shields.io/badge/luisbarros.dev-000000?style=flat-square&logo=vercel&logoColor=white)](https://luisbarros.dev)
[![Email](https://img.shields.io/badge/me%40luisbarros.dev-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:me@luisbarros.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/luis-henrique-de-barros)

</div>

---

Backend engineer com foco em sistemas escaláveis, arquitetura limpa e design orientado a domínio. Atualmente na **NovaSmar S/A** como Analyst.

Especialidade em sistemas Java/Spring Boot com arquitetura hexagonal, DDD e event-driven design — do ambiente enterprise legado ao backend moderno.

---

## Stack

**Linguagens**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PL/SQL](https://img.shields.io/badge/Oracle_PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)

**Frameworks & Plataformas**

![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Banco de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**Arquitetura & Práticas**

`Hexagonal Architecture` · `Domain-Driven Design` · `Event-Driven Design` · `CQRS` · `Bounded Contexts` · `SOLID`

**Infraestrutura**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-9B2335?style=flat-square&logo=testcontainers&logoColor=white)

---

## Projetos

### [Discord-like Chat Platform](https://github.com/LuisHBarros/Discord-like)
Plataforma de mensagens em tempo real com foco em segurança e arquitetura de produção.

- Arquitetura hexagonal com DDD em 3 bounded contexts (Identity, Collaboration, Presence)
- Event-driven com **Apache Kafka** para processamento assíncrono
- **E2EE** via ECDH + HKDF-SHA256 + AES-256-GCM com verificação de assinaturas
- WebSocket com hardening de segurança (sender ID extraído da sessão, não do cliente)
- Testes de integração com **Testcontainers** (PostgreSQL, Redis, Kafka) + CI/CD via GitHub Actions

`Java 21` `Spring Boot 3` `Kafka` `PostgreSQL` `Redis` `WebSocket` `Testcontainers`

---

### [Assine — Newsletter Microservices](https://github.com/LuisHBarros/assine)
Plataforma de assinaturas de newsletters construída como sistema de microsserviços.

- API Gateway com **Spring Cloud Gateway** e roteamento por serviço
- Banco de dados isolado por serviço (PostgreSQL por bounded context)
- Integração com **Stripe** (pagamentos), **SendGrid** (e-mail) e **Nuvem Fiscal** (NF-e)
- Comunicação assíncrona via **RabbitMQ**

`Java 21` `Spring Cloud` `RabbitMQ` `PostgreSQL` `Stripe` `Docker`

---

<div align="center">
  <sub>Building systems that scale. Code that lasts.</sub>
</div>
