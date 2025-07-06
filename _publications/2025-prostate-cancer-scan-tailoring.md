---
title: "Prostate Cancer Risk Stratification and Scan Tailoring Using Deep Learning on Abbreviated Prostate MRI"
collection: publications
category: manuscripts
permalink: /publication/2025-prostate-cancer-scan-tailoring
excerpt: 'Intelligent scanning for prostate MRI'
date: 20235-04-22
venue: 'JMRI'
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/jmri.29798'
citation: 'Johnson, P.M., Dutt, T., Ginocchio, L.A., Saimbhi, A.S., Umapathy, L., Block, K.T., Sodickson, D.K., Chopra, S., Tong, A. and Chandarana, H. (2025), Prostate Cancer Risk Stratification and Scan Tailoring Using Deep Learning on Abbreviated Prostate MRI. J Magn Reson Imaging. https://doi.org/10.1002/jmri.29798'
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
