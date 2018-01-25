---
layout: post
title: "Dynamic Graph CNN for Learning on Point Clouds"
date: 2018-01-24 01:14:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Classification
author: Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon
mathjax: true
---

* content
{:toc}

##### Abstract
Point clouds provide a flexible and scalable geometric representation suitable for countless applications in computer graphics; they also comprise the raw output of most 3D data acquisition devices. Hence, the design of intelligent computational models that act directly on point clouds is critical, especially when efficiency considerations or noise preclude the possibility of expensive denoising and meshing procedures. While hand-designed features on point clouds have long been proposed in graphics and vision, however, the recent overwhelming success of convolutional neural networks (CNNs) for image analysis suggests the value of adapting insight from CNN to the point cloud world. To this end, we propose a new neural network module dubbed EdgeConv suitable for CNN-based high-level tasks on point clouds including classification and segmentation. EdgeConv is differentiable and can be plugged into existing architectures. Compared to existing modules operating largely in extrinsic space or treating each point independently, EdgeConv has several appealing properties: It incorporates local neighborhood information; it can be stacked or recurrently applied to learn global shape properties; and in multi-layer systems affinity in feature space captures semantic characteristics over potentially long distances in the original embedding. Beyond proposing this module, we provide extensive evaluation and analysis revealing that EdgeConv captures and exploits fine-grained geometric properties of point clouds. The proposed approach achieves state-of-the-art performance on standard benchmarks including ModelNet40 and S3DIS.

##### Abstract (translated by Google)
点云提供了一个灵活的可扩展的几何表示适合计算机图形无数的应用程序;它们也是大部分3D数据采集设备的原始输出。因此，直接作用于点云的智能计算模型的设计是至关重要的，特别是当效率考虑或噪声排除了昂贵的去噪和网格划分过程的可能性时。然而，在图形和视觉中长期以来人们提出了点云上的手工设计特征，但是最近卷积神经网络（CNN）用于图像分析的巨大成功表明了从CNN到点云世界调整洞察力的价值。为此，我们提出了一种新的神经网络模块，称为EdgeConv，适用于基于CNN的点云高级任务，包括分类和分割。 EdgeConv是可区分的，可以插入现有的体系结构。相比现有模块主要在外部空间运行或独立处理每个点，EdgeConv有几个吸引人的属性：它包含当地邻居信息;它可以堆叠或反复应用来学习全局形状属性;并且在多层系统中，特征空间中的亲和性捕获原始嵌入中潜在长距离的语义特征。除了提出这个模块之外，我们提供了广泛的评估和分析，揭示了EdgeConv捕捉和利用点云的细粒度几何特性。所提出的方法在包括ModelNet40和S3DIS在内的标准基准上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1801.07829](http://arxiv.org/abs/1801.07829)

##### PDF
[http://arxiv.org/pdf/1801.07829](http://arxiv.org/pdf/1801.07829)

