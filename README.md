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
| User AI session hours | 0.0h | 2.2h | 6.3h | 6.3h |
| AI worker hours | 1.3h | 6.5h | 13.4h | 13.4h |
| AI concurrency hours | 1.3h | 9.8h | 22.0h | 22.0h |
| Interactive sessions | 0 | 4 | 7 | 7 |
| Worker sessions | 25 | 95 | 169 | 169 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,341 | 3K | 820K | 394.9M | $950.21 | $5,331.52 | $0.00 |
| gpt-5.5 | 5,580 | 23.0M | 858K | 160.3M | $115.39 | $432.86 | $521.00 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| k2p6 | 86 | 503K | 22K | 6.6M | $3.83 | $17.85 | $15.31 |
| claude-sonnet-4-6 | 56 | 71 | 24K | 3.2M | $2.66 | $8.70 | $5.36 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **8,250** | **25.8M** | **1.7M** | **582.0M** | **$1,083.31** | **$5,834.86** | **$591.89** |

_625.8M total tokens processed. 93% cache hit rate._

_$6,426.75 total saved ($5,834.86 caching + $591.89 model routing vs all-Opus)._

_Model savings are modest because ~93% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,422 | 115.9M | 5.1M | 1,831.4M | $6,636.54 | $24,724.65 | $0.00 |
| claude-sonnet-4-6 | 32,971 | 127.8M | 8.5M | 1,795.9M | $1,369.52 | $4,849.19 | $4,204.09 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 6,465 | 28.4M | 1.0M | 186.8M | $138.53 | $504.46 | $626.29 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| k2p6 | 859 | 4.0M | 263K | 99.0M | $45.90 | $267.56 | $183.62 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **59,258** | **361.6M** | **16.7M** | **4,350.5M** | **$8,555.70** | **$31,430.28** | **$6,638.21** |

_4,909.4M total tokens processed. 88.6% cache hit rate._

_$38,068.49 total saved ($31,430.28 caching + $6,638.21 model routing vs all-Opus)._

_Model savings are modest because ~88.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-04 23:17 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
