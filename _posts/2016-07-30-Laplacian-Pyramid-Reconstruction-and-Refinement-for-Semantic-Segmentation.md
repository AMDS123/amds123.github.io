---
layout: post
title: "Laplacian Pyramid Reconstruction and Refinement for Semantic Segmentation"
date: 2016-07-30 21:21:58
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Detection Recognition
author: Golnaz Ghiasi, Charless C. Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
CNN architectures have terrific recognition performance but rely on spatial pooling which makes it difficult to adapt them to tasks that require dense, pixel-accurate labeling. This paper makes two contributions: (1) We demonstrate that while the apparent spatial resolution of convolutional feature maps is low, the high-dimensional feature representation contains significant sub-pixel localization information. (2) We describe a multi-resolution reconstruction architecture based on a Laplacian pyramid that uses skip connections from higher resolution feature maps and multiplicative gating to successively refine segment boundaries reconstructed from lower-resolution maps. This approach yields state-of-the-art semantic segmentation results on the PASCAL VOC and Cityscapes segmentation benchmarks without resorting to more complex random-field inference or instance detection driven architectures.

##### Abstract (translated by Google)
CNN体系结构具有出色的识别性能，但依赖于空间池，这使得难以适应需要密集像素精确标记的任务。本文做出了两点贡献：（1）我们证明虽然卷积特征映射表观空间分辨率低，但高维特征表示包含重要的子像素定位信息。 （2）我们描述了一个基于拉普拉斯金字塔的多分辨率重建体系结构，该体系结构使用高分辨率特征映射的跳跃连接和乘法门控来连续优化从较低分辨率的地图重建的分割边界。这种方法在PASCAL VOC和Cityscapes分割基准测试中得出了最先进的语义分割结果，而无需借助更复杂的随机场推断或实例检测驱动的体系结构。

##### URL
[https://arxiv.org/abs/1605.02264](https://arxiv.org/abs/1605.02264)

##### PDF
[https://arxiv.org/pdf/1605.02264](https://arxiv.org/pdf/1605.02264)

