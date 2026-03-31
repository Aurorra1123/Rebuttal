| Sub-Agent Model | AOrchestra Acc | Baseline Acc | Δ (pp) | Avg Delegation Calls | AOrchestra Tokens (est.) | Baseline Tokens | Token Overhead | AOrchestra Latency (s) | Baseline Latency (s) |
|----------------|---------------|-------------|--------|---------------------|------------------------|----------------|---------------|----------------------|---------------------|
| Gemini-3-Flash | 80.00% | 49.09% | +30.9 | 3.39 | 773K | 242K | 2.2x | – | 446 |
| DeepSeek-v3.2 | 67.87% | 46.70% | +21.2 | 3.61 | 346K | 91K | 2.8x | 1422 | – |
| Claude-4-5-Haiku | 60.61% | 47.88% | +12.7 | 5.01 | 200K | 41K | 3.9x | 584 | 123 |
| Claude-4-5-Sonnet | 71.52% | 53.93% | +17.6 | 3.36 | 262K | 48K | 4.4x | 972 | 134 |
| GPT-5-Mini | 67.27% | 54.55% | +12.7 | 4.52 | 619K | 110K | 4.8x | 2611 | 357 |

**Table 4.** Orchestration overhead on GAIA (165 tasks). The orchestrator uses Gemini-3-Flash-Preview; sub-agent model varies by row. Token values are estimates derived from cost. Latency entries marked "–" indicate missing timestamps in the source data.
