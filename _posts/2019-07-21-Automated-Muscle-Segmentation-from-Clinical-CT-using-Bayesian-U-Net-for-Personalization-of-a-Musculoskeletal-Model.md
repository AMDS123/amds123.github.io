---
layout: post
title: "Automated Muscle Segmentation from Clinical CT using Bayesian U-Net for Personalization of a Musculoskeletal Model"
date: 2019-07-21 05:04:16
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Face CNN Quantitative Relation
author: Yuta Hiasa, Yoshito Otake, Masaki Takao, Takeshi Ogawa, Nobuhiko Sugano, Yoshinobu Sato
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for automatic segmentation of individual muscles from a clinical CT. The method uses Bayesian convolutional neural networks with the U-Net architecture, using Monte Carlo dropout that infers an uncertainty metric in addition to the segmentation label. We evaluated the performance of the proposed method using two data sets: 20 fully annotated CTs of the hip and thigh regions and 18 partially annotated CTs that are publicly available from The Cancer Imaging Archive (TCIA) database. The experiments showed a Dice coefficient (DC) of 0.891 +/- 0.016 (mean +/- std) and an average symmetric surface distance (ASD) of 0.994 +/- 0.230 mm over 19 muscles in the set of 20 CTs. These results were statistically significant improvements compared to the state-of-the-art hierarchical multi-atlas method which resulted in 0.845 +/- 0.031 DC and 1.556 +/- 0.444 mm ASD. We evaluated validity of the uncertainty metric in the multi-class organ segmentation problem and demonstrated a correlation between the pixels with high uncertainty and the segmentation failure. One application of the uncertainty metric in active-learning is demonstrated, and the proposed query pixel selection method considerably reduced the manual annotation cost for expanding the training data set. The proposed method allows an accurate patient-specific analysis of individual muscle shapes in a clinical routine. This would open up various applications including personalization of biomechanical simulation and quantitative evaluation of muscle atrophy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08915](http://arxiv.org/abs/1907.08915)

##### PDF
[http://arxiv.org/pdf/1907.08915](http://arxiv.org/pdf/1907.08915)

