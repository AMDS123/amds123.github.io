---
layout: post
title: "Scene Flow to Action Map: A New Representation for RGB-D based Action Recognition with Convolutional Neural Networks"
date: 2017-03-27 00:52:21
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Action_Recognition CNN Recognition
author: Pichao Wang, Wanqing Li, Zhimin Gao, Yuyao Zhang, Chang Tang, Philip Ogunbona
mathjax: true
---

* content
{:toc}

##### Abstract
Scene flow describes the motion of 3D objects in real world and potentially could be the basis of a good feature for 3D action recognition. However, its use for action recognition, especially in the context of convolutional neural networks (ConvNets), has not been previously studied. In this paper, we propose the extraction and use of scene flow for action recognition from RGB-D data. Previous works have considered the depth and RGB modalities as separate channels and extract features for later fusion. We take a different approach and consider the modalities as one entity, thus allowing feature extraction for action recognition at the beginning. Two key questions about the use of scene flow for action recognition are addressed: how to organize the scene flow vectors and how to represent the long term dynamics of videos based on scene flow. In order to calculate the scene flow correctly on the available datasets, we propose an effective self-calibration method to align the RGB and depth data spatially without knowledge of the camera parameters. Based on the scene flow vectors, we propose a new representation, namely, Scene Flow to Action Map (SFAM), that describes several long term spatio-temporal dynamics for action recognition. We adopt a channel transform kernel to transform the scene flow vectors to an optimal color space analogous to RGB. This transformation takes better advantage of the trained ConvNets models over ImageNet. Experimental results indicate that this new representation can surpass the performance of state-of-the-art methods on two large public datasets.

##### Abstract (translated by Google)
场景流描述了真实世界中三维物体的运动，并可能成为三维动作识别的一个很好的特征的基础。然而，其用于动作识别，特别是在卷积神经网络（ConvNets）的情况下，尚未被研究过。在本文中，我们提出从RGB-D数据中提取和使用场景流进行动作识别。先前的作品已经将深度和RGB模态作为单独的通道并提取用于以后的融合的特征。我们采用不同的方法，并将模态视为一个实体，因此在开始时允许对动作识别进行特征提取。针对如何使用场景流进行动作识别，提出了两个关键问题：如何组织场景流向量以及如何根据场景流来表示视频的长期动态。为了在可用数据集上正确计算场景流，我们提出了一种有效的自校准方法，在不知道相机参数的情况下，将RGB和深度数据在空间上对齐。基于场景流向量，我们提出了一种新的表示方式，即场景流向动作映射（SFAM），它描述了动作识别的几个长期的时空动态。我们采用一个信道变换核将场景流向量转换成类似于RGB的最佳色彩空间。这种转换比ImageNet更好地利用了训练的ConvNets模型。实验结果表明，这种新的表示方法可以在两个大型公共数据集上超越最先进方法的性能。

##### URL
[https://arxiv.org/abs/1702.08652](https://arxiv.org/abs/1702.08652)

##### PDF
[https://arxiv.org/pdf/1702.08652](https://arxiv.org/pdf/1702.08652)

