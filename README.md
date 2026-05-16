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
| User AI session hours | 6.3h | 8.2h | 10.2h | 10.2h |
| AI worker hours | 1.0h | 8.7h | 15.1h | 15.1h |
| AI concurrency hours | 11.6h | 23.1h | 34.5h | 34.5h |
| Interactive sessions | 7 | 16 | 20 | 20 |
| Worker sessions | 18 | 150 | 265 | 265 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,966 | 6K | 2.2M | 732.9M | $2,055.84 | $9,894.97 | $0.00 |
| claude-sonnet-4-6 | 3,626 | 4K | 1.7M | 281.1M | $228.97 | $759.00 | $442.72 |
| gpt-5.5 | 3,408 | 15.3M | 544K | 89.6M | $72.16 | $242.16 | $324.54 |
| k2p6 | 851 | 3.9M | 261K | 98.3M | $45.35 | $265.68 | $181.41 |
| k2p5 | 287 | 1.7M | 111K | 35.7M | $17.66 | $96.51 | $70.66 |
| gpt-5.5-fast | 46 | 421K | 14K | 3.2M | $2.14 | $8.85 | $9.84 |
| gpt-5.4 | 42 | 195K | 18K | 4.0M | $1.88 | $7.62 | $7.20 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| **Total** | **13,285** | **21.8M** | **4.9M** | **1,247.8M** | **$2,425.65** | **$11,279.88** | **$1,042.11** |

_1,348.4M total tokens processed. 92.5% cache hit rate._

_$12,321.99 total saved ($11,279.88 caching + $1,042.11 model routing vs all-Opus)._

_Model savings are modest because ~92.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 12,694 | 115.9M | 4.9M | 1,735.6M | $4,711.56 | $23,430.98 | $0.00 |
| claude-sonnet-4-6 | 29,520 | 128.0M | 7.4M | 1,526.4M | $954.63 | $4,121.30 | $3,818.58 |
| k2p5 | 2,698 | 52.3M | 833K | 189.6M | $226.45 | $512.08 | $905.89 |
| gpt-5-codex | 1,367 | 20.5M | 309K | 123.9M | $103.36 | $334.68 | $413.52 |
| gpt-5.5 | 3,293 | 13.9M | 527K | 86.9M | $75.88 | $234.63 | $303.58 |
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
| **Total** | **52,036** | **350.0M** | **14.9M** | **3,880.3M** | **$6,234.73** | **$29,126.43** | **$5,957.13** |

_4,401.8M total tokens processed. 88.2% cache hit rate._

_$35,083.57 total saved ($29,126.43 caching + $5,957.13 model routing vs all-Opus)._

_Model savings are modest because ~88.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-16 09:34 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
