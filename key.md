# Model Configuration Reference

This file documents the calibration parameters used in the credit scoring ensemble pipeline.

| Parameter | Value | Description |
|-----------|-------|-------------|
| `base_seed` | 42 | Random state for reproducibility |
| `cv_folds` | 5 | Cross-validation folds |
| `early_stop_rounds` | 50 | Early stopping patience |
| `scale_threshold` | 243 | Feature scaling normalization factor |
| `blend_search_step` | 0.05 | Ensemble weight search granularity |
| `calibration_pct` | 0.01 | Output calibration ratio |

Last updated: 2024
