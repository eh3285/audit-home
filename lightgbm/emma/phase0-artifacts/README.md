| Files | Description |
| --- | --- |
| `audit_oof_with_raw_attributes.csv` | Connects predictions, outcomes, and raw demographic/contextual attributes |
| `baseline_metrics.json` | Final AUC, PR-AUC, calibration metrics, and hyperparameters |
| `category_codebook.json` | Documents categorical encoding |
| `environment.json` | Records package versions and random seed |
| `feature_missingness.csv` | Records missing-data patterns |
| `feature_schema.json` | Exact 486 model features and their ordering |
| `fold_metrics.csv` | Performance for each validation fold |
| `lightgbm_fold_01.txt`, `lightgbm_fold_02.txt`, `lightgbm_fold_03.txt`, `lightgbm_fold_04.txt`, `lightgbm_fold_05.txt` | Saved trained models  |
| `oof_predictions.csv` | Allows teammates to reproduce metrics and conduct subgroup analysis |
| `phase0_run_complete.json` | Confirms successful completion of the baseline experiment |
| `raw_file_inventory.csv` | Documents the original input datasets |
| `raw_population_summary.json` | Documents the population and target distribution |
