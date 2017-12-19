---
layout: post
title: "moco: Fast Motion Correction for Calcium Imaging"
date: 2015-06-19 15:03:13
categories: arXiv_CV
tags: arXiv_CV Detection
author: Alexander Dubbs, James Guevara, Darcy S. Peterka, Rafael Yuste
mathjax: true
---

* content
{:toc}

##### Abstract
Motion correction is the first in a pipeline of algorithms to analyze calcium imaging videos and extract biologically relevant information, for example the network structure of the neurons therein. Fast motion correction would be especially critical for closed-loop activity triggered stimulation experiments, where accurate detection and targeting of specific cells in necessary. Our algorithm uses a Fourier-transform approach, and its efficiency derives from a combination of judicious downsampling and the accelerated computation of many $L_2$ norms using dynamic programming and two-dimensional, fft-accelerated convolutions. Its accuracy is comparable to that of established community-used algorithms, and it is more stable to large translational motions. It is programmed in Java and is compatible with ImageJ.

##### Abstract (translated by Google)
运动校正是分析钙成像视频并提取生物相关信息（例如其中的神经元的网络结构）的算法流水线中的第一个。快速运动校正对闭环活动触发的刺激实验来说尤其重要，在这些实验中，需要精确检测和锁定特定细胞。我们的算法使用傅里叶变换方法，其效率来自明智的下采样和使用动态编程和二维fft加速卷积的许多$ L_2 $标准的加速计算的组合。其准确度与已建立的社区使用的算法相当，并且对大的平移运动更为稳定。它在Java中编程并与ImageJ兼容。

##### URL
[https://arxiv.org/abs/1506.06039](https://arxiv.org/abs/1506.06039)

##### PDF
[https://arxiv.org/pdf/1506.06039](https://arxiv.org/pdf/1506.06039)

