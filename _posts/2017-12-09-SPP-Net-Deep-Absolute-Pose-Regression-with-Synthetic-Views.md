---
layout: post
title: "SPP-Net: Deep Absolute Pose Regression with Synthetic Views"
date: 2017-12-09 23:45:03
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation CNN
author: Pulak Purkait, Cheng Zhao, Christopher Zach
mathjax: true
---

* content
{:toc}

##### Abstract
Image based localization is one of the important problems in computer vision due to its wide applicability in robotics, augmented reality, and autonomous systems. There is a rich set of methods described in the literature how to geometrically register a 2D image w.r.t.\ a 3D model. Recently, methods based on deep (and convolutional) feedforward networks (CNNs) became popular for pose regression. However, these CNN-based methods are still less accurate than geometry based methods despite being fast and memory efficient. In this work we design a deep neural network architecture based on sparse feature descriptors to estimate the absolute pose of an image. Our choice of using sparse feature descriptors has two major advantages: first, our network is significantly smaller than the CNNs proposed in the literature for this task---thereby making our approach more efficient and scalable. Second---and more importantly---, usage of sparse features allows to augment the training data with synthetic viewpoints, which leads to substantial improvements in the generalization performance to unseen poses. Thus, our proposed method aims to combine the best of the two worlds---feature-based localization and CNN-based pose regression--to achieve state-of-the-art performance in the absolute pose estimation. A detailed analysis of the proposed architecture and a rigorous evaluation on the existing datasets are provided to support our method.

##### Abstract (translated by Google)
由于在机器人，增强现实和自治系统中的广泛适用性，基于图像的定位是计算机视觉中的重要问题之一。在文献中描述了一系列丰富的方法，如何几何地记录一个3D模型的二维图像。最近，基于深度（和卷积）前馈网络（CNN）的方法开始普遍用于姿态回归。然而，这些基于CNN的方法仍然不如基于几何的方法准确，尽管速度和内存效率都很高。在这项工作中，我们设计了一个基于稀疏特征描述符的深度神经网络体系结构来估计图像的绝对姿态。我们使用稀疏特征描述符的选择有两个主要优势：第一，我们的网络比文献中提出的CNNs要小得多，从而使我们的方法更加高效和可扩展。第二，更重要的是，稀疏特征的使用允许用合成视点来增加训练数据，这导致对看不见的姿势的泛化性能的实质性改进。因此，我们提出的方法旨在结合两个世界中最好的 - 基于特征的定位和基于CNN的姿态回归 - 在绝对姿态估计中实现最先进的性能。提供了对建议的架构的详细分析和对现有数据集的严格评估，以支持我们的方法。

##### URL
[http://arxiv.org/abs/1712.03452](http://arxiv.org/abs/1712.03452)

##### PDF
[http://arxiv.org/pdf/1712.03452](http://arxiv.org/pdf/1712.03452)

