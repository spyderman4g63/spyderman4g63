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
| User AI session hours | 5.4h | 7.2h | 9.3h | 9.3h |
| AI worker hours | 1.1h | 8.9h | 15.1h | 15.1h |
| AI concurrency hours | 9.7h | 21.2h | 32.4h | 32.4h |
| Interactive sessions | 7 | 16 | 20 | 20 |
| Worker sessions | 19 | 152 | 266 | 266 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,657 | 6K | 2.1M | 670.9M | $1,949.32 | $9,057.77 | $0.00 |
| claude-sonnet-4-6 | 3,663 | 4K | 1.7M | 286.2M | $231.30 | $772.95 | $449.61 |
| gpt-5.5 | 3,338 | 15.0M | 534K | 87.3M | $70.63 | $235.91 | $317.61 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| k2p5 | 287 | 1.7M | 111K | 35.7M | $17.66 | $96.51 | $70.66 |
| gpt-5.4 | 42 | 195K | 18K | 4.0M | $1.88 | $7.62 | $7.20 |
| gpt-5.5-fast | 43 | 304K | 10K | 3.0M | $1.74 | $8.29 | $7.97 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **12,940** | **21.4M** | **4.8M** | **1,188.5M** | **$2,319.53** | **$10,449.83** | **$1,040.19** |

_1,288.3M total tokens processed. 92.3% cache hit rate._

_$11,490.02 total saved ($10,449.83 caching + $1,040.19 model routing vs all-Opus)._

_Model savings are modest because ~92.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,386 | 115.9M | 4.8M | 1,673.6M | $4,612.55 | $22,593.79 | $0.00 |
| claude-sonnet-4-6 | 29,520 | 128.0M | 7.4M | 1,526.4M | $954.63 | $4,121.30 | $3,818.58 |
| k2p5 | 2,698 | 52.3M | 833K | 189.6M | $226.45 | $512.08 | $905.89 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.5 | 3,233 | 13.7M | 519K | 84.9M | $74.40 | $229.27 | $297.63 |
| gpt-5.4 | 690 | 9.0M | 231K | 61.0M | $62.98 | $114.39 | $181.23 |
| k2p6 | 853 | 3.9M | 261K | 98.3M | $45.33 | $265.68 | $181.41 |
| gpt-5.3-codex | 353 | 2.5M | 132K | 29.8M | $26.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 399 | 2.4M | 189K | 20.0M | $20.66 | $37.68 | $61.04 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $2.84 | $5.09 | $8.47 |
| gpt-5.5-fast | 44 | 304K | 10K | 3.0M | $1.98 | $8.29 | $7.97 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $1.41 | $3.17 | $3.43 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.40 | $0.00 | $1.63 |
| qwen3.6-plus-free | 18 | 90 | 3K | 713K | $0.25 | $1.93 | $1.04 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.06 | $0.00 | $0.28 |
| **Total** | **51,666** | **349.6M** | **14.8M** | **3,816.0M** | **$6,133.77** | **$28,283.32** | **$5,949.32** |

_4,336.7M total tokens processed. 88% cache hit rate._

_$34,232.63 total saved ($28,283.32 caching + $5,949.32 model routing vs all-Opus)._

_Model savings are modest because ~88% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-16 01:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
