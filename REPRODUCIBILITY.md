# Reproducibility Map

This file maps manuscript and appendix outputs to source artifacts in this repository.

## Main Manuscript (2x2 design)
- Primary metrics tables: `cross_dataset_2_by_2_results_selected/table1_master_results_corrected.csv`
- Effect decomposition: `cross_dataset_2_by_2_results_selected/table2_effect_decomposition_corrected.csv`
- Statistical tests: `cross_dataset_2_by_2_results_selected/table3_statistical_tests_corrected.csv`
- Dataset comparison summary: `cross_dataset_2_by_2_results_selected/table4_dataset_comparison_corrected.csv`
- Synthea threshold sensitivity: `cross_dataset_2_by_2_results_selected/synthea_threshold_sensitivity.csv`
- Main manuscript figures: `cross_dataset_2_by_2_results_selected/viz_*.png`

## Appendix 1 (Prompt Template and Settings)
- Inference notebooks:
  - `notebooks/NLP Code Implementation Notebooks/mistral_nbme_inference.ipynb`
  - `notebooks/NLP Code Implementation Notebooks/gemma_nbme_inference.ipynb`
  - `notebooks/NLP Code Implementation Notebooks/qwen_nbme_inference.ipynb`
  - `notebooks/NLP Code Implementation Notebooks/biomistral_nbme_inference.ipynb`
  - `notebooks/NLP Code Implementation Notebooks/synthea-inference.ipynb`
  - `notebooks/NLP Code Implementation Notebooks/mtsamples-inference.ipynb`

## Appendix 3 (Raw vs Post-processing; NBME)
- `nbme_results_selected/nbme_symptom_stats.csv`
- `nbme_results_selected/nbme_empty_stats.csv`
- `nbme_results_selected/nbme_leakage_stats.csv`
- `nbme_results_selected/raw_vs_post_performance.csv`

## Appendix 4 (Threshold Sensitivity; NBME)
- `nbme_results_selected/threshold_sensitivity_analysis.csv`
- `nbme_results_selected/model_performance_summary.csv`
- Figures:
  - `nbme_results_selected/viz_threshold_sensitivity.png`
  - `nbme_results_selected/viz_macro_vs_micro_f1.png`

## Appendix 5 (Error Taxonomy; NBME)
- `nbme_results_selected/nbme_all_errors_corrected.csv`
- `nbme_results_selected/nbme_error_examples_for_paper.csv`
- Figures:
  - `nbme_results_selected/viz_12_error_category_heatmap_corrected.png`
  - `nbme_results_selected/viz_error_categories_small_multiples.png`

## Appendix 6 (Statistical Outputs; NBME)
- `nbme_results_selected/nbme_statistical_tests_corrected.csv`
- `nbme_results_selected/nbme_confidence_intervals.csv`
- Figure: `nbme_results_selected/viz_17_f1_confidence_intervals_corrected.png`

## Synthea and MTSamples Supporting Outputs
- Synthea: `synthea_results_selected/`
- MTSamples: `mtsamples_results_selected/`

## Data Artifacts Used in Manuscript Pipeline
- `data/synthea/synthea_clinical_notes.csv`
- `data/synthea/synthea_clinical_notes_clean.csv`
- `data/synthea/synthea_conditions_capped.csv`
- `data/synthea/synthea_metadata.json`
- `data/mtsamples/mtsamples_predictions/`

## Note on NBME Raw Data
NBME competition data are license-restricted and should not be distributed publicly.
