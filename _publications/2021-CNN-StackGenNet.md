---
title: "A Stacked Generalization of 3D Orthogonal Deep Learning Convolutional Neural Networks for Improved Detection of White Matter Hyperintensities in 3D FLAIR Images"
collection: publications
category: manuscripts
permalink: /publication/2021-CNN-StackGenNet
excerpt: 'Stacked Generalization for WMH segmentation in T2-FLAIR images.'
date: 2021-04-01
venue: 'Am J Neuroradiol'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.ajnr.org/content/42/4/639.full'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Umapathy L, Perez-Carrillo GG, Keerthivasan MB, Rosado-Toro JA, Altbach MI, Winegar B, Weinkauf C, Bilgin A; Alzheimer’s Disease Neuroimaging Initiative. A Stacked Generalization of 3D Orthogonal Deep Learning Convolutional Neural Networks for Improved Detection of White Matter Hyperintensities in 3D FLAIR Images. AJNR Am J Neuroradiol. 2021 Apr;42(4):639-647. doi: 10.3174/ajnr.A6970. Epub 2021 Feb 11. PMID: 33574101; PMCID: PMC8040994.'
---
Background and purpose: Accurate and reliable detection of white matter hyperintensities and their volume quantification can provide valuable clinical information to assess neurologic disease progression. In this work, a stacked generalization ensemble of orthogonal 3D convolutional neural networks, StackGen-Net, is explored for improving automated detection of white matter hyperintensities in 3D T2-FLAIR images.

Materials and methods: Individual convolutional neural networks in StackGen-Net were trained on 2.5D patches from orthogonal reformatting of 3D-FLAIR (n = 21) to yield white matter hyperintensity posteriors. A meta convolutional neural network was trained to learn the functional mapping from orthogonal white matter hyperintensity posteriors to the final white matter hyperintensity prediction. The impact of training data and architecture choices on white matter hyperintensity segmentation performance was systematically evaluated on a test cohort (n = 9). The segmentation performance of StackGen-Net was compared with state-of-the-art convolutional neural network techniques on an independent test cohort from the Alzheimer's Disease Neuroimaging Initiative-3 (n = 20).

Results: StackGen-Net outperformed individual convolutional neural networks in the ensemble and their combination using averaging or majority voting. In a comparison with state-of-the-art white matter hyperintensity segmentation techniques, StackGen-Net achieved a significantly higher Dice score (0.76 [SD, 0.08], F1-lesion (0.74 [SD, 0.13]), and area under precision-recall curve (0.84 [SD, 0.09]), and the lowest absolute volume difference (13.3% [SD, 9.1%]). StackGen-Net performance in Dice scores (median = 0.74) did not significantly differ (P = .22) from interobserver (median = 0.73) variability between 2 experienced neuroradiologists. We found no significant difference (P = .15) in white matter hyperintensity lesion volumes from StackGen-Net predictions and ground truth annotations.

Conclusions: A stacked generalization of convolutional neural networks, utilizing multiplanar lesion information using 2.5D spatial context, greatly improved the segmentation performance of StackGen-Net compared with traditional ensemble techniques and some state-of-the-art deep learning models for 3D-FLAIR.