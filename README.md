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
| User AI session hours | 1.5h | 4.7h | 9.5h | 121.4h |
| AI worker hours | 1.2h | 9.3h | 43.8h | 268.1h |
| AI concurrency hours | 3.7h | 17.9h | 62.1h | 526.9h |
| Interactive sessions | 2 | 16 | 29 | 302 |
| Worker sessions | 22 | 122 | 89 | 2,295 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 109 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 908 | 1K | 721K | 112.9M | $365.43 | $1,524.87 | $0.00 |
| gpt-5.5 | 7,421 | 33.3M | 1.1M | 226.5M | $163.03 | $611.78 | $739.42 |
| claude-opus-4-6 | 226 | 305 | 74K | 17.6M | $69.77 | $238.19 | $0.00 |
| k2p7 | 194 | 1.1M | 98K | 20.1M | $10.85 | $54.43 | $43.39 |
| claude-sonnet-4-6 | 42 | 48 | 29K | 3.1M | $2.49 | $8.47 | $5.53 |
| kimi-k2.7-code-highspeed | 25 | 90K | 24K | 954K | $0.92 | $0.00 | $4.59 |
| k2p6 | 2 | 80K | 3K | 0 | $0.29 | $0.00 | $1.15 |
| **Total** | **8,818** | **34.6M** | **2.0M** | **381.4M** | **$612.78** | **$2,437.73** | **$794.09** |

_428.0M total tokens processed. 89.1% cache hit rate._

_$3,231.83 total saved ($2,437.73 caching + $794.09 model routing vs all-Opus)._

_Model savings are modest because ~89.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-sonnet-4-6 | 33,013 | 127.8M | 8.5M | 1,799.1M | $1,372.01 | $4,857.66 | $4,209.62 |
| claude-opus-4-7 | 908 | 1K | 721K | 112.9M | $365.43 | $1,524.87 | $0.00 |
| gpt-5.5 | 14,597 | 65.0M | 2.2M | 436.8M | $317.41 | $1,179.44 | $1,437.67 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| k2p6 | 861 | 4.1M | 266K | 99.0M | $46.19 | $267.56 | $184.77 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| k2p7 | 194 | 1.1M | 98K | 20.1M | $10.85 | $54.43 | $43.39 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| kimi-k2.7-code-highspeed | 25 | 90K | 24K | 954K | $0.92 | $0.00 | $4.59 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **68,825** | **399.3M** | **18.9M** | **4,758.6M** | **$9,198.40** | **$33,975.57** | **$7,504.25** |

_5,367.8M total tokens processed. 88.7% cache hit rate._

_$41,479.82 total saved ($33,975.57 caching + $7,504.25 model routing vs all-Opus)._

_Model savings are modest because ~88.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-07 16:59 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
