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
| User AI session hours | 0.0h | 3.1h | 11.1h | 11.1h |
| AI worker hours | 0.0h | 6.4h | 15.0h | 15.0h |
| AI concurrency hours | 0.1h | 11.5h | 33.9h | 33.9h |
| Interactive sessions | 1 | 4 | 17 | 17 |
| Worker sessions | 1 | 116 | 264 | 264 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,696 | 6K | 2.1M | 685.4M | $1,917.97 | $9,252.96 | $0.00 |
| gpt-5.5 | 4,634 | 20.5M | 727K | 129.1M | $98.69 | $348.57 | $445.21 |
| claude-sonnet-4-6 | 2,024 | 2K | 931K | 102.9M | $97.38 | $277.91 | $179.41 |
| k2p6 | 269 | 1.2M | 95K | 24.2M | $12.39 | $65.60 | $49.56 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **11,810** | **23.9M** | **3.9M** | **958.7M** | **$2,137.65** | **$9,988.97** | **$724.39** |

_1,039.6M total tokens processed. 92.2% cache hit rate._

_$10,713.35 total saved ($9,988.97 caching + $724.39 model routing vs all-Opus)._

_Model savings are modest because ~92.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,814 | 115.9M | 4.9M | 1,748.7M | $6,402.70 | $23,607.57 | $0.00 |
| claude-sonnet-4-6 | 32,947 | 127.8M | 8.5M | 1,794.6M | $1,368.49 | $4,845.46 | $4,201.90 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 4,634 | 20.5M | 727K | 129.1M | $98.69 | $348.57 | $445.21 |
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
| **Total** | **56,795** | **353.6M** | **16.2M** | **4,208.6M** | **$8,280.99** | **$30,153.58** | **$6,454.93** |

_4,753.9M total tokens processed. 88.5% cache hit rate._

_$36,608.51 total saved ($30,153.58 caching + $6,454.93 model routing vs all-Opus)._

_Model savings are modest because ~88.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-23 13:34 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
