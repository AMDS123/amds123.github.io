---
layout: post
title: "Degenerative Adversarial NeuroImage Nets: Generating Images that Mimic Disease Progression"
date: 2019-07-05 12:11:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Image_Generation Deep_Learning Prediction Quantitative
author: Daniele Ravi, Daniel C. Alexander, Neil P. Oxtoby
mathjax: true
---

* content
{:toc}

##### Abstract
Simulating images representative of neurodegenerative diseases is important for predicting patient outcomes and for validation of computational models of disease progression. This capability is valuable for secondary prevention clinical trials where outcomes and screening criteria involve neuroimaging. Traditional computational methods are limited by imposing a parametric model for atrophy and are extremely resource-demanding. Recent advances in deep learning have yielded data-driven models for longitudinal studies (e.g., face ageing) that are capable of generating synthetic images in real-time. Similar solutions can be used to model trajectories of atrophy in the brain, although new challenges need to be addressed to ensure accurate disease progression modelling. Here we propose Degenerative Adversarial NeuroImage Net (DaniNet) --- a new deep learning approach that learns to emulate the effect of neurodegeneration on MRI. DaniNet uses an underlying set of Support Vector Regressors (SVRs) trained to capture the patterns of regional intensity changes that accompany disease progression. DaniNet produces whole output images, consisting of 2D-MRI slices that are constrained to match regional predictions from the SVRs. DaniNet is also able to condition the progression on non-imaging characteristics (age, diagnosis, etc.) while it maintains the unique brain morphology of individuals. Adversarial training ensures realistic brain images and smooth temporal progression. We train our model using 9652 T1-weighted (longitudinal) MRI extracted from the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset. We perform quantitative and qualitative evaluations on a separate test set of 1283 images (also from ADNI) demonstrating the ability of DaniNet to produce accurate and convincing synthetic images that emulate disease progression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02787](http://arxiv.org/abs/1907.02787)

##### PDF
[http://arxiv.org/pdf/1907.02787](http://arxiv.org/pdf/1907.02787)

