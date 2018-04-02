---
layout: post
title: "SpiderCNN: Deep Learning on Point Sets with Parameterized Convolutional Filters"
date: 2018-03-30 16:10:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yifan Xu, Tianqi Fan, Mingye Xu, Long Zeng, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have enjoyed remarkable success for various vision tasks, however it remains challenging to apply CNNs to domains lacking a regular underlying structures such as 3D point clouds. Towards this we propose a novel convolutional architecture, termed SpiderCNN, to efficiently extract geometric features from point clouds. SpiderCNN is comprised of units called SpiderConv, which extend convolutional operations from regular grids to irregular point set that can be embedded in R^n, by parametrizing a family of convolutional filters. We elaborately design the filter as a product of simple step function that captures local geodesic information and a Taylor polynomial that ensures the expressiveness. SpiderCNN inherits the multi-scale hierarchical architecture from the classical CNNs, which allows it to extract semantic deep features. Experiments on ModelNet40 demonstrate that SpiderCNN achieves the-state-of-the art accuracy 92.4% on standard benchmarks, and shows competitive performance on segmentation task.

##### Abstract (translated by Google)
深度神经网络在各种视觉任务中取得了显着的成功，但将CNN应用于缺乏像3D点云那样的常规基础结构的领域仍然具有挑战性。为此，我们提出了一种称为SpiderCNN的新型卷积体系结构，可有效地从点云中提取几何特征。 SpiderCNN由称为SpiderConv的单元组成，这些单元通过参数化卷积滤波器族将卷积操作从规则网格扩展到可以嵌入R ^ n的不规则点集合。我们精心设计滤波器，作为捕捉局部测地信息的简单步进函数和确保表达性的泰勒多项式的乘积。 SpiderCNN继承了经典CNN的多尺度分层体系结构，允许其提取语义深度特征。 ModelNet40上的实验表明，SpiderCNN在标准基准测试中达到了92.4％的最高精度，并且在分割任务上显示出具有竞争力的性能。

##### URL
[https://arxiv.org/abs/1803.11527](https://arxiv.org/abs/1803.11527)

##### PDF
[https://arxiv.org/pdf/1803.11527](https://arxiv.org/pdf/1803.11527)

