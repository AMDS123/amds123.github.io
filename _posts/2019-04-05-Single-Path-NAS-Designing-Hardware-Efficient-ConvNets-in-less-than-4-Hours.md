---
layout: post
title: "Single-Path NAS: Designing Hardware-Efficient ConvNets in less than 4 Hours"
date: 2019-04-05 05:49:41
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Dimitrios Stamoulis, Ruizhou Ding, Di Wang, Dimitrios Lymberopoulos, Bodhi Priyantha, Jie Liu, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
Can we automatically design a Convolutional Network (ConvNet) with the highest image classification accuracy under the runtime constraint of a mobile device? Neural architecture search (NAS) has revolutionized the design of hardware-efficient ConvNets by automating this process. However, the NAS problem remains challenging due to the combinatorially large design space, causing a significant searching time (at least 200 GPU-hours). To alleviate this complexity, we propose Single-Path NAS, a novel differentiable NAS method for designing hardware-efficient ConvNets in less than 4 hours. Our contributions are as follows: 1. Single-path search space: Compared to previous differentiable NAS methods, Single-Path NAS uses one single-path over-parameterized ConvNet to encode all architectural decisions with shared convolutional kernel parameters, hence drastically decreasing the number of trainable parameters and the search cost down to few epochs. 2. Hardware-efficient ImageNet classification: Single-Path NAS achieves 74.96% top-1 accuracy on ImageNet with 79ms latency on a Pixel 1 phone, which is state-of-the-art accuracy compared to NAS methods with similar constraints (<80ms). 3. NAS efficiency: Single-Path NAS search cost is only 8 epochs (30 TPU-hours), which is up to 5,000x faster compared to prior work. 4. Reproducibility: Unlike all recent mobile-efficient NAS methods which only release pretrained models, we open-source our entire codebase at: this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02877](https://arxiv.org/abs/1904.02877)

##### PDF
[https://arxiv.org/pdf/1904.02877](https://arxiv.org/pdf/1904.02877)

