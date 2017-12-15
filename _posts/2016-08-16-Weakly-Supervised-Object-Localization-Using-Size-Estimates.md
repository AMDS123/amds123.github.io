---
layout: post
title: "Weakly Supervised Object Localization Using Size Estimates"
date: 2016-08-16 11:31:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Miaojing Shi, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present a technique for weakly supervised object localization (WSOL), building on the observation that WSOL algorithms usually work better on images with bigger objects. Instead of training the object detector on the entire training set at the same time, we propose a curriculum learning strategy to feed training images into the WSOL learning loop in an order from images containing bigger objects down to smaller ones. To automatically determine the order, we train a regressor to estimate the size of the object given the whole image as input. Furthermore, we use these size estimates to further improve the re-localization step of WSOL by assigning weights to object proposals according to how close their size matches the estimated object size. We demonstrate the effectiveness of using size order and size weighting on the challenging PASCAL VOC 2007 dataset, where we achieve a significant improvement over existing state-of-the-art WSOL techniques.

##### Abstract (translated by Google)
我们提出了一种弱监督对象定位技术（WSOL），建立在观察到WSOL算法通常在具有较大对象的图像上更好地工作。我们提出了一个课程学习策略，将训练图像按照从包含较大对象到较小对象的图像的顺序送入WSOL学习循环，而不是同时在整个训练集上训练目标探测器。为了自动确定顺序，我们训练一个回归器来估计给定整个图像的对象的大小作为输入。此外，我们使用这些大小估计来进一步改进WSOL的​​重新定位步骤，方法是根据对象提议的大小与估计对象大小的匹配程度，为对象提议分配权重。我们展示了在具有挑战性的PASCAL VOC 2007数据集上使用大小顺序和大小权重的有效性，在这个数据集中我们实现了对现有最先进的WSOL技术的显着改进。

##### URL
[https://arxiv.org/abs/1608.04314](https://arxiv.org/abs/1608.04314)

##### PDF
[https://arxiv.org/pdf/1608.04314](https://arxiv.org/pdf/1608.04314)

