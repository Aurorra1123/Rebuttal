| Sub-Agent Style | Baseline (Standalone) | AOrchestra (Plug-in) | Δ |
|-----------------|----------------------|---------------------|-----|
| ReAct | 28.57 | 52.86 | +24.29 |
| Mini-SWE-Agent | 34.29 | 44.29 | +10.00 |
| Claude Code | 32.86 | 41.43 | +8.57 |

Table 1. Results on TerminalBench with Gemini-3-Flash-Preview high reasoning effort as the backbone model. "Baseline" runs each agent standalone; "AOrchestra" plugs the same agent as a sub-agent into AOrchestra's orchestration layer without any modification to the agent itself. Δ denotes absolute accuracy improvement.