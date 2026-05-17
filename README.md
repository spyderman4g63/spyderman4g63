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
| User AI session hours | 0.0h | 8.3h | 10.3h | 10.3h |
| AI worker hours | 1.1h | 8.6h | 15.2h | 15.2h |
| AI concurrency hours | 1.1h | 23.3h | 34.7h | 34.7h |
| Interactive sessions | 0 | 17 | 20 | 20 |
| Worker sessions | 21 | 145 | 273 | 273 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,736 | 6K | 2.1M | 691.5M | $1,947.47 | $9,336.45 | $0.00 |
| claude-sonnet-4-6 | 3,401 | 3K | 1.6M | 255.3M | $211.12 | $689.44 | $407.11 |
| gpt-5.5 | 3,656 | 16.4M | 583K | 97.9M | $77.62 | $264.44 | $349.31 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| gpt-5.5-fast | 51 | 546K | 15K | 3.6M | $2.59 | $9.98 | $11.94 |
| gpt-5.4 | 42 | 195K | 18K | 4.0M | $1.88 | $7.62 | $7.20 |
| k2p5 | 19 | 372K | 5K | 1.4M | $1.63 | $3.84 | $6.50 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **12,815** | **21.6M** | **4.7M** | **1,155.0M** | **$2,289.31** | **$10,582.54** | **$969.21** |

_1,250.6M total tokens processed. 92.4% cache hit rate._

_$11,551.75 total saved ($10,582.54 caching + $969.21 model routing vs all-Opus)._

_Model savings are modest because ~92.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,707 | 115.9M | 4.9M | 1,738.2M | $6,370.71 | $23,466.04 | $0.00 |
| claude-sonnet-4-6 | 32,925 | 127.8M | 8.5M | 1,793.3M | $1,367.50 | $4,842.18 | $4,200.06 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| gpt-5.5 | 3,656 | 16.4M | 583K | 97.9M | $77.62 | $264.44 | $349.31 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.5-fast | 51 | 546K | 15K | 3.6M | $2.59 | $9.98 | $11.94 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **55,603** | **347.9M** | **16.0M** | **4,154.4M** | **$8,219.41** | **$29,893.91** | **$6,322.44** |

_4,692.8M total tokens processed. 88.5% cache hit rate._

_$36,216.34 total saved ($29,893.91 caching + $6,322.44 model routing vs all-Opus)._

_Model savings are modest because ~88.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-17 16:58 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
