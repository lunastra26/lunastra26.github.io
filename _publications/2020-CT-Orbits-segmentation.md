---
title: "Fully Automated detection of Globes for Volume Quantification in CT Orbits Images Using Deep Learning"
collection: publications
category: manuscripts
permalink: /publication/2020-CT-Orbits-segmentation
excerpt: 'Deep learning based segmentation for orbits in CT images.'
date: 2009-10-01
venue: 'Am J Neuroradiol'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.ajnr.org/content/41/6/1061'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Umapathy L, Winegar B, MacKinnon L, Hill M, Altbach MI, Miller JM, Bilgin A. Fully Automated Segmentation of Globes for Volume Quantification in CT Images of Orbits using Deep Learning. AJNR Am J Neuroradiol. 2020 Jun;41(6):1061-1069. doi: 10.3174/ajnr.A6538. Epub 2020 May 21. PMID: 32439637; PMCID: PMC7342761.'
---
BACKGROUND AND PURPOSE: Fast and accurate quantification of globe volumes in the event of an ocular trauma can provide clinicians with valuable diagnostic information. In this work, an automated workflow using a deep learning-based convolutional neural network is proposed for prediction of globe contours and their subsequent volume quantification in CT images of the orbits.

MATERIALS AND METHODS: An automated workflow using a deep learning -based convolutional neural network is proposed for prediction of globe contours in CT images of the orbits. The network, 2D Modified Residual UNET (MRes-UNET2D), was trained on axial CT images from 80 subjects with no imaging or clinical findings of globe injuries. The predicted globe contours and volume estimates were compared with manual annotations by experienced observers on 2 different test cohorts.

RESULTS: On the first test cohort (n = 18), the average Dice, precision, and recall scores were 0.95, 96%, and 95%, respectively. The average 95% Hausdorff distance was only 1.5 mm, with a 5.3% error in globe volume estimates. No statistically significant differences (P = .72) were observed in the median globe volume estimates from our model and the ground truth. On the second test cohort (n = 9) in which a neuroradiologist and 2 residents independently marked the globe contours, MRes-UNET2D (Dice = 0.95) approached human interobserver variability (Dice = 0.94). We also demonstrated the utility of inter-globe volume difference as a quantitative marker for trauma in 3 subjects with known globe injuries.

CONCLUSIONS: We showed that with fast prediction times, we can reliably detect and quantify globe volumes in CT images of the orbits across a variety of acquisition parameters.
