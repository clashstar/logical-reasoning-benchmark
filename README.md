# Logical Reasoning Benchmark Experiments and Analysis

## Overview

This upload contains the code, configuration templates, result summaries, and analysis artifacts used to evaluate models on the logical reasoning benchmark.

The experiments compare:

- A from-scratch transformer trained with standard binary cross-entropy.
- The same transformer trained with an auxiliary matched-pair ranking objective.
- A shuffled-pair ablation.
- Pretrained encoder controls.

## Directory Structure

```text
code/
  run_final_experiments.py
  run_additional_seeds.py
  aggregate_paper_metrics.py
  run_shallow_baselines.py

results/
  paper_metrics.xlsx
  seed_averages.csv
  ablation_stats.csv
  results_section_draft.md

figures/
  mean_accuracy_symbolic.png
  mean_accuracy_controlled.png
  mean_accuracy_natural.png
  pair_aux_difficulty_symbolic.png
  pair_aux_difficulty_controlled.png
  pair_aux_difficulty_natural.png

documentation/
  reproducibility.md
  analysis_plan.md
```

## Author

Yash Baligar

## License

Code is released under the MIT License. Result tables and figures may be reused with attribution.
