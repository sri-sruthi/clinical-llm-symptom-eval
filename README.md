# Datasets

This project evaluates open-source large language models for clinical symptom identification using three publicly available clinical text sources.

## 1. Synthea (Synthetic EHR Data)
- Source: https://github.com/synthetichealth/synthea
- Type: Synthetic electronic health records
- Usage: Controlled baseline dataset
- Construction: Clinical narratives were constructed by aggregating encounter context, reasons for visit, and clinically meaningful conditions.
- File: synthea/synthea_clinical_notes.csv
- License: Apache 2.0

The Synthea simulator generated over 21,000 encounters and 13,000 condition records. From this raw synthetic EHR data, a curated subset of encounters was transformed into short clinical narratives to serve as a controlled baseline dataset.

## 2. NBME Clinical Patient Notes
- Source: Kaggle (USMLE Step 2 CS)
- Type: Standardized exam-style clinical notes
- Usage: Primary evaluation dataset
- License: Research and educational use

## 3. MTSamples (Medical Transcriptions)
- Source: Kaggle (CC0)
- Type: Medical transcription text
- Usage: Robustness and stress-test dataset
- License: CC0 (Public Domain)
