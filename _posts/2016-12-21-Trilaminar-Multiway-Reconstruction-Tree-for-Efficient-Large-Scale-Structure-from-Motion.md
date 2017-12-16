---
layout: post
title: "Trilaminar Multiway Reconstruction Tree for Efficient Large Scale Structure from Motion"
date: 2016-12-21 14:50:36
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kun Sun, Wenbing Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Accuracy and efficiency are two key problems in large scale incremental Structure from Motion (SfM). In this paper, we propose a unified framework to divide the image set into clusters suitable for reconstruction as well as find multiple reliable and stable starting points. Image partitioning performs in two steps. First, some small image groups are selected at places with high image density, and then all the images are clustered according to their optimal reconstruction paths to these image groups. This promises that the scene is always reconstructed from dense places to sparse areas, which can reduce error accumulation when images have weak overlap. To enable faster speed, images outside the selected group in each cluster are further divided to achieve a greater degree of parallelism. Experiments show that our method achieves significant speedup, higher accuracy and better completeness.

##### Abstract (translated by Google)
准确性和效率是大规模增量运动结构（SfM）中的两个关键问题。在本文中，我们提出了一个统一的框架，将图像集划分为适合重建的集群，并找到多个可靠和稳定的起点。图像分区分两步执行。首先在图像密度较高的地方选取一些小的图像组，然后根据这些图像组的最佳重建路径将所有图像进行聚类。这保证了场景总是从稠密的地方重建到稀疏的地方，这样可以减少图像重叠较弱时的误差累积。为了实现更快的速度，每个群集中选定群组之外的图像被进一步分割以达到更高程度的并行性。实验表明，我们的方法实现了显着的加速，更高的准确性和更好的完整性。

##### URL
[https://arxiv.org/abs/1612.07153](https://arxiv.org/abs/1612.07153)

##### PDF
[https://arxiv.org/pdf/1612.07153](https://arxiv.org/pdf/1612.07153)

