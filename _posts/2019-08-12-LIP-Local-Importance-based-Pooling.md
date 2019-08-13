---
layout: post
title: "LIP: Local Importance-based Pooling"
date: 2019-08-12 14:02:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Ziteng Gao, Limin Wang, Gangshan Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial downsampling layers are favored in convolutional neural networks (CNNs) to downscale feature maps for larger receptive fields and less memory consumption. However, for discriminative tasks, there are possibilities that these layers lose the discriminative details due to improper pooling strategies, which could hinder the learning process and eventually result in suboptimal models. In this paper, we present a unified framework over the existing downsampling layers (e.g., average pooling, max pooling, and strided convolution) from a local importance perspective. In this framework, we analyze the problems of these widely-used pooling layers and figure out the criteria for designing an effective downsampling layer. According to this analysis, we propose a conceptually simple, general, and effective pooling layer based on local importance modeling, termed as Local Importance-based Pooling (LIP). LIP can automatically enhance discriminative features during the downsampling procedure by learning adaptive importance weights based on inputs in an end-to-end manner. Experiment results show that LIP consistently yields notable gains with different depths and different architectures on ImageNet classification. In the challenging MS COCO dataset, detectors with our LIP-ResNets as backbones obtain a consistent improvement ($\ge 1.4\%$) over plain ResNets, and especially achieve state-of-the-art performance in detecting small objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.04156](https://arxiv.org/abs/1908.04156)

##### PDF
[https://arxiv.org/pdf/1908.04156](https://arxiv.org/pdf/1908.04156)

