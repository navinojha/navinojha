# <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"> Hi, I'm Navin Ojha

### Backend Engineer • Java • Spring Boot • Distributed Systems • Kafka

> Building scalable backend systems, real-time applications, and reliable distributed services.

I’m a **Backend Software Engineer with 5+ years of experience**, focused on designing and building high-performance backend systems using **Java, Spring Boot, Kafka, Redis, PostgreSQL, and distributed-system architectures**.

Currently working as an **SDE 2 at Pragmatic Play / Arrise**, where I work on real-time gaming systems and backend services.

---

## 🚀 What I Work On

```text
☕ Java / Spring Boot
⚡ High-performance backend services
📨 Kafka & event-driven architectures
🧠 Distributed systems
⚡ Redis & caching
🗄️ PostgreSQL / relational databases
🔌 REST APIs & WebSockets
🔐 Security / JWT / OAuth
🧵 Concurrency & multithreading
🎮 Real-time gaming systems
☁️ Scalable cloud-native architectures
```

---

## 🧠 Engineering Interests

I'm especially interested in problems involving:

**Scalability → Reliability → Performance → Distributed Systems**

Some areas I'm actively exploring:

- Distributed systems & system design
- Kafka internals and event-driven architecture
- Redis internals and high-throughput caching
- JVM internals, GC and performance tuning
- Low-latency real-time applications
- Concurrent programming in Java
- Microservices architecture
- AI-powered developer tools and agents
- MCP / LLM-powered engineering workflows

---

## 🛠️ Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)

### Messaging & Distributed Systems

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Development

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 💻 Featured Engineering Projects

### 🎮 Real-Time Game Systems

Exploring backend architectures for real-time multiplayer and casino gaming systems.

**Technologies:**  
`Java` `Spring Boot` `WebSockets` `Kafka` `Redis` `Concurrency`

Focus areas:

- Real-time event broadcasting
- Game-round lifecycle management
- Concurrent state management
- Low-latency communication
- Fault tolerance
- Event-driven architecture

---

### 🚦 Distributed Rate Limiter

A production-style rate limiting system supporting multiple strategies.

```text
                    ┌─────────────────┐
                    │     Client      │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   Rate Limiter  │
                    └────────┬────────┘
                             │
             ┌───────────────┼───────────────┐
             ▼               ▼               ▼
       Fixed Window    Sliding Window   Token Bucket
             │               │               │
             └───────────────┼───────────────┘
                             ▼
                      State Manager
                             │
                             ▼
                           Redis
```

Designed with **Strategy Pattern, SOLID principles, concurrency control and extensibility** in mind.

---

### 🧩 Distributed Systems Playground

A collection of backend experiments covering:

- Kafka producers & consumers
- Retry strategies
- Dead Letter Queues
- Idempotency
- Distributed locking
- Caching
- Database optimization
- JVM performance
- Concurrency patterns

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=navinojha&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=navinojha&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=navinojha&theme=tokyonight&hide_border=true" />
</p>

---

## 🔥 Things I'm Currently Learning

```text
┌──────────────────────────────────────────┐
│ Distributed Systems                      │
│                                          │
│  Kafka Internals                         │
│  Redis Internals                         │
│  JVM Internals                           │
│  Garbage Collection                      │
│  High-Performance Java                  │
│  System Design                           │
│  AI Agents & MCP                         │
│  LLM-powered Developer Tools             │
└──────────────────────────────────────────┘
```

---

## 🧪 Engineering Philosophy

I enjoy going beyond **"it works"** and asking:

> **Can it scale?**  
> **Can it fail safely?**  
> **Can we make it faster?**  
> **What happens when traffic grows 10x?**  
> **What happens when a dependency goes down?**

Good backend engineering isn't only about writing APIs.

It's about designing systems that remain **fast, reliable and maintainable under pressure**.

---

## 🏗️ System Design

I enjoy designing systems around:

```text
                 ┌─────────────┐
                 │   Clients   │
                 └──────┬──────┘
                        │
                        ▼
                ┌───────────────┐
                │ API Gateway   │
                └───────┬───────┘
                        │
                        ▼
                ┌───────────────┐
                │ Load Balancer │
                └───────┬───────┘
                        │
             ┌──────────┼──────────┐
             ▼          ▼          ▼
          Service A  Service B  Service C
             │          │          │
             └──────────┼──────────┘
                        │
                 ┌──────┴──────┐
                 │    Kafka    │
                 └──────┬──────┘
                        │
             ┌──────────┼──────────┐
             ▼                     ▼
          Redis                 PostgreSQL
```

Areas I care about:

`CAP` • `PACELC` • `CQRS` • `Saga` • `Caching` • `Sharding` • `Replication` • `Idempotency` • `Observability`

---

## 📚 Problem Solving

I regularly practice data structures and algorithms with a focus on recognizing patterns rather than memorizing solutions.

Some patterns I focus on:

`Sliding Window`  
`Two Pointers`  
`Prefix Sum`  
`Hashing`  
`Binary Search`  
`Heap / Priority Queue`  
`Graphs`  
`Dynamic Programming`

---

## 🌱 Open Source & Learning

I'm continuously experimenting with new backend technologies and building small projects to understand how things work **under the hood**.

My goal is simple:

> **Learn → Build → Measure → Improve**

---

## 🤝 Let's Connect

I'm interested in conversations around:

**Backend Engineering • Distributed Systems • Java • Kafka • System Design • Performance • AI Engineering**

<p align="left">
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

### ⚡ Fun Fact

I like taking a simple backend problem and asking:

**"How would we design this if 100 million users suddenly used it?"**

---

<p align="center">
  <b>⭐ Build systems. Understand fundamentals. Keep learning.</b>
</p>
