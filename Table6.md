| Failure Type | # Tasks | % | Avg Delegations | Description |
|---|---:|---:|---:|---|
| Over-delegation | 6 | 12.0% | 9.7 | Orchestrator repeatedly delegates similar sub-tasks without meaningful progress, often continuing near the cap of 10. |
| Wrong decomposition | 9 | 18.0% | 4.8 | Orchestrator decomposes the task in a fundamentally incorrect direction from the first step. |
| Insufficient context | 5 | 10.0% | 6.8 | Sub-task direction is correct, but critical constraints or information are missing from the delegated context. |
| Synthesis / verification failure | 13 | 26.0% | 5.0 | Sub-agents retrieve partially or fully correct information, but the orchestrator fails to properly integrate, reconcile, or verify the results. |
| Tool / retrieval failure | 17 | 34.0% | 8.1 | External tool calls, web extraction, or file parsing fail or return unusable content, breaking the trajectory. |

Table 6. Failure taxonomy on 50 manually annotated failed tasks (sampled across Gemini-3-Flash, Claude-4-5-Haiku, and DeepSeek-v3.2 configurations on GAIA). Each task is assigned a single primary failure type.
