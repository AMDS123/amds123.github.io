---
layout: post
title: "GPU Accelerated Cascade Hashing Image Matching for Large Scale 3D Reconstruction"
date: 2018-05-23 07:57:01
categories: arXiv_CV
tags: arXiv_CV
author: Tao Xu, Kun Sun, Wenbing Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Image feature point matching is a key step in Structure from Motion(SFM). However, it is becoming more and more time consuming because the number of images is getting larger and larger. In this paper, we proposed a GPU accelerated image matching method with improved Cascade Hashing. Firstly, we propose a Disk-Memory-GPU data exchange strategy and optimize the load order of data, so that the proposed method can deal with big data. Next, we parallelize the Cascade Hashing method on GPU. An improved parallel reduction and an improved parallel hashing ranking are proposed to fulfill this task. Finally, extensive experiments show that our image matching is about 20 times faster than SiftGPU on the same graphics card, nearly 100 times faster than the CPU CasHash method and hundreds of times faster than the CPU Kd-Tree based matching method. Further more, we introduce the epipolar constraint to the proposed method, and use the epipolar geometry to guide the feature matching procedure, which further reduces the matching cost.

##### Abstract (translated by Google)
图像特征点匹配是Structure from Motion（SFM）中的关键步骤。但是，由于图像数量越来越大，它变得越来越耗时。在本文中，我们提出了一种改进的级联散列的GPU加速图像匹配方法。首先，我们提出了一种磁盘 - 内存 -  GPU数据交换策略，并优化了数据的加载顺序，使得该方法可以处理大数据。接下来，我们在GPU上并行化Cascade Hashing方法。提出了一种改进的并行压缩和改进的并行哈希排序来完成这项任务。最后，大量实验表明，我们的图像匹配比同一块图形卡上的SiftGPU快大约20倍，比CPU CasHash方法快近100倍，比基于CPU Kd-Tree的匹配方法快数百倍。进一步，我们将外极线约束引入到所提出的方法中，并且使用对极几何来指导特征匹配过程，这进一步降低了匹配成本。

##### URL
[http://arxiv.org/abs/1805.08995](http://arxiv.org/abs/1805.08995)

##### PDF
[http://arxiv.org/pdf/1805.08995](http://arxiv.org/pdf/1805.08995)

