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

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 24h | 158.9h | 455.4h | ~6023h* |
| Interactive human attention | 0.0h | 4.6h | 14.7h | 120.2h |
| Interactive AI generation | 0.0h | 5.1h | 22.5h | 160.1h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 2.9h | 18.2h | 60.1h | 331.8h |
| Additive observed work | 2.9h | 27.9h | 97.4h | 612.2h |
| Interactive sessions | 0 | 6 | 27 | 442 |
| Worker sessions | 91 | 350 | 818 | 4,495 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 138 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 2,948 | 4K | 2.1M | 469.2M | $1,302.58 | $6,335.47 | $0.00 |
| gpt-5.6-sol | 9,524 | 34.2M | 1.2M | 399.0M | $432.70 | $1,077.34 | $963.25 |
| gpt-5.5 | 1,024 | 5.9M | 202K | 77.9M | $38.60 | $210.56 | $177.68 |
| k3 | 165 | 797K | 76K | 17.6M | $8.83 | $47.55 | $35.31 |
| claude-sonnet-4-6 | 59 | 65 | 20K | 4.1M | $2.24 | $11.30 | $6.25 |
| gpt-5.6-luna | 37 | 216K | 3K | 958K | $0.35 | $2.59 | $3.95 |
| gpt-5.6-terra | 3 | 132K | 85 | 45K | $0.34 | $0.12 | $1.65 |
| **Total** | **13,760** | **41.3M** | **3.6M** | **969.0M** | **$1,785.64** | **$7,684.92** | **$1,188.09** |

_1,037.7M total tokens processed. 93.4% cache hit rate._

_$8,873.01 total saved ($7,684.92 caching + $1,188.09 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-opus-4-7 | 3,529 | 6K | 2.6M | 540.3M | $1,549.99 | $7,294.85 | $0.00 |
| claude-sonnet-4-6 | 33,072 | 127.8M | 8.6M | 1,803.3M | $1,374.25 | $4,868.96 | $4,215.87 |
| gpt-5.6-sol | 9,524 | 34.2M | 1.2M | 399.0M | $432.70 | $1,077.34 | $963.25 |
| gpt-5.5 | 15,312 | 69.8M | 2.3M | 505.9M | $349.93 | $1,366.15 | $1,588.17 |
| k2p5 | 2,444 | 47.8M | 790K | 182.3M | $209.98 | $492.29 | $839.91 |
| k2p6 | 861 | 4.1M | 266K | 99.0M | $46.19 | $267.56 | $184.77 |
| gpt-5-codex | 1,366 | 20.5M | 309K | 123.9M | $46.12 | $334.68 | $413.52 |
| gpt-5.4 | 689 | 9.0M | 231K | 61.0M | $41.96 | $114.39 | $181.12 |
| gpt-5.3-codex | 352 | 2.5M | 132K | 29.8M | $24.47 | $55.98 | $67.19 |
| gpt-5.3-codex-spark | 398 | 2.4M | 189K | 20.0M | $24.11 | $37.68 | $61.04 |
| k2p7 | 194 | 1.1M | 98K | 20.1M | $10.85 | $54.43 | $43.39 |
| gpt-5.5-fast | 128 | 2.0M | 51K | 14.3M | $9.57 | $38.84 | $44.49 |
| k3 | 165 | 797K | 76K | 17.6M | $8.83 | $47.55 | $35.31 |
| claude-sonnet-4 | 35 | 76 | 598 | 142K | $5.66 | $0.39 | $0.21 |
| gpt-5.2-codex | 64 | 372K | 22K | 2.7M | $1.09 | $5.09 | $8.47 |
| kimi-k2.7-code-highspeed | 25 | 90K | 24K | 954K | $0.92 | $0.00 | $4.59 |
| gpt-5.4-fast | 37 | 135K | 3K | 1.6M | $0.87 | $3.17 | $3.43 |
| qwen3.6-plus-free | 17 | 90 | 3K | 713K | $0.50 | $1.93 | $1.04 |
| nemotron-3-super-free | 2 | 133K | 485 | 0 | $0.41 | $0.00 | $1.63 |
| gpt-5.6-luna | 37 | 216K | 3K | 958K | $0.35 | $2.59 | $3.95 |
| gpt-5.6-terra | 3 | 132K | 85 | 45K | $0.34 | $0.12 | $1.65 |
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **81,949** | **439.6M** | **22.2M** | **5,677.0M** | **$10,859.94** | **$41,071.16** | **$8,665.17** |

_6,351.4M total tokens processed. 89.4% cache hit rate._

_$49,736.32 total saved ($41,071.16 caching + $8,665.17 model routing vs all-Opus)._

_Model savings are modest because ~89.4% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-05 10:14 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/spyderman4g63?theme=dark" />
    <img alt="spyderman4g63's commit history" src="https://commit-history.com/embed/spyderman4g63" />
  </picture>
</div>
