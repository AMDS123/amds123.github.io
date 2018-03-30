---
layout: post
title: "3DMV: Joint 3D-Multi-View Prediction for 3D Semantic Scene Segmentation"
date: 2018-03-28 04:22:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Angela Dai, Matthias Nießner
mathjax: true
---

* content
{:toc}

##### Abstract
We present 3DMV, a novel method for 3D semantic scene segmentation of RGB-D scans in indoor environments using a joint 3D-multi-view prediction network. In contrast to existing methods that either use geometry or RGB data as input for this task, we combine both data modalities in a joint, end-to-end network architecture. Rather than simply projecting color data into a volumetric grid and operating solely in 3D -- which would result in insufficient detail -- we first extract feature maps from associated RGB images. These features are then mapped into the volumetric feature grid of a 3D network using a differentiable backprojection layer. Since our target is 3D scanning scenarios with possibly many frames, we use a multi-view pooling approach in order to handle a varying number of RGB input views. This learned combination of RGB and geometric features with our joint 2D-3D architecture achieves significantly better results than existing baselines. For instance, our final result on the ScanNet 3D segmentation benchmark increases from 52.8\% to 75\% accuracy compared to existing volumetric architectures.

##### Abstract (translated by Google)
我们提出了3DMV，这是一种用于使用联合3D多视图预测网络在室内环境中进行RGB-D扫描的3D语义场景分割的新方法。与使用几何或RGB数据作为此任务的输入的现有方法相比，我们将这两种数据模式组合在一个联合的端到端网络体系结构中。我们首先从关联的RGB图像中提取特征图，而不是简单地将颜色数据投影到体积网格中，而只是在3D中操作 - 这会导致细节不足。然后使用可微分背投影层将这些特征映射到3D网络的体积特征网格中。由于我们的目标是可能有很多帧的3D扫描场景，因此我们使用多视图池化方法来处理不同数量的RGB输入视图。将RGB和几何特征与我们的联合2D-3D架构相结合，可获得比现有基线更好的结果。例如，与现有的体积架构相比，ScanNet 3D分割基准测试的最终结果从52.8％提高到75％。

##### URL
[https://arxiv.org/abs/1803.10409](https://arxiv.org/abs/1803.10409)

##### PDF
[https://arxiv.org/pdf/1803.10409](https://arxiv.org/pdf/1803.10409)

