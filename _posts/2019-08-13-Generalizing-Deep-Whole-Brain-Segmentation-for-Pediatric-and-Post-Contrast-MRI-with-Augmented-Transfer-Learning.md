---
layout: post
title: "Generalizing Deep Whole Brain Segmentation for Pediatric and Post-Contrast MRI with Augmented Transfer Learning"
date: 2019-08-13 15:27:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Transfer_Learning
author: Camilo Bermudez, Justin Blaber, Samuel W. Remedios, Jess E. Reynolds, Catherine Lebel, Maureen McHugo, Stephan Heckers, Yuankai Huo, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Generalizability is an important problem in deep neural networks, especially in the context of the variability of data acquisition in clinical magnetic resonance imaging (MRI). Recently, the Spatially Localized Atlas Network Tiles (SLANT) approach has been shown to effectively segment whole brain non-contrast T1w MRI with 132 volumetric labels. Enhancing generalizability of SLANT would enable broader application of volumetric assessment in multi-site studies. Transfer learning (TL) is commonly used to update the neural network weights for local factors; yet, it is commonly recognized to risk degradation of performance on the original validation/test cohorts. Here, we explore TL by data augmentation to address these concerns in the context of adapting SLANT to anatomical variation and scanning protocol. We consider two datasets: First, we optimize for age with 30 T1w MRI of young children with manually corrected volumetric labels, and accuracy of automated segmentation defined relative to the manually provided truth. Second, we optimize for acquisition with 36 paired datasets of pre- and post-contrast clinically acquired T1w MRI, and accuracy of the post-contrast segmentations assessed relative to the pre-contrast automated assessment. For both studies, we augment the original TL step of SLANT with either only the new data or with both original and new data. Over baseline SLANT, both approaches yielded significantly improved performance (signed rank tests; pediatric: 0.89 vs. 0.82 DSC, p&lt;0.001; contrast: 0.80 vs 0.76, p&lt;0.001). The performance on the original test set decreased with the new-data only transfer learning approach, so data augmentation was superior to strict transfer learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04702](http://arxiv.org/abs/1908.04702)

##### PDF
[http://arxiv.org/pdf/1908.04702](http://arxiv.org/pdf/1908.04702)

