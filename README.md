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
| User AI session hours | 0.0h | 0.6h | 9.3h | 115.5h |
| AI worker hours | 1.4h | 9.4h | 35.9h | 239.7h |
| AI concurrency hours | 1.4h | 12.5h | 52.2h | 487.6h |
| Interactive sessions | 0 | 4 | 17 | 280 |
| Worker sessions | 42 | 294 | 353 | 2,295 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 90 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 904 | 1K | 278K | 106.0M | $324.50 | $1,431.77 | $0.00 |
| gpt-5.5 | 6,381 | 29.9M | 959K | 205.6M | $145.62 | $555.36 | $663.57 |
| claude-opus-4-7 | 39 | 64 | 52K | 5.0M | $18.88 | $67.62 | $0.00 |
| claude-sonnet-4-6 | 39 | 49 | 29K | 2.6M | $2.57 | $7.13 | $4.97 |
| k2p6 | 2 | 80K | 3K | 0 | $0.29 | $0.00 | $1.15 |
| **Total** | **7,365** | **30.0M** | **1.3M** | **319.3M** | **$491.86** | **$2,061.87** | **$669.69** |

_359.1M total tokens processed. 88.9% cache hit rate._

_$2,731.56 total saved ($2,061.87 caching + $669.69 model routing vs all-Opus)._

_Model savings are modest because ~88.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-sonnet-4-6 | 32,983 | 127.8M | 8.5M | 1,797.1M | $1,370.76 | $4,852.44 | $4,206.73 |
| gpt-5.5 | 11,001 | 50.4M | 1.6M | 334.4M | $243.99 | $902.96 | $1,107.30 |
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
| **Total** | **64,111** | **383.5M** | **17.5M** | **4,525.2M** | **$8,765.41** | **$32,182.19** | **$7,123.01** |

_5,110.0M total tokens processed. 88.6% cache hit rate._

_$39,305.20 total saved ($32,182.19 caching + $7,123.01 model routing vs all-Opus)._

_Model savings are modest because ~88.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-21 01:46 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
