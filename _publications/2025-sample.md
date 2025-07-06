---
title: "Leveraging Representation Learning for Biparametric Prostate MRI to Disambiguate PIRADS 3 and Improve Biopsy Decision Strategies"
collection: publications
category: manuscripts
permalink: /publication/2025-sample
excerpt: 'Representation learning for prostate MRI'
date: 2025-06-30
venue: 'Investigative Radiology'
paperurl: 'https://pubmed.ncbi.nlm.nih.gov/40586610'
citation: 'Umapathy, Lavanya; Johnson, Patricia M; Dutt, Tarun; Tong, Angela; Chopra, Sumit; Sodickson, Daniel K; Chandarana, Hersh. Leveraging Representation Learning for Biparametric Prostate MRI to Disambiguate PIRADS3 and Improve Biopsy Decision Strategies. Investigative Radiology. 2025.'
---
Background
MRI plays a critical role in prostate cancer (PCa) detection and management. Bi-parametric MRI (bpMRI) offers a faster, contrast-free alternative to multi-parametric MRI (mpMRI). Routine use of mpMRI for all patients may not be necessary, and a tailored imaging approach (bpMRI or mpMRI) based on individual risk might optimize resource utilization. Purpose:To develop and evaluate a deep learning (DL) model for classifying clinically significant PCa (csPCa) using bpMRI and to assess its potential for optimizing MRI protocol selection by recommending the additional sequences of mpMRI only when beneficial.

Study Type
Retrospective and prospective.

Population
The DL model was trained and validated on 26,129 prostate MRI studies. A retrospective cohort of 151 patients (mean age 65 ± 8) with ground-truth verification from biopsy, prostatectomy, or long-term follow-up, alongside a prospective cohort of 142 treatment-naïve patients (mean age 65 ± 9) undergoing bpMRI, was evaluated.

Field Strength/Sequence
3 T, Turbo-spin echo T2-weighted imaging (T2WI) and single shot EPI diffusion-weighted imaging (DWI).

Assessment
The DL model, based on a 3D ResNet-50 architecture, classified csPCa using PI-RADS ≥ 3 and Gleason ≥ 7 as outcome measures. The model was evaluated on a prospective cohort labeled by consensus of three radiologists and a retrospective cohort with ground truth verification based on biopsy or long-term follow-up. Real-time inference was tested on an automated MRI workflow, providing classification results directly at the scanner.

Statistical Tests
AUROC with 95% confidence intervals (CI) was used to evaluate model performance.

Results
In the prospective cohort, the model achieved an AUC of 0.83 (95% CI: 0.77–0.89) for PI-RADS ≥ 3 classification, with 93% sensitivity and 54% specificity. In the retrospective cohort, the model achieved an AUC of 0.86 (95% CI: 0.80–0.91) for Gleason ≥ 7 classification, with 93% sensitivity and 62% specificity. Real-time implementation demonstrated a processing latency of 14–16 s for protocol recommendations.

Data Conclusion
The proposed DL model identifies csPCa using bpMRI and integrates it into clinical workflows.
