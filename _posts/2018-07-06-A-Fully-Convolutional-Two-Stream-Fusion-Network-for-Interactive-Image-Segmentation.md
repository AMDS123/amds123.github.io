---
layout: post
title: "A Fully Convolutional Two-Stream Fusion Network for Interactive Image Segmentation"
date: 2018-07-06 16:48:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Yang Hu, Andrea Soltoggio, Russell Lock, Steve Carter
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel fully convolutional two-stream fusion network (FCTSFN) for interactive image segmentation. The proposed network includes two sub-networks: a two-stream late fusion network (TSLFN) that predicts the foreground at a reduced resolution, and a multi-scale refining network (MSRN) that refines the foreground at full resolution. The TSLFN includes two distinct deep streams followed by a fusion network. The intuition is that, since user interactions are more direction information on foreground/background than the image itself, the two-stream structure of the TSLFN reduces the number of layers between the pure user interaction features and the network output, allowing the user interactions to have a more direct impact on the segmentation result. The MSRN fuses the features from different layers of TSLFN with different scales, in order to seek the local to global information on the foreground to refine the segmentation result at full resolution. We conduct comprehensive experiments on four benchmark datasets. The results show that the proposed network achieves competitive performance compared to current state-of-the-art interactive image segmentation methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的完全卷积双流融合网络（FCTSFN）用于交互式图像分割。所提出的网络包括两个子网络：以降低的分辨率预测前景的双流晚期融合网络（TSLFN），以及以全分辨率精化前景的多尺度精炼网络（MSRN）。 TSLFN包括两个不同的深流，然后是融合网络。直觉是，由于用户交互是前景/背景上比图像本身更多的方向信息，因此TSLFN的双流结构减少了纯用户交互功能和网络输出之间的层数，允许用户交互到对分割结果有更直接的影响。 MSRN融合来自不同尺度的TSLFN的不同层的特征，以便在前景上寻找局部到全局信息以在全分辨率下细化分割结果。我们对四个基准数据集进行了全面的实验。结果表明，与当前最先进的交互式图像分割方法相比，所提出的网络实现了竞争性能。

##### URL
[http://arxiv.org/abs/1807.02480](http://arxiv.org/abs/1807.02480)

##### PDF
[http://arxiv.org/pdf/1807.02480](http://arxiv.org/pdf/1807.02480)

