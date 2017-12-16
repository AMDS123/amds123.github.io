---
layout: post
title: "Faster Spatially Regularized Correlation Filters for Visual Tracking"
date: 2017-06-01 01:11:57
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Relation
author: Xiaoxiang Hu, Yujiu Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminatively learned correlation filters (DCF) have been widely used in online visual tracking filed due to its simplicity and efficiency. These methods utilize a periodic assumption of the training samples to construct a circulant data matrix, which implicitly increases the training samples and reduces both storage and computational complexity.The periodic assumption also introduces unwanted boundary effects. Recently, Spatially Regularized Correlation Filters (SRDCF) solved this issue by introducing penalization on correlation filter coefficients depending on their spatial location. However, SRDCF's efficiency dramatically decreased due to the breaking of circulant structure. We propose Faster Spatially Regularized Discriminative Correlation Filters (FSRDCF) for tracking. The FSRDCF is constructed from Ridge Regression, the circulant structure of training samples in the spatial domain is fully used, more importantly, we further exploit the circulant structure of regularization function in the Fourier domain, which allows our problem to be solved more directly and efficiently. Experiments are conducted on three benchmark datasets: OTB-2013, OTB-2015 and VOT2016. Our approach achieves equivalent performance to the baseline tracker SRDCF on all three datasets. On OTB-2013 and OTB-2015 datasets, our approach obtains a more than twice faster running speed and a more than third times shorter start-up time than the SRDCF. For state-of-the-art comparison, our approach demonstrates superior performance compared to other non-spatial-regularization trackers.

##### Abstract (translated by Google)
判别式学习相关滤波器（DCF）由于其简单和有效而被广泛用于在线视觉跟踪领域。这些方法利用训练样本的周期性假设来构造循环数据矩阵，这隐含地增加了训练样本并减少了存储和计算的复杂性。周期性假设还引入了不想要的边界效应。最近，空间正则化相关滤波器（SRDCF）通过根据相关滤波器系数的空间位置引入惩罚来解决这个问题。然而，由于循环结构的破坏，SRDCF的效率急剧下降。我们提出更快的空间正则化判别相关滤波器（FSRDCF）进行跟踪。 FSRDCF是由岭回归构造而成，充分利用了空间域训练样本的循环结构，更重要的是进一步利用了傅里叶域正则化函数的循环结构，使得我们的问题得到更为直接有效的解决。在三个基准数据集上进行实验：OTB-2013，OTB-2015和VOT2016。我们的方法在所有三个数据集上实现了与基线跟踪器SRDCF相当的性能。在OTB-2013和OTB-2015数据集上，我们的方法比SRDCF获得的运行速度提高了两倍多，启动时间缩短了三倍以上。对于最先进的比较，我们的方法与其他非空间正则化跟踪器相比表现出优越的性能。

##### URL
[https://arxiv.org/abs/1706.00140](https://arxiv.org/abs/1706.00140)

##### PDF
[https://arxiv.org/pdf/1706.00140](https://arxiv.org/pdf/1706.00140)

