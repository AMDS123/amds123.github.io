---
layout: post
title: "High Frequency Residual Learning for Multi-Scale Image Classification"
date: 2019-05-07 15:47:27
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification
author: Bowen Cheng, Rong Xiao, Jianfeng Wang, Thomas Huang, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel high frequency residual learning framework, which leads to a highly efficient multi-scale network (MSNet) architecture for mobile and embedded vision problems. The architecture utilizes two networks: a low resolution network to efficiently approximate low frequency components and a high resolution network to learn high frequency residuals by reusing the upsampled low resolution features. With a classifier calibration module, MSNet can dynamically allocate computation resources during inference to achieve a better speed and accuracy trade-off. We evaluate our methods on the challenging ImageNet-1k dataset and observe consistent improvements over different base networks. On ResNet-18 and MobileNet with alpha=1.0, MSNet gains 1.5% accuracy over both architectures without increasing computations. On the more efficient MobileNet with alpha=0.25, our method gains 3.8% accuracy with the same amount of computations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02649](https://arxiv.org/abs/1905.02649)

##### PDF
[https://arxiv.org/pdf/1905.02649](https://arxiv.org/pdf/1905.02649)

