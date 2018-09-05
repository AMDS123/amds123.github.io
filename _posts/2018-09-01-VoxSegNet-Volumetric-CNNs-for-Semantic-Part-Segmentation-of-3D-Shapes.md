---
layout: post
title: "VoxSegNet: Volumetric CNNs for Semantic Part Segmentation of 3D Shapes"
date: 2018-09-01 17:34:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Deep_Learning
author: Zongji Wang, Feng Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Voxel is an important format to represent geometric data, which has been widely used for 3D deep learning in shape analysis due to its generalization ability and regular data format. However, fine-grained tasks like part segmentation require detailed structural information, which increases voxel resolution and thus causes other issues such as the exhaustion of computational resources. In this paper, we propose a novel volumetric convolutional neural network, which could extract discriminative features encoding detailed information from voxelized 3D data under a limited resolution. To this purpose, a spatial dense extraction (SDE) module is designed to preserve the spatial resolution during the feature extraction procedure, alleviating the loss of detail caused by sub-sampling operations such as max-pooling. An attention feature aggregation (AFA) module is also introduced to adaptively select informative features from different abstraction scales, leading to segmentation with both semantic consistency and high accuracy of details. Experiment results on the large-scale dataset demonstrate the effectiveness of our method in 3D shape part segmentation.

##### Abstract (translated by Google)
体素是表示几何数据的重要格式，由于其泛化能力和常规数据格式，已被广泛用于形状分析中的3D深度学习。然而，像细分部分这样的细粒度任务需要详细的结构信息，这会增加体素分辨率，从而导致其他问题，例如耗尽计算资源。在本文中，我们提出了一种新颖的体积卷积神经网络，它可以在有限的分辨率下从体素化的3D数据中提取编码详细信息的判别特征。为此目的，空间密集提取（SDE）模块被设计为在特征提取过程期间保持空间分辨率，减轻由诸如最大池之类的子采样操作引起的细节损失。还引入了注意特征聚合（AFA）模块，以从不同的抽象尺度自适应地选择信息特征，从而导致具有语义一致性和高精度细节的分割。大规模数据集的实验结果证明了我们的方法在三维形状零件分割中的有效性。

##### URL
[http://arxiv.org/abs/1809.00226](http://arxiv.org/abs/1809.00226)

##### PDF
[http://arxiv.org/pdf/1809.00226](http://arxiv.org/pdf/1809.00226)

