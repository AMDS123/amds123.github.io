---
layout: post
title: "Automatic Assessment of Full Left Ventricular Coverage in Cardiac Cine Magnetic Resonance Imaging with Fisher-Discriminative 3D CNN"
date: 2018-11-06 22:07:09
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Detection
author: Le Zhang, Ali Gooya, Marco Pereanez, Bo Dong, Stefan K. Piechnik, Stefan Neubauer, Steffen E. Petersen, Alejandro F. Frangi
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac magnetic resonance (CMR) images play a growing role in the diagnostic imaging of cardiovascular diseases. Full coverage of the left ventricle (LV), from base to apex, is a basic criterion for CMR image quality and necessary for accurate measurement of cardiac volume and functional assessment. Incomplete coverage of the LV is identified through visual inspection, which is time-consuming and usually done retrospectively in the assessment of large imaging cohorts. This paper proposes a novel automatic method for determining LV coverage from CMR images by using Fisher-discriminative three-dimensional (FD3D) convolutional neural networks (CNNs). In contrast to our previous method employing 2D CNNs, this approach utilizes spatial contextual information in CMR volumes, extracts more representative high-level features and enhances the discriminative capacity of the baseline 2D CNN learning framework, thus achieving superior detection accuracy. A two-stage framework is proposed to identify missing basal and apical slices in measurements of CMR volume. First, the FD3D CNN extracts high-level features from the CMR stacks. These image representations are then used to detect the missing basal and apical slices. Compared to the traditional 3D CNN strategy, the proposed FD3D CNN minimizes within-class scatter and maximizes between-class scatter. We performed extensive experiments to validate the proposed method on more than 5,000 independent volumetric CMR scans from the UK Biobank study, achieving low error rates for missing basal/apical slice detection (4.9\%/4.6\%). The proposed method can also be adopted for assessing LV coverage for other types of CMR image data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02688](http://arxiv.org/abs/1811.02688)

##### PDF
[http://arxiv.org/pdf/1811.02688](http://arxiv.org/pdf/1811.02688)

