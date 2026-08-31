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
| Screen time (Mac) | 24h | 167.3h | 595.9h | ~6787h* |
| Interactive human attention | 0.0h | 0.0h | 0.1h | 120.2h |
| Interactive AI generation | 0.0h | 0.0h | 0.7h | 160.2h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 2.9h | 16.9h | 65.2h | 391.1h |
| Additive observed work | 2.9h | 16.9h | 66.0h | 671.5h |
| Interactive sessions | 0 | 0 | 5 | 445 |
| Worker sessions | 86 | 464 | 1,754 | 6,100 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 164 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-terra | 15,083 | 60.8M | 1.7M | 591.8M | $286.23 | $1,598.12 | $1,543.97 |
| gpt-5.6-sol | 3,624 | 14.5M | 496K | 159.4M | $176.19 | $430.46 | $395.36 |
| gpt-5.5 | 191 | 2.8M | 59K | 27.8M | $15.32 | $75.32 | $71.50 |
| **Total** | **18,898** | **78.2M** | **2.2M** | **779.2M** | **$477.74** | **$2,103.90** | **$2,010.83** |

_859.8M total tokens processed. 90.6% cache hit rate._

_$4,114.73 total saved ($2,103.90 caching + $2,010.83 model routing vs all-Opus)._

_Model savings are modest because ~90.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 13,686 | 115.9M | 5.2M | 1,852.3M | $6,720.38 | $25,007.19 | $0.00 |
| claude-opus-4-7 | 3,529 | 6K | 2.6M | 540.3M | $1,549.99 | $7,294.85 | $0.00 |
| claude-sonnet-4-6 | 33,072 | 127.8M | 8.6M | 1,803.3M | $1,374.25 | $4,868.96 | $4,215.87 |
| gpt-5.6-sol | 10,712 | 39.2M | 1.4M | 452.4M | $492.74 | $1,221.66 | $1,098.06 |
| gpt-5.5 | 15,312 | 69.8M | 2.3M | 505.9M | $349.93 | $1,366.15 | $1,588.17 |
| gpt-5.6-terra | 15,086 | 60.9M | 1.7M | 591.9M | $286.51 | $1,598.24 | $1,545.62 |
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
| big-pickle | 5 | 56K | 827 | 228K | $0.28 | $0.00 | $1.26 |
| minimax-m2.5-free | 2 | 35K | 195 | 35K | $0.12 | $0.00 | $0.61 |
| gpt-5.6-luna | 38 | 244K | 3K | 958K | $0.08 | $2.59 | $4.29 |
| registry.ollama.ai/library/qwopus:latest | 2 | 22K | 143 | 0 | $0.07 | $0.00 | $0.28 |
| **Total** | **98,221** | **505.5M** | **24.1M** | **6,322.3M** | **$11,205.88** | **$42,813.60** | **$10,344.28** |

_7,064.5M total tokens processed. 89.5% cache hit rate._

_$53,157.88 total saved ($42,813.60 caching + $10,344.28 model routing vs all-Opus)._

_Model savings are modest because ~89.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[cg_readthedocs](https://github.com/spyderman4g63/cg_readthedocs)** -- No description
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/spyderman4g63)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-31 05:16 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/spyderman4g63?theme=dark" />
    <img alt="spyderman4g63's commit history" src="https://commit-history.com/embed/spyderman4g63" />
  </picture>
</div>
