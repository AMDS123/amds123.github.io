---
layout: post
title: "Convolutional Neural Network-based Speech Enhancement for Cochlear Implant Recipients"
date: 2019-07-03 21:25:21
categories: arXiv_SD
tags: arXiv_SD CNN
author: Nursadul Mamun, Soheil Khorram, John H.L. Hansen
mathjax: true
---

* content
{:toc}

##### Abstract
Attempts to develop speech enhancement algorithms with improved speech intelligibility for cochlear implant (CI) users have met with limited success. To improve speech enhancement methods for CI users, we propose to perform speech enhancement in a cochlear filter-bank feature space, a feature-set specifically designed for CI users based on CI auditory stimuli. We leverage a convolutional neural network (CNN) to extract both stationary and non-stationary components of environmental acoustics and speech. We propose three CNN architectures: (1) vanilla CNN that directly generates the enhanced signal; (2) spectral-subtraction-style CNN (SS-CNN) that first predicts noise and then generates the enhanced signal by subtracting noise from the noisy signal; (3) Wiener-style CNN (Wiener-CNN) that generates an optimal mask for suppressing noise. An important problem of the proposed networks is that they introduce considerable delays, which limits their real-time application for CI users. To address this, this study also considers causal variations of these networks. Our experiments show that the proposed networks (both causal and non-causal forms) achieve significant improvement over existing baseline systems. We also found that causal Wiener-CNN outperforms other networks, and leads to the best overall envelope coefficient measure (ECM). The proposed algorithms represent a viable option for implementation on the CCi-MOBILE research platform as a pre-processor for CI users in naturalistic environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02526](http://arxiv.org/abs/1907.02526)

##### PDF
[http://arxiv.org/pdf/1907.02526](http://arxiv.org/pdf/1907.02526)

