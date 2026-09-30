<!--
**Polynomeer/Polynomeer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

[![Blog](https://img.shields.io/badge/Tech%20Blog-333664?&style=flat&logo=github&logoColor=white)](https://polynomeer.github.io/) [![For Recruiters](https://img.shields.io/badge/For%20Recruiters-2F855A?&style=flat&logo=readme&logoColor=white)](https://polynomeer.github.io/about/) ![polynomeer@gmail.com](https://img.shields.io/badge/polynomeer@gmail.com-red.svg?&style=flat&logo=gmail&logoColor=white)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&size=20&duration=2800&pause=1200&color=7EE787&center=true&vCenter=true&width=560&lines=%24+whoami;polynomeer+%E2%80%94+backend+engineer;%24+cat+motto.txt;Make+Non-Polynomial+Polynomial.;%24+echo+%24INTERESTS;concurrency%2C+Redis+internals%2C+someday+my+own+product" alt="typing banner" />
</p>

<pre>
$ neofetch --github

polynomeer@github
-----------------
Role       backend engineer
Focus      state machines, locks, transaction boundaries
Repos      <img src="https://img.shields.io/github/repos/polynomeer?style=flat&label=%20&color=7EE787&logo=github" alt="repo count" height="18" />
Followers  <img src="https://img.shields.io/github/followers/polynomeer?style=flat&label=%20&color=BF91F3&logo=github" alt="followers" height="18" />
Stars      <img src="https://img.shields.io/github/stars/polynomeer?style=flat&label=%20&color=70A5FD&logo=github&affiliations=OWNER" alt="stars" height="18" />
</pre>

```
$ cat interests.txt
# the kind of problem I stay up late on
- state that must never end up in two places at once
- reproducing a bug on purpose before calling it fixed
- Redis internals, transaction boundaries, distributed locks
- long-standing itch to ship my own product someday, not just work inside one
```

### Projects worth reading

| Repository | What it demonstrates |
| --- | --- |
| [parity-pay](https://github.com/polynomeer/parity-pay) | Prepaid wallet payment and double-entry ledger backend. Lost bank responses are kept as an undetermined state and settled by status query instead of retried; a Transactional Outbox bridges DB commit and Kafka publish; broker kills, misconfigured partition keys, and slow institutions were reproduced to measure what bulkheads, circuit breakers, and rate limiters each prevent. 41 load and failure experiments, 14 defects found and fixed. |
| [monticker](https://github.com/polynomeer/monticker) | Event-centric stock monitoring: volume surges judged as multiples of an EMA baseline, one record per change per minute enforced by a pre-save check and a DB constraint, TimescaleDB continuous aggregates, OpenTelemetry tracing. |
| [quno](https://github.com/polynomeer/quno) | Developer Q&A that keeps every question revision. Concurrent edits lock the question row before computing the next version, change and notification request commit in one transaction, verified by an 8-thread integration test. |
| [sys-drill](https://github.com/polynomeer/sys-drill) | Backend failure-handling practice platform: six exercises graded by staged tests, design answers scored by an AI evaluator whose output the server validates and recomputes, evaluation run from a Redis queue with a retry limit. |
| [spring-lab](https://github.com/polynomeer/spring-lab) | 20-week walk through Spring internals — container, bean lifecycle, AOP, transactions, MVC, Boot auto-configuration — verified against source and reproduced in reduced modules with tests. |
| [redis-lite-java](https://github.com/polynomeer/redis-lite-java) | Redis clone on Java NIO: RESP protocol, single-threaded reactor, expiry heap, transactions, Pub/Sub, Lua. |

Long-form write-ups live on the blog: [ParityPay series](https://polynomeer.github.io/series/parity-pay/), [monticker series](https://polynomeer.github.io/series/monticker/), [batch consistency series](https://polynomeer.github.io/series/batch-structure-improvement/), [key generation bottleneck series](https://polynomeer.github.io/series/sequence-bottleneck/).

### Statistics

<table>
  <tr>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats-rho-one-51.vercel.app/api?username=polynomeer&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" alt="polynomeer's GitHub stats" />
      </a>
    </td>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats-rho-one-51.vercel.app/api/top-langs/?username=polynomeer&layout=compact&theme=tokyonight&hide_border=true" alt="polynomeer's most-used languages" />
      </a>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/DenverCoder1/github-readme-streak-stats">
    <img src="https://streak-stats.demolab.com/?user=polynomeer&theme=tokyonight&hide_border=true" alt="polynomeer's GitHub streak stats" />
  </a>
</p>
