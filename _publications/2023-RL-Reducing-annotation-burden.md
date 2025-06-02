---
title: "Reducing annotation burden in MR: A novel MR-contrast guided contrastive learning approach for image segmentation"
collection: publications
category: manuscripts
permalink: /publication/2023-RL-Reducing-annotation-burden
excerpt: 'Multi-contrast contrastive learning for MR segmentation'
date: 2023-11-01
venue: 'Med Physics'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://pmc.ncbi.nlm.nih.gov/articles/PMC10994772/'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Umapathy L, Brown T, Mushtaq R, Greenhill M, Lu J, Martin D, Altbach M, Bilgin A. Reducing annotation burden in MR: A novel MR-contrast guided contrastive learning approach for image segmentation. Med Phys. 2024 Apr;51(4):2707-2720. doi: 10.1002/mp.16820. Epub 2023 Nov 13. PMID: 37956263; PMCID: PMC10994772.'
---
Background:
Contrastive learning, a successful form of representational learning, has shown promising results in pretraining deep learning (DL) models for downstream tasks. When working with limited annotation data, as in medical image segmentation tasks, learning domain-specific local representations can further improve the performance of DL models.

Purpose:
In this work, we extend the contrastive learning framework to utilize domain-specific contrast information from unlabeled Magnetic Resonance (MR) images to improve the performance of downstream MR image segmentation tasks in the presence of limited labeled data.

Methods:
The contrast in MR images is controlled by underlying tissue properties (e.g., T1 or T2) and image acquisition parameters. We hypothesize that learning to discriminate local representations based on underlying tissue properties should improve subsequent segmentation tasks on MR images. We propose a novel constrained contrastive learning (CCL) strategy that uses tissue-specific information via a constraint map to define positive and negative local neighborhoods for contrastive learning, embedding this information in the representational space during pretraining. For a given MR contrast image, the proposed strategy uses local signal characteristics (constraint map) across a set of related multi-contrast MR images as a surrogate for underlying tissue information.

We demonstrate the utility of the approach for downstream: a) multi-organ segmentation tasks in T2-weighted images where a DL model learns T2 information with constraint maps from a set of 2D multi-echo T2-weighted images (n=101) and b) tumor segmentation tasks in multi-parametric images from the public brain tumor segmentation (BraTS) (n=80) dataset where DL models learn T1 and T2 information from multi-parametric BraTS images. Performance is evaluated on downstream multi-label segmentation tasks with limited data in a) T2-weighted images of abdomen from an in-house Radial-T2 (Train/Test=30/20), b) public Cartesian-T2 (Train/Test=6/12) dataset, and c) multi-parametric MR images from the public brain tumor segmentation dataset (BraTS) (Train/Test=40/50).

The performance of the proposed CCL strategy is compared to state-of-the-art self-supervised contrastive learning techniques. In each task, a model is also trained using all available labeled data for supervised baseline performance.

Results:
The proposed CCL strategy consistently yielded improved Dice scores, Precision, and Recall metrics, and reduced HD95 values across all segmentation tasks. We also observed performance comparable to baseline with reduced annotation effort. The t-SNE visualization of features for T2-weighted images demonstrates its ability to embed T2 information in the representational space. On the BraTS dataset, we also observed that using an appropriate multi-contrast space to learn T1+T2, T1, or T2 information during pretraining further improved the performance of tumor segmentation tasks.

Conclusions:
Learning to embed tissue-specific information that controls MR image contrast with the proposed constrained contrastive learning improved the performance of DL models on subsequent segmentation tasks compared to conventional self-supervised contrastive learning techniques. The use of such domain-specific local representations could help understand, improve performance, and mitigate the scarcity of labeled data in MR image segmentation tasks.