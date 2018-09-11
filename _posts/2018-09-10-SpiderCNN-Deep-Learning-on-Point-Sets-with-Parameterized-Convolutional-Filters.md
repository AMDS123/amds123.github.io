---
layout: post
title: "SpiderCNN: Deep Learning on Point Sets with Parameterized Convolutional Filters"
date: 2018-09-10 14:16:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yifan Xu, Tianqi Fan, Mingye Xu, Long Zeng, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have enjoyed remarkable success for various vision tasks, however it remains challenging to apply CNNs to domains lacking a regular underlying structures such as 3D point clouds. Towards this we propose a novel convolutional architecture, termed SpiderCNN, to efficiently extract geometric features from point clouds. SpiderCNN is comprised of units called SpiderConv, which extend convolutional operations from regular grids to irregular point sets that can be embedded in R^n, by parametrizing a family of convolutional filters. We design the filter as a product of a simple step function that captures local geodesic information and a Taylor polynomial that ensures the expressiveness. SpiderCNN inherits the multi-scale hierarchical architecture from classical CNNs, which allows it to extract semantic deep features. Experiments on ModelNet40 demonstrate that SpiderCNN achieves state-of-the-art accuracy 92.4% on standard benchmarks, and shows competitive performance on segmentation task.

##### Abstract (translated by Google)
深度神经网络已经在各种视觉任务中获得了显着的成功，但是将CNN应用于缺乏诸如3D点云的常规底层结构的域仍然是具有挑战性的。为此，我们提出了一种新的卷积结构，称为SpiderCNN，可以有效地从点云中提取几何特征。 SpiderCNN由称为SpiderConv的单元组成，它通过参数化一系列卷积滤波器，将卷积运算从常规网格扩展到可嵌入R ^ n的不规则点集。我们将滤波器设计为捕获局部测地信息的简单阶跃函数和确保表达性的泰勒多项式的乘积。 SpiderCNN继承了经典CNN的多尺度层次结构，允许它提取语义深层特征。 ModelNet40上的实验表明，SpiderCNN在标准基准测试中达到了92.4％的最新精度，并在分割任务上显示出竞争性的表现。

##### URL
[http://arxiv.org/abs/1803.11527](http://arxiv.org/abs/1803.11527)

##### PDF
[http://arxiv.org/pdf/1803.11527](http://arxiv.org/pdf/1803.11527)

