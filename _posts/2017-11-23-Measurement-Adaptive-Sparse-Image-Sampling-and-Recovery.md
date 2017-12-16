---
layout: post
title: "Measurement-Adaptive Sparse Image Sampling and Recovery"
date: 2017-11-23 19:51:17
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Ali Taimori, Farokh Marvasti
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an adaptive and intelligent sparse model for digital image sampling and recovery. In the proposed sampler, we adaptively determine the number of required samples for retrieving image based on space-frequency-gradient information content of image patches. By leveraging texture in space, sparsity locations in DCT domain, and directional decomposition of gradients, the sampler structure consists of a combination of uniform, random, and nonuniform sampling strategies. For reconstruction, we model the recovery problem as a two-state cellular automaton to iteratively restore image with scalable windows from generation to generation. We demonstrate the recovery algorithm quickly converges after a few generations for an image with arbitrary degree of texture. For a given number of measurements, extensive experiments on standard image-sets, infra-red, and mega-pixel range imaging devices show that the proposed measurement matrix considerably increases the overall recovery performance, or equivalently decreases the number of sampled pixels for a specific recovery quality compared to random sampling matrix and Gaussian linear combinations employed by the state-of-the-art compressive sensing methods. In practice, the proposed measurement-adaptive sampling/recovery framework includes various applications from intelligent compressive imaging-based acquisition devices to computer vision and graphics, and image processing technology. Simulation codes are available online for reproduction purposes.

##### Abstract (translated by Google)
本文提出了一种适应性和智能化的稀疏数字图像采样和恢复模型。在所提出的采样器中，我们根据图像块的空间频率梯度信息内容自适应地确定了用于检索图像所需的样本的数量。通过利用空间中的纹理，DCT域中的稀疏位置以及梯度的方向分解，采样器结构由均匀，随机和非均匀采样策略的组合组成。为了重建，我们将恢复问题建模为一个双状态元胞自动机，以迭代方式将图像与可扩展窗口一代一代地恢复。我们演示了恢复算法几代之后迅速收敛的任意程度的纹理图像。对于给定数量的测量，在标准图像集，红外和兆像素范围成像设备上的大量实验表明，所提出的测量矩阵大大地提高了整体恢复性能，或等同地减少了特定采样像素的数量与随机采样矩阵和现有技术的压缩感测方法采用的高斯线性组合相比，恢复质量更高。在实践中，所提出的测量自适应采样/恢复框架包括从基于智能压缩成像的采集设备到计算机视觉和图形以及图像处理技术的各种应用。仿真代码可以在线获得用于复制的目的。

##### URL
[https://arxiv.org/abs/1706.03129](https://arxiv.org/abs/1706.03129)

##### PDF
[https://arxiv.org/pdf/1706.03129](https://arxiv.org/pdf/1706.03129)

