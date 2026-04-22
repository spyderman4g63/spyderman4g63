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
| User AI session hours | 1.5h | 8.8h | 22.2h | 22.2h |
| AI worker hours | 2.3h | 9.5h | 15.5h | 15.5h |
| AI concurrency hours | 4.5h | 26.7h | 69.1h | 69.1h |
| Interactive sessions | 6 | 30 | 84 | 84 |
| Worker sessions | 19 | 56 | 127 | 127 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 8,089 | 115.9M | 2.8M | 1,061.0M | $4,476.53 | $14,323.68 | $0.00 |
| claude-sonnet-4-6 | 30,888 | 127.8M | 7.6M | 1,691.6M | $1,271.12 | $4,567.55 | $4,022.49 |
| k2p5 | 2,254 | 46.8M | 745K | 167.9M | $202.26 | $453.56 | $809.04 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| gpt-5.4 | 560 | 8.0M | 173K | 53.8M | $36.47 | $100.91 | $158.40 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| k2p6 | 195 | 721K | 47K | 26.3M | $10.77 | $71.03 | $43.08 |
| gpt-5.3-codex | 97 | 926K | 30K | 5.4M | $6.35 | $10.26 | $18.37 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **43,952** | **323.9M** | **11.9M** | **3,153.2M** | **$6,081.08** | **$19,904.81** | **$5,537.15** |

_3,611.2M total tokens processed. 87.3% cache hit rate._

_$25,441.96 total saved ($19,904.81 caching + $5,537.15 model routing vs all-Opus)._

_Model savings are modest because ~87.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 8,130 | 115.9M | 2.8M | 1,063.3M | $3,545.31 | $14,354.62 | $0.00 |
| claude-sonnet-4-6 | 27,891 | 128.0M | 6.7M | 1,438.8M | $916.51 | $3,884.95 | $3,666.08 |
| k2p5 | 2,679 | 51.9M | 827K | 188.2M | $224.84 | $508.24 | $899.38 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.4 | 690 | 9.0M | 231K | 61.0M | $62.98 | $114.39 | $181.23 |
| gpt-5.3-codex | 353 | 2.5M | 132K | 29.8M | $26.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 399 | 2.4M | 189K | 20.0M | $20.66 | $37.68 | $61.04 |
| k2p6 | 195 | 721K | 47K | 26.3M | $10.76 | $71.03 | $43.08 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $2.84 | $5.09 | $8.47 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.40 | $0.00 | $1.63 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.06 | $0.00 | $0.28 |
| **Total** | **41,772** | **331.8M** | **11.2M** | **2,954.3M** | **$4,914.19** | **$19,366.65** | **$5,341.92** |

_3,408.3M total tokens processed. 86.7% cache hit rate._

_$24,708.57 total saved ($19,366.65 caching + $5,341.92 model routing vs all-Opus)._

_Model savings are modest because ~86.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-22 03:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
