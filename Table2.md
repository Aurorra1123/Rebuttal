| Metric | 1K Trajectories | 2K Trajectories | Delta |
|--------|----------------|----------------|-------|
| Overall Accuracy | 56.4% (93/165) | 68.3% (112/164) | +11.9pp |
| Level 1 | 69.8% (37/53) | 79.2% (42/53) | +9.4pp |
| Level 2 | 58.1% (50/86) | 68.2% (58/85) | +10.1pp |
| Level 3 | 23.1% (6/26) | 46.2% (12/26) | +23.1pp |
| Avg Attempts | 5.05 | 4.62 | -0.43 |
| Avg Cost / Task | $0.85 | $0.68 | -$0.17 |

Table 2. Effect of training trajectory scale (1K vs. 2K) on accuracy, efficiency, and cost. More trajectories consistently improve performance across all levels while reducing inference attempts and cost.