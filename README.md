<!--
**Polynomeer/Polynomeer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=20&duration=2800&pause=1200&color=7EE787&center=true&vCenter=true&width=560&lines=%24+whoami;polynomeer+%E2%80%94+backend+engineer;%24+cat+motto.txt;Make+Non-Polynomial+Polynomial.;%24+echo+%24INTERESTS;concurrency%2C+Redis+internals%2C+someday+my+own+product" alt="typing banner" />
</p>

[![Blog](https://img.shields.io/badge/Tech%20Blog-333664?&style=flat&logo=github&logoColor=white)](https://polynomeer.github.io/) [![For Recruiters](https://img.shields.io/badge/For%20Recruiters-2F855A?&style=flat&logo=readme&logoColor=white)](https://polynomeer.github.io/about/) ![polynomeer@gmail.com](https://img.shields.io/badge/polynomeer@gmail.com-red.svg?&style=flat&logo=gmail&logoColor=white)

<p align="center">
  <img src="assets/terminal-b.svg" alt="terminal: whoami, motto, neofetch, interests" width="680" />
</p>

<div align="center">

![followers](https://img.shields.io/github/followers/polynomeer?style=flat&label=followers&color=BF91F3&logo=github&logoColor=white)
![stars](https://img.shields.io/github/stars/polynomeer?style=flat&label=stars&color=70A5FD&logo=github&logoColor=white&affiliations=OWNER)
![repos](https://img.shields.io/badge/dynamic/json?style=flat&label=repos&color=7EE787&logo=github&logoColor=white&query=public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2Fpolynomeer)

</div>

> [!IMPORTANT]
> What I claim, I rebuild outside of work and put under load before I call it proven — see the projects below.

## `~/projects`

<details>
<summary><code>parity-pay/</code> — prepaid wallet + ledger, 41 failure experiments, 14 defects fixed</summary>
<br>

Lost bank responses are kept as an undetermined state and settled by status query instead of retried. A Transactional Outbox bridges DB commit and Kafka publish. Broker kills, misconfigured partition keys, and slow institutions were reproduced to measure what bulkheads, circuit breakers, and rate limiters each prevent.

[repo](https://github.com/polynomeer/parity-pay) · [write-up](https://polynomeer.github.io/series/parity-pay/)

</details>

<details>
<summary><code>monticker/</code> — event-centric stock monitor, TimescaleDB + OpenTelemetry</summary>
<br>

Volume surges judged as multiples of an EMA baseline. One record per change per minute, enforced by a pre-save check and a DB constraint.

[repo](https://github.com/polynomeer/monticker) · [write-up](https://polynomeer.github.io/series/monticker/)

</details>

<details>
<summary><code>quno/</code> — revisioned Q&amp;A, row-locked concurrent edits</summary>
<br>

Concurrent edits lock the question row before computing the next version. The change and its notification request commit in one transaction — verified with an 8-thread integration test.

[repo](https://github.com/polynomeer/quno)

</details>

<details>
<summary><code>sys-drill/</code> — failure-handling practice platform, AI-graded + server-verified</summary>
<br>

Six exercises graded by staged tests. Design answers are scored by an AI evaluator whose output the server validates and recomputes.

[repo](https://github.com/polynomeer/sys-drill)

</details>

<details>
<summary><code>spring-lab/</code> — 20-week walk through Spring internals</summary>
<br>

Container, bean lifecycle, AOP, transactions, MVC, Boot auto-configuration — verified against source and reproduced in reduced modules with tests.

[repo](https://github.com/polynomeer/spring-lab)

</details>

<details>
<summary><code>redis-lite-java/</code> — Redis clone on Java NIO</summary>
<br>

RESP protocol, single-threaded reactor, expiry heap, transactions, Pub/Sub, Lua.

[repo](https://github.com/polynomeer/redis-lite-java)

</details>

## GitHub status at a glance

<table>
  <tr>
    <td><img src="https://github-readme-stats-rho-one-51.vercel.app/api?username=polynomeer&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" alt="stats" /></td>
    <td><img src="https://streak-stats.demolab.com/?user=polynomeer&theme=tokyonight&hide_border=true" alt="streak" /></td>
  </tr>
</table>
