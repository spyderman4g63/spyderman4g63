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
| User AI session hours | 0.0h | 0.6h | 8.1h | 115.5h |
| AI worker hours | 1.5h | 9.6h | 35.7h | 241.3h |
| AI concurrency hours | 1.5h | 12.7h | 50.7h | 489.2h |
| Interactive sessions | 0 | 4 | 17 | 280 |
| Worker sessions | 38 | 289 | 340 | 2,295 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 90 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 872 | 1K | 270K | 103.6M | $317.69 | $1,399.62 | $0.00 |
| gpt-5.5 | 6,658 | 31.2M | 1.0M | 213.3M | $151.73 | $576.13 | $691.19 |
| claude-opus-4-7 | 39 | 64 | 52K | 5.0M | $18.88 | $67.62 | $0.00 |
| claude-sonnet-4-6 | 37 | 45 | 29K | 2.5M | $2.34 | $6.98 | $4.88 |
| k2p6 | 2 | 80K | 3K | 0 | $0.29 | $0.00 | $1.15 |
| **Total** | **7,608** | **31.3M** | **1.3M** | **324.6M** | **$490.93** | **$2,050.35** | **$697.22** |

_365.5M total tokens processed. 88.8% cache hit rate._

_$2,747.57 total saved ($2,050.35 caching + $697.22 model routing vs all-Opus)._

_Model savings are modest because ~88.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-sonnet-4-6 | 32,983 | 127.8M | 8.5M | 1,797.1M | $1,370.76 | $4,852.44 | $4,206.73 |
| gpt-5.5 | 11,289 | 51.7M | 1.7M | 342.4M | $250.31 | $924.66 | $1,135.88 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| k2p6 | 861 | 4.1M | 266K | 99.0M | $46.19 | $267.56 | $184.77 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| claude-opus-4-7 | 39 | 64 | 52K | 5.0M | $18.88 | $67.62 | $0.00 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **64,399** | **384.9M** | **17.6M** | **4,533.3M** | **$8,771.73** | **$32,203.89** | **$7,151.59** |

_5,119.4M total tokens processed. 88.6% cache hit rate._

_$39,355.48 total saved ($32,203.89 caching + $7,151.59 model routing vs all-Opus)._

_Model savings are modest because ~88.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-22 04:04 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
