---
layout: post
title: "VConv-DAE: Deep Volumetric Shape Learning Without Object Labels"
date: 2016-09-09 20:36:36
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification Deep_Learning Recognition
author: Abhishek Sharma, Oliver Grau, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
With the advent of affordable depth sensors, 3D capture becomes more and more ubiquitous and already has made its way into commercial products. Yet, capturing the geometry or complete shapes of everyday objects using scanning devices (e.g. Kinect) still comes with several challenges that result in noise or even incomplete shapes. Recent success in deep learning has shown how to learn complex shape distributions in a data-driven way from large scale 3D CAD Model collections and to utilize them for 3D processing on volumetric representations and thereby circumventing problems of topology and tessellation. Prior work has shown encouraging results on problems ranging from shape completion to recognition. We provide an analysis of such approaches and discover that training as well as the resulting representation are strongly and unnecessarily tied to the notion of object labels. Thus, we propose a full convolutional volumetric auto encoder that learns volumetric representation from noisy data by estimating the voxel occupancy grids. The proposed method outperforms prior work on challenging tasks like denoising and shape completion. We also show that the obtained deep embedding gives competitive performance when used for classification and promising results for shape interpolation.

##### Abstract (translated by Google)
随着价格合理的深度传感器的出现，3D捕捉变得越来越无处不在，并已经进入商业产品。然而，使用扫描设备（例如Kinect）捕捉日常物体的几何形状或完整形状仍然带来几个挑战，导致噪音甚至不完整的形状。最近在深度学习方面取得的成功表明，如何以大规模3D CAD模型集合的数据驱动方式学习复杂的形状分布，并将其用于体积表示的3D处理，从而避免拓扑和曲面细分的问题。先前的工作已经在从形状完成到识别的问题上显示出令人鼓舞的结果我们提供了这种方法的分析，发现训练以及由此产生的表示强烈地，不必要地与对象标签的概念联系在一起。因此，我们提出了一个完整的卷积容积自动编码器，通过估计体素占用网格来从噪声数据中学习体积表示。提出的方法胜过以前的工作，如去噪和形状完成等具有挑战性的任务。我们还表明，获得的深嵌入提供了竞争性能用于分类和有希望的结果形状插值。

##### URL
[https://arxiv.org/abs/1604.03755](https://arxiv.org/abs/1604.03755)

##### PDF
[https://arxiv.org/pdf/1604.03755](https://arxiv.org/pdf/1604.03755)

