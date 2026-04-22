# John Ward

**http://johnathanward.com**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 0h | 0h | 0h | ~0h* |
| User AI session hours | 1.6h | 9.9h | 22.0h | 22.0h |
| AI worker hours | 0.5h | 9.5h | 15.2h | 15.2h |
| AI concurrency hours | 4.3h | 29.1h | 62.7h | 62.7h |
| Interactive sessions | 10 | 32 | 85 | 85 |
| Worker sessions | 2 | 56 | 116 | 116 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 8,074 | 115.9M | 2.8M | 1,060.8M | $4,473.75 | $14,321.87 | $0.00 |
| claude-sonnet-4-6 | 30,905 | 127.8M | 7.6M | 1,691.6M | $1,271.12 | $4,567.55 | $4,022.49 |
| k2p5 | 2,203 | 46.6M | 735K | 166.2M | $200.75 | $448.77 | $802.99 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| gpt-5.4 | 560 | 8.0M | 173K | 53.8M | $36.47 | $100.91 | $158.40 |
| k2p6 | 590 | 2.8M | 168K | 74.8M | $33.52 | $201.96 | $134.06 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| gpt-5.3-codex | 96 | 809K | 30K | 5.4M | $5.94 | $10.26 | $16.90 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 63 | 338K | 22K | 2.7M | $1.05 | $5.09 | $8.05 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **44,296** | **325.6M** | **12.0M** | **3,199.8M** | **$6,099.09** | **$20,029.15** | **$5,620.19** |

_3,659.5M total tokens processed. 87.4% cache hit rate._

_$25,649.34 total saved ($20,029.15 caching + $5,620.19 model routing vs all-Opus)._

_Model savings are modest because ~87.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 8,132 | 115.9M | 2.8M | 1,063.3M | $3,545.31 | $14,354.62 | $0.00 |
| claude-sonnet-4-6 | 27,891 | 128.0M | 6.7M | 1,438.8M | $916.51 | $3,884.95 | $3,666.08 |
| k2p5 | 2,685 | 52.0M | 828K | 188.7M | $225.34 | $509.71 | $901.41 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.4 | 690 | 9.0M | 231K | 61.0M | $62.98 | $114.39 | $181.23 |
| k2p6 | 590 | 2.8M | 168K | 74.8M | $33.51 | $201.96 | $134.06 |
| gpt-5.3-codex | 353 | 2.5M | 132K | 29.8M | $26.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 399 | 2.4M | 189K | 20.0M | $20.66 | $37.68 | $61.04 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $2.84 | $5.09 | $8.47 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.40 | $0.00 | $1.63 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.06 | $0.00 | $0.28 |
| **Total** | **42,175** | **334.1M** | **11.4M** | **3,003.3M** | **$4,937.44** | **$19,499.06** | **$5,434.93** |

_3,459.7M total tokens processed. 86.8% cache hit rate._

_$24,933.99 total saved ($19,499.06 caching + $5,434.93 model routing vs all-Opus)._

_Model savings are modest because ~86.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-22 20:46 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
