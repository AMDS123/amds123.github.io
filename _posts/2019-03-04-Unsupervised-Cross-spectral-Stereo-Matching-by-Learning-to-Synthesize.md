---
layout: post
title: "Unsupervised Cross-spectral Stereo Matching by Learning to Synthesize"
date: 2019-03-04 05:29:00
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Tracking Detection Recognition
author: Mingyang Liang, Xiaoyang Guo, Hongsheng Li, Xiaogang Wang, You Song
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised cross-spectral stereo matching aims at recovering disparity given cross-spectral image pairs without any supervision in the form of ground truth disparity or depth. The estimated depth provides additional information complementary to individual semantic features, which can be helpful for other vision tasks such as tracking, recognition and detection. However, there are large appearance variations between images from different spectral bands, which is a challenge for cross-spectral stereo matching. Existing deep unsupervised stereo matching methods are sensitive to the appearance variations and do not perform well on cross-spectral data. We propose a novel unsupervised cross-spectral stereo matching framework based on image-to-image translation. First, a style adaptation network transforms images across different spectral bands by cycle consistency and adversarial learning, during which appearance variations are minimized. Then, a stereo matching network is trained with image pairs from the same spectra using view reconstruction loss. At last, the estimated disparity is utilized to supervise the spectral-translation network in an end-to-end way. Moreover, a novel style adaptation network F-cycleGAN is proposed to improve the robustness of spectral translation. Our method can tackle appearance variations and enhance the robustness of unsupervised cross-spectral stereo matching. Experimental results show that our method achieves good performance without using depth supervision or explicit semantic information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01078](http://arxiv.org/abs/1903.01078)

##### PDF
[http://arxiv.org/pdf/1903.01078](http://arxiv.org/pdf/1903.01078)

