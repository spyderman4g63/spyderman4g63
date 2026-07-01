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
| User AI session hours | 0.0h | 0.9h | 5.9h | 116.7h |
| AI worker hours | 1.7h | 14.3h | 43.7h | 259.8h |
| AI concurrency hours | 1.7h | 16.0h | 56.5h | 510.1h |
| Interactive sessions | 0 | 5 | 18 | 286 |
| Worker sessions | 23 | 189 | 226 | 2,295 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 101 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 7,772 | 35.7M | 1.1M | 241.8M | $173.69 | $653.01 | $789.31 |
| claude-opus-4-6 | 300 | 395 | 102K | 24.3M | $100.82 | $328.39 | $0.00 |
| claude-opus-4-7 | 125 | 217 | 100K | 14.5M | $45.12 | $196.08 | $0.00 |
| k2p7 | 162 | 1.0M | 90K | 18.8M | $10.12 | $50.77 | $40.49 |
| claude-sonnet-4-6 | 17 | 21 | 21K | 1.4M | $1.54 | $3.85 | $2.99 |
| k2p6 | 2 | 80K | 3K | 0 | $0.29 | $0.00 | $1.15 |
| **Total** | **8,378** | **36.8M** | **1.4M** | **300.9M** | **$331.58** | **$1,232.10** | **$833.94** |

_343.3M total tokens processed. 87.6% cache hit rate._

_$2,066.04 total saved ($1,232.10 caching + $833.94 model routing vs all-Opus)._

_Model savings are modest because ~87.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-sonnet-4-6 | 32,983 | 127.8M | 8.5M | 1,797.1M | $1,370.76 | $4,852.44 | $4,206.73 |
| gpt-5.5 | 13,484 | 60.9M | 2.0M | 404.9M | $295.76 | $1,093.30 | $1,340.72 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| k2p6 | 861 | 4.1M | 266K | 99.0M | $46.19 | $267.56 | $184.77 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| claude-opus-4-7 | 125 | 217 | 100K | 14.5M | $45.12 | $196.08 | $0.00 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| k2p7 | 162 | 1.0M | 90K | 18.8M | $10.12 | $50.77 | $40.49 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **66,842** | **395.1M** | **18.0M** | **4,624.0M** | **$8,853.54** | **$32,551.76** | **$7,396.91** |

_5,221.3M total tokens processed. 88.6% cache hit rate._

_$39,948.67 total saved ($32,551.76 caching + $7,396.91 model routing vs all-Opus)._

_Model savings are modest because ~88.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-01 10:44 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
