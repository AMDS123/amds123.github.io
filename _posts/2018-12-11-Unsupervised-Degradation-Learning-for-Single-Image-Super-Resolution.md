---
layout: post
title: "Unsupervised Degradation Learning for Single Image Super-Resolution"
date: 2018-12-11 07:07:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN
author: Tianyu Zhao, Changqing Zhang, Wenqi Ren, Dongwei Ren, Qinghua Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolution Neural Networks (CNN) have achieved significant performance on single image super-resolution (SR) recently. However, existing CNN-based methods use artificially synthetic low-resolution (LR) and high-resolution (HR) image pairs to train networks, which cannot handle real-world cases since the degradation from HR to LR is much more complex than manually designed. To solve this problem, we propose a real-world LR images-guided bi-cycle network for single image super-resolution, in which the bidirectional structural consistency is exploited to train both the degradation and SR reconstruction networks in an unsupervised way. Specifically, we propose a degradation network to model the real-world degradation process from HR to LR via generative adversarial networks, and these generated realistic LR images paired with real-world HR images are exploited for training the SR reconstruction network, forming the first cycle. Then in the second reverse cycle, consistency of real-world LR images are exploited to further stabilize the training of SR reconstruction and degradation networks. Extensive experiments on both synthetic and real-world images demonstrate that the proposed algorithm performs favorably against state-of-the-art single image SR methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04240](http://arxiv.org/abs/1812.04240)

##### PDF
[http://arxiv.org/pdf/1812.04240](http://arxiv.org/pdf/1812.04240)

