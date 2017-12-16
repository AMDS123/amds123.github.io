---
layout: post
title: "Real-Time Video Super-Resolution with Spatio-Temporal Networks and Motion Compensation"
date: 2017-04-10 11:53:26
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Quantitative Relation
author: Jose Caballero, Christian Ledig, Andrew Aitken, Alejandro Acosta, Johannes Totz, Zehan Wang, Wenzhe Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have enabled accurate image super-resolution in real-time. However, recent attempts to benefit from temporal correlations in video super-resolution have been limited to naive or inefficient architectures. In this paper, we introduce spatio-temporal sub-pixel convolution networks that effectively exploit temporal redundancies and improve reconstruction accuracy while maintaining real-time speed. Specifically, we discuss the use of early fusion, slow fusion and 3D convolutions for the joint processing of multiple consecutive video frames. We also propose a novel joint motion compensation and video super-resolution algorithm that is orders of magnitude more efficient than competing methods, relying on a fast multi-resolution spatial transformer module that is end-to-end trainable. These contributions provide both higher accuracy and temporally more consistent videos, which we confirm qualitatively and quantitatively. Relative to single-frame models, spatio-temporal networks can either reduce the computational cost by 30% whilst maintaining the same quality or provide a 0.2dB gain for a similar computational cost. Results on publicly available datasets demonstrate that the proposed algorithms surpass current state-of-the-art performance in both accuracy and efficiency.

##### Abstract (translated by Google)
卷积神经网络实现了准确的图像超分辨率实时。然而，最近从视频超分辨率的时间相关性中受益的尝试仅限于天真或低效的体系结构。在本文中，我们引入时空子像素卷积网络，有效地利用时间冗余，提高重建精度，同时保持实时速度。具体而言，我们讨论了对于多个连续视频帧的联合处理的早期融合，慢融合​​和3D卷积的使用。我们还提出了一种新颖的联合运动补偿和视频超分辨率算法，它比竞争方法的效率高数个数量级，依靠快速的多分辨率空间变换器模块，是端到端可训练的。这些贡献提供了更高的准确性和时间上更一致的视频，我们确认定性和定量。相对于单帧模型，时空网络可以将计算成本降低30％，同时保持相同的质量，或者为类似的计算成本提供0.2dB的增益。公开可用的数据集的结果表明，所提出的算法在准确性和效率两方面都超越了当前最先进的性能。

##### URL
[https://arxiv.org/abs/1611.05250](https://arxiv.org/abs/1611.05250)

##### PDF
[https://arxiv.org/pdf/1611.05250](https://arxiv.org/pdf/1611.05250)

