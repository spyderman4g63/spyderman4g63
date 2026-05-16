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
| User AI session hours | 6.0h | 7.8h | 9.9h | 9.9h |
| AI worker hours | 1.2h | 8.9h | 15.2h | 15.2h |
| AI concurrency hours | 11.1h | 22.5h | 33.8h | 33.8h |
| Interactive sessions | 7 | 16 | 20 | 20 |
| Worker sessions | 19 | 152 | 267 | 267 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,838 | 6K | 2.1M | 699.4M | $2,001.31 | $9,442.05 | $0.00 |
| claude-sonnet-4-6 | 3,626 | 4K | 1.7M | 281.1M | $228.97 | $759.00 | $442.72 |
| gpt-5.5 | 3,345 | 15.0M | 535K | 87.5M | $70.81 | $236.50 | $318.42 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| k2p5 | 287 | 1.7M | 111K | 35.7M | $17.66 | $96.51 | $70.66 |
| gpt-5.5-fast | 46 | 421K | 14K | 3.2M | $2.14 | $8.85 | $9.84 |
| gpt-5.4 | 42 | 195K | 18K | 4.0M | $1.88 | $7.62 | $7.20 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **13,094** | **21.6M** | **4.8M** | **1,212.2M** | **$2,369.77** | **$10,821.29** | **$1,035.99** |

_1,312.3M total tokens processed. 92.4% cache hit rate._

_$11,857.28 total saved ($10,821.29 caching + $1,035.99 model routing vs all-Opus)._

_Model savings are modest because ~92.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,566 | 115.9M | 4.8M | 1,702.0M | $4,658.67 | $22,978.06 | $0.00 |
| claude-sonnet-4-6 | 29,520 | 128.0M | 7.4M | 1,526.4M | $954.63 | $4,121.30 | $3,818.58 |
| k2p5 | 2,698 | 52.3M | 833K | 189.6M | $226.45 | $512.08 | $905.89 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.5 | 3,240 | 13.7M | 520K | 85.1M | $74.60 | $229.86 | $298.45 |
| gpt-5.4 | 690 | 9.0M | 231K | 61.0M | $62.98 | $114.39 | $181.23 |
| k2p6 | 853 | 3.9M | 261K | 98.3M | $45.33 | $265.68 | $181.41 |
| gpt-5.3-codex | 353 | 2.5M | 132K | 29.8M | $26.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 399 | 2.4M | 189K | 20.0M | $20.66 | $37.68 | $61.04 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $2.84 | $5.09 | $8.47 |
| gpt-5.5-fast | 46 | 421K | 14K | 3.2M | $2.45 | $8.85 | $9.84 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $1.41 | $3.17 | $3.43 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.40 | $0.00 | $1.63 |
| qwen3.6-plus-free | 18 | 90 | 3K | 713K | $0.25 | $1.93 | $1.04 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.06 | $0.00 | $0.28 |
| **Total** | **51,855** | **349.8M** | **14.9M** | **3,844.9M** | **$6,180.56** | **$28,668.73** | **$5,952.00** |

_4,366.2M total tokens processed. 88.1% cache hit rate._

_$34,620.74 total saved ($28,668.73 caching + $5,952.00 model routing vs all-Opus)._

_Model savings are modest because ~88.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-16 02:26 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
