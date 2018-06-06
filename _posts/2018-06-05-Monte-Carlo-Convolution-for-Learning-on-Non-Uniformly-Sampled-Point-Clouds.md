---
layout: post
title: "Monte Carlo Convolution for Learning on Non-Uniformly Sampled Point Clouds"
date: 2018-06-05 15:56:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Pedro Hermosilla, Tobias Ritschel, Pere-Pau V&#xe1;zquez, &#xc0;lvar Vinacua, Timo Ropinski
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient and effective method to learn convolutions for non-uniformly sampled point clouds, as they are obtained with modern acquisition techniques. Learning is enabled by four key novelties: first, representing the convolution kernel itself as a multilayer perceptron; second, phrasing convolution as a Monte Carlo integration problem, third, constructing an unstructured Poisson disk hierarchy for pooling, and fourth, using Monte Carlo convolution as pooling and upsampling operation at different resolutions simultaneously. The key idea across all these contributions is to guarantee adequate consideration of the underlying non-uniform sample distribution function from a Monte Carlo perspective. To make the proposed concepts applicable for real-world tasks, we furthermore propose an efficient implementation which significantly reduces the required GPU memory. By employing our method in hierarchical network architectures we can outperform most of the state-of-the-art networks on established point cloud segmentation, classification and normal estimation benchmarks. Furthermore, in contrast to most existing approaches, we can also demonstrate the robustness of our method with respect to sampling variations even when only trained on uniformly sampled models.

##### Abstract (translated by Google)
我们提出了一种高效和有效的方法来学习非均匀采样点云的卷积，因为它们是通过现代采集技术获得的。学习是由四个关键的创新实现的：首先，将卷积核本身表示为多层感知器;第二，作为蒙特卡洛积分问题的措词卷积，第三，构造用于合并的非结构化泊松盘层次结构，以及第四，使用蒙特卡洛卷积作为同时以不同分辨率进行汇集和上采样操作。所有这些贡献的关键思想是保证从蒙特卡罗的角度充分考虑潜在的非均匀样本分布函数。为了使所提出的概念适用于现实世界的任务，我们还提出了一种有效的实现方式，它显着减少了所需的GPU内存。通过在分层网络架构中采用我们的方法，我们可以在建立的点云分割，分类和正常估算基准上超越大多数最先进的网络。此外，与大多数现有方法相比，即使仅在均匀采样模型上进行训练，我们也可以证明我们的方法在采样变化方面的稳健性。

##### URL
[http://arxiv.org/abs/1806.01759](http://arxiv.org/abs/1806.01759)

##### PDF
[http://arxiv.org/pdf/1806.01759](http://arxiv.org/pdf/1806.01759)

