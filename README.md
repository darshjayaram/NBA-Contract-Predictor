# Sports Contract Predictor Summary

What
- A data-driven project to predict player performance and estimate contract value for professional players (primary focus: NBA; includes a Baseball folder with a parallel pipeline).

**Why**
- To quantify player value, reveal market inefficiencies, and support roster and salary decisions using reproducible analytics instead of intuition.

**How**
- Collects and cleans historical stats and salary data from public sources.
- Uses SQL and pandas for feature engineering (season-level, rolling windows, derived metrics).
- Trains and evaluates predictive models (Linear Regression, Random Forest) with cross-validation.
- Provides notebooks, saved models, and scripts to reproduce the pipeline and experiments.

## Scope & main features
- Modular pipelines per sport (NBA core, Baseball directory mirrors the approach).
- End-to-end workflow: data fetch → clean → feature engineering → model training → evaluation.
- Configurable scripts, example configs, and lightweight SQLite support for reproducible queries.
- Notebooks for EDA and model analysis; model artifacts


