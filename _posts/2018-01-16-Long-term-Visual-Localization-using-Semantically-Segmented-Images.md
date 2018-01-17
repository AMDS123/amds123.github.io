---
layout: post
title: "Long-term Visual Localization using Semantically Segmented Images"
date: 2018-01-16 14:43:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Erik Stenborg, Carl Toft, Lars Hammarstrand
mathjax: true
---

* content
{:toc}

##### Abstract
Robust cross-seasonal localization is one of the major challenges in long-term visual navigation of autonomous vehicles. In this paper, we exploit recent advances in semantic segmentation of images, i.e., where each pixel is assigned a label related to the type of object it represents, to solve the problem of long-term visual localization. We show that semantically labeled 3D point maps of the environment, together with semantically segmented images, can be efficiently used for vehicle localization without the need for detailed feature descriptors (SIFT, SURF, etc.). Thus, instead of depending on hand-crafted feature descriptors, we rely on the training of an image segmenter. The resulting map takes up much less storage space compared to a traditional descriptor based map. A particle filter based semantic localization solution is compared to one based on SIFT-features, and even with large seasonal variations over the year we perform on par with the larger and more descriptive SIFT-features, and are able to localize with an error below 1 m most of the time.

##### Abstract (translated by Google)
强劲的跨季节性定位是自主车辆长期视觉导航的主要挑战之一。在本文中，我们利用图像语义分割方面的最新进展，即为每个像素分配与其所代表的对象类型相关的标签，以解决长期视觉定位问题。我们表明，语义标记的环境三维点图，连同语义分割的图像，可以有效地用于车辆定位，而不需要详细的特征描述符（SIFT，SURF等）。因此，我们不依赖于手工制作的特征描述符，而是依赖于图像分割器的训练。与传统的基于描述符的地图相比，由此产生的地图占用更少的存储空间。将基于粒子滤波器的语义定位解决方案与基于SIFT特征的解决方案进行比较，即使一年中有大量的季节变化，我们也可以与更大，更具描述性的SIFT特征进行比较，并且能够以低于1大部分时间。

##### URL
[http://arxiv.org/abs/1801.05269](http://arxiv.org/abs/1801.05269)

##### PDF
[http://arxiv.org/pdf/1801.05269](http://arxiv.org/pdf/1801.05269)

