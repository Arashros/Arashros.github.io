---
title: "ECG Beat Classification"
collection: portfolio
featured: true
permalink: /portfolio/ecg-arrhythmia-classification/
date: 2026-10-17
excerpt: "Status: In progress. An ECG processing and beat-classification pipeline using MIT-BIH annotations and participant-aware evaluation."
---

**Status: In progress.** This project is being developed to complement structural-MRI analysis with a biomedical signal-processing example. The planned workflow uses annotated ECG recordings, extracts beat-centered waveform windows and RR-interval features, and compares baseline and tree-based classifiers using participant-grouped evaluation.

The implementation and evaluation are still being completed. No performance results are reported here until the full dataset has been processed and the models have run successfully.

**Planned tools:** Python, WFDB, NumPy, SciPy, scikit-learn  
**Dataset:** [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)
