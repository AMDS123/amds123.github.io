---
layout: post
title: "Multi-Modal Obstacle Detection in Unstructured Environments with Conditional Random Fields"
date: 2017-06-09 11:48:25
categories: arXiv_CV
tags: arXiv_CV Sparse Inference Classification Detection
author: Mikkel Kragh, James Underwood
mathjax: true
---

* content
{:toc}

##### Abstract
Reliable obstacle detection and classification in rough and unstructured terrain such as agricultural fields or orchards remains a challenging problem. These environments involve large variations in both geometry and appearance, challenging perception systems that rely on only a single sensor modality. Geometrically, tall grass, fallen leaves, or terrain roughness can mistakenly be perceived as non-traversable or might even obscure actual obstacles. Likewise, traversable grass or dirt roads and obstacles such as trees and bushes might be visually ambiguous. In this paper, we combine appearance- and geometry-based detection methods by probabilistically fusing lidar and camera sensing using a conditional random field. We apply a state-of-the-art multi-modal fusion algorithm from the scene analysis domain and adjust it for obstacle detection in agriculture with moving ground vehicles. This involves explicitly handling sparse point cloud data and exploiting both spatial, temporal, and multi-modal links between corresponding 2D and 3D regions. The proposed method is evaluated on a diverse dataset, comprising a dairy paddock and a number of different orchards gathered with a perception research robot in Australia. Results show that for a two-class classification problem (ground and non-ground), only the camera leverages from information provided by the other modality. However, as more classes are introduced (ground, sky, vegetation, and object), both modalities complement each other and improve the mean classification score. Further improvement is achieved by introducing recursive inference with temporal links between successive frames.

##### Abstract (translated by Google)
在粗糙和非结构化的地形（如农田或果园）中进行可靠的障碍物检测和分类仍然是一个具有挑战性的问题。这些环境在几何和外观上都有很大的变化，只依靠单一传感器模式的挑战感知系统。几何学上，高草，落叶或地形粗糙度可能被误认为是不可穿越的，甚至可能模糊实际障碍。同样，可穿越的草地或土路以及诸如树木和灌木丛等障碍物可能在视觉上模棱两可。在本文中，我们结合基于外观和几何的检测方法，通过概率融合激光雷达和相机感应使用条件随机场。我们从现场分析领域采用最先进的多模式融合算法，并利用移动的地面车辆对农业中的障碍物进行调整。这涉及明确处理稀疏点云数据并利用对应的2D和3D区域之间的空间，时间和多模式链接。所提出的方法在不同的数据集上进行评估，包括一个奶牛围场和澳大利亚的一个感知研究机器人聚集的许多不同的果园。结果显示，对于两类分类问题（地面和非地面），只有相机利用其他方式提供的信息。然而，随着更多类别（地面，天空，植被和对象）的引入，两种模式相辅相成，提高了平均分类得分。进一步的改进是通过在连续帧之间引入递归推理来实现的。

##### URL
[https://arxiv.org/abs/1706.02908](https://arxiv.org/abs/1706.02908)

##### PDF
[https://arxiv.org/pdf/1706.02908](https://arxiv.org/pdf/1706.02908)

