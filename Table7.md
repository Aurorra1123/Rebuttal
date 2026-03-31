Rebuttal Table 7. Factorized ablation on GAIA (a randomly sampled 50-task subset) with Gemini-3-Flash-Preview. The full AOrchestra dynamically generates the entire four-tuple `(I, C, T, M)`; each ablation weakens one dimension while keeping the others unchanged.

| Setting | I | C | T | M | Acc. | Δ vs Full (I,C,T,M) |
| --- | --- | --- | --- | --- | ---: | ---: |
| Baseline (no orchestration) | - | - | - | fixed | 60.0% | -24.0 |
| AOrchestra w/o context curation | dynamic | raw full-context | dynamic | fixed | 84.0% | 0.0 |
| AOrchestra w/o tool selection | dynamic | dynamic curated | all tools | fixed | 80.0% | -4.0 |
| AOrchestra full (I, C, T) | dynamic | dynamic curated | dynamic selected | fixed | 92.0% | +8.0 |
| AOrchestra full (I, C, T, M) | dynamic | dynamic curated | dynamic selected | dynamic | 84.0% | - |
