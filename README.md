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
| User AI session hours | 0.0h | 6.5h | 8.2h | 8.2h |
| AI worker hours | 1.0h | 7.9h | 16.6h | 16.6h |
| AI concurrency hours | 1.0h | 19.3h | 31.2h | 31.2h |
| Interactive sessions | 0 | 8 | 15 | 15 |
| Worker sessions | 21 | 140 | 292 | 292 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,683 | 6K | 2.1M | 685.8M | $1,923.40 | $9,259.05 | $0.00 |
| claude-sonnet-4-6 | 2,251 | 2K | 1.0M | 121.7M | $110.12 | $328.59 | $206.76 |
| gpt-5.5 | 4,498 | 19.9M | 707K | 124.8M | $95.85 | $337.22 | $432.25 |
| k2p6 | 859 | 4.0M | 263K | 99.0M | $45.90 | $267.56 | $183.62 |
| gpt-5.5-fast | 63 | 1.0M | 24K | 4.4M | $4.19 | $12.13 | $19.44 |
| k2p5 | 19 | 372K | 5K | 1.4M | $1.63 | $3.84 | $6.50 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **12,432** | **25.6M** | **4.1M** | **1,040.0M** | **$2,182.74** | **$10,213.49** | **$854.30** |

_1,124.7M total tokens processed. 92.5% cache hit rate._

_$11,067.79 total saved ($10,213.49 caching + $854.30 model routing vs all-Opus)._

_Model savings are modest because ~92.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,757 | 115.9M | 4.9M | 1,744.4M | $6,389.54 | $23,550.47 | $0.00 |
| claude-sonnet-4-6 | 32,944 | 127.8M | 8.5M | 1,794.5M | $1,368.19 | $4,845.31 | $4,201.76 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 4,498 | 19.9M | 707K | 124.8M | $95.85 | $337.22 | $432.25 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| k2p6 | 859 | 4.0M | 263K | 99.0M | $45.90 | $267.56 | $183.62 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.5-fast | 63 | 1.0M | 24K | 4.4M | $4.19 | $12.13 | $19.44 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **56,534** | **352.1M** | **16.1M** | **4,190.2M** | **$8,259.31** | **$30,058.27** | **$6,416.78** |

_4,733.5M total tokens processed. 88.5% cache hit rate._

_$36,475.05 total saved ($30,058.27 caching + $6,416.78 model routing vs all-Opus)._

_Model savings are modest because ~88.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-21 14:14 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
