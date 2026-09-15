<!--
**Polynomeer/Polynomeer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

## Hi there, I'm Polynomeer

[![Blog](https://img.shields.io/badge/Tech%20Blog-333664?&style=flat&logo=github&logoColor=white)](https://polynomeer.github.io/) [![For Recruiters](https://img.shields.io/badge/For%20Recruiters-2F855A?&style=flat&logo=readme&logoColor=white)](https://polynomeer.github.io/about/) ![polynomeer@gmail.com](https://img.shields.io/badge/polynomeer@gmail.com-red.svg?&style=flat&logo=gmail&logoColor=white)

### Make Non-Polynomial Polynomial

Backend engineer who designs systems where state transitions, concurrency, and transactional consistency have to hold. I have worked on settlement, batch, and content platforms where a single wrong state or a race between two jobs directly corrupts money-related data, and I solve those problems with explicit state models, lock design, and transaction boundaries rather than defensive patches.

In large data-processing environments I locate bottlenecks by measurement (heap dumps, GC logs, APM traces) and improve code and data structures together. I write the process down with numbers, and I rebuild the same principles in personal projects to check that I actually understand them.

### What I have shipped

- Redesigned an 800k-row settlement batch with chunked transactions, a SETNX + token distributed lock, and an explicit state transition model — 2 hours to 5 minutes, race conditions removed.
- Led the backend redesign of a music content platform from screen-driven APIs to a domain-centric structure with CQRS and a validation pipeline — API response 1.5 s to 300 ms, sequence lock contention removed (2 min to 10 s).
- Introduced ArchUnit and SonarCloud guardrails on a legacy codebase — static analysis violations 480 to 75.
- Moved long-running JPA batches and Excel exports to chunked and streaming processing — peak memory 3.8 GB to 1.6 GB, 1.2 GB to 180 MB.

### Projects worth reading

| Repository | What it demonstrates |
| --- | --- |
| [parity-pay](https://github.com/polynomeer/parity-pay) | Payment and double-entry ledger backend that keeps financial invariants under duplicate requests, concurrent debits, lost external responses, and process restarts. 26 load and failure experiments, 11 defects found and documented. |
| [monticker](https://github.com/polynomeer/monticker) | Event-centric stock monitoring: EMA-based anomaly detection over a 1-second ingestion loop, TimescaleDB continuous aggregates, OpenTelemetry tracing. |
| [spring-lab](https://github.com/polynomeer/spring-lab) | 20-week walk through Spring internals — container, bean lifecycle, AOP, transactions, MVC, Boot auto-configuration — verified against source and reproduced in 22 reduced modules with 217 tests. |
| [spring-lite](https://github.com/polynomeer/spring-lite) | Minimal Spring reimplementation: IoC/DI, bean lifecycle, proxy-based AOP, `@Transactional`, MVC dispatcher. |
| [redis-lite-java](https://github.com/polynomeer/redis-lite-java) | Redis clone on Java NIO: RESP protocol, single-threaded reactor, expiry heap, transactions, Pub/Sub, Lua. |
| [starkraft](https://github.com/polynomeer/starkraft) | Deterministic RTS simulation core with versioned protocol, replay verification, and CI soak tests. |

Long-form write-ups live on the blog: [batch consistency series](https://polynomeer.github.io/series/batch-structure-improvement/), [key generation bottleneck series](https://polynomeer.github.io/series/sequence-bottleneck/), [Redis internals via redis-lite-java](https://polynomeer.github.io/series/redis-lite-java/).

### Stack

**Backend** ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?&style=flat&logo=openjdk&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Spring Batch](https://img.shields.io/badge/Spring%20Batch-6DB33F?style=flat&logo=spring&logoColor=white)

**Data** ![JPA](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=flat&logo=hibernate&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat) ![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=flat) ![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&style=flat&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Messaging** ![Amazon SQS](https://img.shields.io/badge/Amazon%20SQS-FF4F8B?style=flat&logo=amazonsqs&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

**Infrastructure** ![Amazon AWS](https://img.shields.io/badge/AWS%20EC2%20%2F%20RDS%20%2F%20ECS-232F3E.svg?&style=flat&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Observability and quality** ![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat&logo=junit5&logoColor=white) ![ArchUnit](https://img.shields.io/badge/ArchUnit-1B1F23?style=flat)

### Statistics

<table>
  <tr>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats-rho-one-51.vercel.app/api?username=polynomeer&show_icons=true&theme=material-palenight&hide_border=true&bg_color=20232a&icon_color=E3E3E3A8&text_color=fff&title_color=918FE0" />
      </a>
    </td>
    <td>
      <a href="https://github.com/polynomeer/github-stats">
        <img src="https://raw.githubusercontent.com/polynomeer/github-stats-transparent/output/generated/languages.svg" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats-rho-one-51.vercel.app/api/top-langs/?username=polynomeer&layout=compact&theme=blueberry&hide_border=true" />
      </a>
    </td>
    <td>
      <img src="https://github-readme-stats-rho-one-51.vercel.app/api?username=polynomeer&show_icons=true&count_private=true&theme=blueberry&hide_border=true" />
    </td>
  </tr>
</table>
