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
| User AI session hours | 4.0h | 8.3h | 10.4h | 10.4h |
| AI worker hours | 0.8h | 8.6h | 14.9h | 14.9h |
| AI concurrency hours | 7.7h | 23.3h | 34.6h | 34.6h |
| Interactive sessions | 3 | 17 | 21 | 21 |
| Worker sessions | 16 | 146 | 263 | 263 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,947 | 6K | 2.2M | 726.9M | $2,041.74 | $9,813.29 | $0.00 |
| claude-sonnet-4-6 | 3,411 | 3K | 1.6M | 256.8M | $214.32 | $693.60 | $409.60 |
| gpt-5.5 | 3,453 | 15.5M | 552K | 91.1M | $73.20 | $246.06 | $329.19 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| k2p5 | 53 | 539K | 30K | 7.5M | $4.34 | $20.44 | $17.36 |
| gpt-5.5-fast | 51 | 546K | 15K | 3.6M | $2.59 | $9.98 | $11.94 |
| gpt-5.4 | 42 | 195K | 18K | 4.0M | $1.88 | $7.62 | $7.20 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **12,867** | **21.0M** | **4.7M** | **1,191.2M** | **$2,385.07** | **$11,061.77** | **$962.44** |

_1,288.7M total tokens processed. 92.4% cache hit rate._

_$12,024.21 total saved ($11,061.77 caching + $962.44 model routing vs all-Opus)._

_Model savings are modest because ~92.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,725 | 115.9M | 4.9M | 1,738.2M | $4,716.31 | $23,466.04 | $0.00 |
| claude-sonnet-4-6 | 29,520 | 128.0M | 7.4M | 1,526.4M | $954.63 | $4,121.30 | $3,818.58 |
| k2p5 | 2,698 | 52.3M | 833K | 189.6M | $226.45 | $512.08 | $905.89 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.5 | 3,338 | 14.1M | 535K | 88.3M | $77.05 | $238.53 | $308.23 |
| gpt-5.4 | 690 | 9.0M | 231K | 61.0M | $62.98 | $114.39 | $181.23 |
| k2p6 | 853 | 3.9M | 261K | 98.3M | $45.33 | $265.68 | $181.41 |
| gpt-5.3-codex | 353 | 2.5M | 132K | 29.8M | $26.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 399 | 2.4M | 189K | 20.0M | $20.66 | $37.68 | $61.04 |
| gpt-5.5-fast | 51 | 546K | 15K | 3.6M | $2.96 | $9.98 | $11.94 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $2.84 | $5.09 | $8.47 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $1.41 | $3.17 | $3.43 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.40 | $0.00 | $1.63 |
| qwen3.6-plus-free | 18 | 90 | 3K | 713K | $0.25 | $1.93 | $1.04 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.06 | $0.00 | $0.28 |
| **Total** | **52,117** | **350.3M** | **14.9M** | **3,884.7M** | **$6,241.16** | **$29,166.53** | **$5,963.89** |

_4,406.8M total tokens processed. 88.2% cache hit rate._

_$35,130.41 total saved ($29,166.53 caching + $5,963.89 model routing vs all-Opus)._

_Model savings are modest because ~88.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-16 20:48 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
