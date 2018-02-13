---
layout: post
title: "Object Detection with Mask-based Feature Encoding"
date: 2018-02-12 08:44:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xiaochuan Fan, Hao Guo, Kang Zheng, Wei Feng, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Region-based Convolutional Neural Networks (R-CNNs) have achieved great success in the field of object detection. The existing R-CNNs usually divide a Region-of-Interest (ROI) into grids, and then localize objects by utilizing the spatial information reflected by the relative position of each grid in the ROI. In this paper, we propose a novel feature-encoding approach, where spatial information is represented through the spatial distributions of visual patterns. In particular, we design a Mask Weight Network (MWN) to learn a set of masks and then apply channel-wise masking operations to ROI feature map, followed by a global pooling and a cheap fully-connected layer. We integrate the newly designed feature encoder into the Faster R-CNN architecture. The resulting new Faster R-CNNs can preserve the object-detection accuracy of the standard Faster R-CNNs by using substantially fewer parameters. Compared to R-FCNs using state-of-art PS ROI pooling and deformable PS ROI pooling, the new Faster R-CNNs can produce higher object-detection accuracy with good run-time efficiency. We also show that a specifically designed and learned MWN can capture global contextual information and further improve the object-detection accuracy. Validation experiments are conducted on both PASCAL VOC and MS COCO datasets.

##### Abstract (translated by Google)
基于区域的卷积神经网络（R-CNN）在物体检测领域取得了巨大的成功。现有的R-CNN通常将兴趣区域（ROI）划分为网格，然后利用ROI中每个网格的相对位置所反映的空间信息来定位对象。在本文中，我们提出了一种新颖的特征编码方法，其中空间信息通过视觉模式的空间分布来表示。特别是，我们设计了一个面罩重量网络（MWN）来学习一组掩模，然后将通道掩蔽操作应用到ROI特征映射，然后是全局池和廉价的完全连接层。我们将新设计的功能编码器集成到更快的R-CNN架构中。由此产生的更快的R-CNN可以通过使用相当少的参数来保持标准更快的R-CNN的物体检测精度。与使用最先进的PS ROI池和可变形PS ROI池的R-FCN相比，新型更快的R-CNN可以产生更高的目标检测精度并具有良好的运行时效率。我们还展示了一个专门设计和学习的MWN可以捕捉全局背景信息并进一步提高对象检测的准确性。在PASCAL VOC和MS COCO数据集上进行验证实验。

##### URL
[http://arxiv.org/abs/1802.03934](http://arxiv.org/abs/1802.03934)

##### PDF
[http://arxiv.org/pdf/1802.03934](http://arxiv.org/pdf/1802.03934)

