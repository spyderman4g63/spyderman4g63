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
| User AI session hours | 0.0h | 3.4h | 6.3h | 6.3h |
| AI worker hours | 1.1h | 6.5h | 13.0h | 13.0h |
| AI concurrency hours | 1.3h | 11.0h | 21.5h | 21.5h |
| Interactive sessions | 2 | 5 | 8 | 8 |
| Worker sessions | 20 | 97 | 173 | 173 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,386 | 3K | 845K | 397.3M | $964.98 | $5,364.29 | $0.00 |
| gpt-5.5 | 5,519 | 23.0M | 859K | 153.6M | $113.60 | $414.85 | $512.18 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| k2p6 | 149 | 662K | 54K | 9.7M | $5.72 | $26.27 | $22.89 |
| claude-sonnet-4-6 | 51 | 64 | 23K | 2.9M | $2.36 | $8.09 | $5.01 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **8,292** | **25.8M** | **1.8M** | **580.7M** | **$1,097.88** | **$5,857.44** | **$590.29** |

_625.1M total tokens processed. 92.9% cache hit rate._

_$6,447.73 total saved ($5,857.44 caching + $590.29 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,410 | 115.9M | 5.1M | 1,830.1M | $6,629.74 | $24,707.29 | $0.00 |
| claude-sonnet-4-6 | 32,966 | 127.8M | 8.5M | 1,795.7M | $1,369.22 | $4,848.59 | $4,203.74 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 5,927 | 26.0M | 922K | 169.8M | $126.54 | $458.51 | $571.68 |
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
| **Total** | **58,703** | **359.1M** | **16.6M** | **4,332.0M** | **$8,536.61** | **$31,366.37** | **$6,583.24** |

_4,888.0M total tokens processed. 88.6% cache hit rate._

_$37,949.61 total saved ($31,366.37 caching + $6,583.24 model routing vs all-Opus)._

_Model savings are modest because ~88.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-02 10:12 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
