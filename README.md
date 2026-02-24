# Clinical LLM Symptom Evaluation

This repository contains the code, outputs, and reproducibility assets for our clinical symptom extraction study using open-weight LLMs.

## Study Summary

- Task: symptom extraction from clinical text
- Models: Mistral-7B-Instruct, BioMistral-7B, Qwen2.5-7B-Instruct, Gemma-2B-IT
- Design: cross-dataset 2x2 evaluation (dataset type x matching strictness)
- Datasets:
  - NBME clinical patient notes (primary benchmark)
  - Synthea-derived synthetic notes (controlled synthetic benchmark)
  - MTSamples transcripts (real-world stress test, qualitative robustness)

## Repository Contents

- `notebooks/NLP Code Implementation Notebooks/`
  - Main inference and evaluation notebooks used in the paper.
- `cross_dataset_2_by_2_results_selected/`
  - Main manuscript 2x2 outputs (tables, stats, figures).
- `nbme_results_selected/`
  - NBME result files used across multimedia appendices.
- `synthea_results_selected/`
  - Synthea evaluation outputs.
- `mtsamples_results_selected/`
  - MTSamples qualitative error-analysis outputs.
- `data/synthea/`
  - Synthea source and derived artifacts used in manuscript analyses.
- `data/mtsamples/mtsamples_predictions/`
  - Model predictions on MTSamples.
- `REPRODUCIBILITY.md`
  - Exact map from manuscript/appendix claims to source files.
- `requirements.txt`
  - Python packages used in the notebook pipeline.

## Data Sources

### Synthea
- Source: https://github.com/synthetichealth/synthea
- Type: synthetic EHR data
- License: Apache 2.0

### NBME Clinical Patient Notes
- Source: Kaggle competition (USMLE Step 2 CS): https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes/data
- Type: standardized exam-style clinical notes
- License: research/competition terms (restricted)

### MTSamples
- Source: Kaggle dataset: https://www.kaggle.com/datasets/tboyle10/medicaltranscriptions
- Type: medical transcription text
- License: CC0 (public domain)

## Reproducibility

For manuscript and appendix traceability:

- Start with `REPRODUCIBILITY.md`.
- Use the notebooks in `notebooks/NLP Code Implementation Notebooks/`.
- Use result files from the `*_results_selected/` folders as the canonical outputs.

## Notes on Data Sharing

- NBME raw competition files are license-restricted and should not be redistributed publicly unless allowed by the dataset terms.
- Derived outputs in this repository are provided for reproducibility of reported analyses.
