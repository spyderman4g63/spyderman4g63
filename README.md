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
| User AI session hours | 0.7h | 7.2h | 8.8h | 8.8h |
| AI worker hours | 1.0h | 7.8h | 16.6h | 16.6h |
| AI concurrency hours | 2.3h | 20.5h | 32.5h | 32.5h |
| Interactive sessions | 2 | 9 | 16 | 16 |
| Worker sessions | 21 | 140 | 292 | 292 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,664 | 6K | 2.1M | 683.3M | $1,911.92 | $9,224.90 | $0.00 |
| claude-sonnet-4-6 | 2,206 | 2K | 985K | 117.9M | $105.56 | $318.40 | $200.66 |
| gpt-5.5 | 4,541 | 20.1M | 713K | 126.2M | $96.72 | $340.93 | $436.21 |
| k2p6 | 859 | 4.0M | 263K | 99.0M | $45.90 | $267.56 | $183.62 |
| gpt-5.5-fast | 101 | 1.5M | 37K | 9.7M | $6.91 | $26.35 | $32.00 |
| k2p5 | 19 | 372K | 5K | 1.4M | $1.63 | $3.84 | $6.50 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **12,449** | **26.3M** | **4.1M** | **1,040.4M** | **$2,170.29** | **$10,187.07** | **$864.71** |

_1,124.4M total tokens processed. 92.5% cache hit rate._

_$11,051.78 total saved ($10,187.07 caching + $864.71 model routing vs all-Opus)._

_Model savings are modest because ~92.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,760 | 115.9M | 4.9M | 1,744.5M | $6,390.97 | $23,551.96 | $0.00 |
| claude-sonnet-4-6 | 32,944 | 127.8M | 8.5M | 1,794.5M | $1,368.19 | $4,845.31 | $4,201.76 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 4,541 | 20.1M | 713K | 126.2M | $96.72 | $340.93 | $436.21 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| k2p6 | 859 | 4.0M | 263K | 99.0M | $45.90 | $267.56 | $183.62 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| gpt-5.5-fast | 101 | 1.5M | 37K | 9.7M | $6.91 | $26.35 | $32.00 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **56,618** | **352.7M** | **16.2M** | **4,197.0M** | **$8,264.33** | **$30,077.69** | **$6,433.29** |

_4,741.0M total tokens processed. 88.5% cache hit rate._

_$36,510.98 total saved ($30,077.69 caching + $6,433.29 model routing vs all-Opus)._

_Model savings are modest because ~88.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-21 18:16 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
