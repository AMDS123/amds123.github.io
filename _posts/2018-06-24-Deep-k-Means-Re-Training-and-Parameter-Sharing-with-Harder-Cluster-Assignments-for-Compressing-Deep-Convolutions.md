---
layout: post
title: "Deep $k$-Means: Re-Training and Parameter Sharing with Harder Cluster Assignments for Compressing Deep Convolutions"
date: 2018-06-24 22:49:24
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Junru Wu, Yue Wang, Zhenyu Wu, Zhangyang Wang, Ashok Veeraraghavan, Yingyan Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The current trend of pushing CNNs deeper with convolutions has created a pressing demand to achieve higher compression gains on CNNs where convolutions dominate the computation and parameter amount (e.g., GoogLeNet, ResNet and Wide ResNet). Further, the high energy consumption of convolutions limits its deployment on mobile devices. To this end, we proposed a simple yet effective scheme for compressing convolutions though applying k-means clustering on the weights, compression is achieved through weight-sharing, by only recording $K$ cluster centers and weight assignment indexes. We then introduced a novel spectrally relaxed $k$-means regularization, which tends to make hard assignments of convolutional layer weights to $K$ learned cluster centers during re-training. We additionally propose an improved set of metrics to estimate energy consumption of CNN hardware implementations, whose estimation results are verified to be consistent with previously proposed energy estimation tool extrapolated from actual hardware measurements. We finally evaluated Deep $k$-Means across several CNN models in terms of both compression ratio and energy consumption reduction, observing promising results without incurring accuracy loss. The code is available at https://github.com/Sandbox3aster/Deep-K-Means

##### Abstract (translated by Google)
当前CNNs卷积更深的趋势已经产生迫切需求，以在卷积主导计算和参数量的CNN上实现更高的压缩增益（例如，GoogLeNet，ResNet和WideResNet）。此外，卷积的高能耗限制了其在移动设备上的部署。为此，我们提出了一种简单而有效的压缩卷积方案，即通过对权重应用k均值聚类，通过权重共享实现压缩，仅记录$ K $聚类中心和权重分配索引。然后，我们引入了一种新的频谱宽松的$ k $ -means正则化，它倾向于在重新训练期间对$ K $学习的聚类中心进行卷积层权重的硬分配。我们还提出了一套改进的度量标准来估计CNN硬件实现的能耗，其估计结果经过验证与先前提出的从实际硬件测量推断出的能量估算工具一致。我们最终评估了几个CNN模型在压缩比和能耗降低方面的深度$ k $  - 平均值，观察到有希望的结果而不会导致精度损失。该代码可在https://github.com/Sandbox3aster/Deep-K-Means中找到

##### URL
[http://arxiv.org/abs/1806.09228](http://arxiv.org/abs/1806.09228)

##### PDF
[http://arxiv.org/pdf/1806.09228](http://arxiv.org/pdf/1806.09228)

