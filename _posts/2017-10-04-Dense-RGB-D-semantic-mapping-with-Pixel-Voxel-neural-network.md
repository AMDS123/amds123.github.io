---
layout: post
title: "Dense RGB-D semantic mapping with Pixel-Voxel neural network"
date: 2017-10-04 21:21:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Cheng Zhao, Li Sun, Pulak Purkait, Rustam Stolkin
mathjax: true
---

* content
{:toc}

##### Abstract
For intelligent robotics applications, extending 3D mapping to 3D semantic mapping enables robots to, not only localize themselves with respect to the scene's geometrical features but also simultaneously understand the higher level meaning of the scene contexts. Most previous methods focus on geometric 3D reconstruction and scene understanding independently notwithstanding the fact that joint estimation can boost the accuracy of the semantic mapping. In this paper, a dense RGB-D semantic mapping system with a Pixel-Voxel network is proposed, which can perform dense 3D mapping while simultaneously recognizing and semantically labelling each point in the 3D map. The proposed Pixel-Voxel network obtains global context information by using PixelNet to exploit the RGB image and meanwhile, preserves accurate local shape information by using VoxelNet to exploit the corresponding 3D point cloud. Unlike the existing architecture that fuses score maps from different models with equal weights, we proposed a Softmax weighted fusion stack that adaptively learns the varying contributions of PixelNet and VoxelNet, and fuses the score maps of the two models according to their respective confidence levels. The proposed Pixel-Voxel network achieves the state-of-the-art semantic segmentation performance on the SUN RGB-D benchmark dataset. The runtime of the proposed system can be boosted to 11-12Hz, enabling near to real-time performance using an i7 8-cores PC with Titan X GPU.

##### Abstract (translated by Google)
对于智能机器人应用，将3D映射扩展到3D语义映射使机器人不仅可以根据场景的几何特征定位自己，还可以同时理解场景上下文的更高级别的含义。以前的方法大多集中在几何三维重建和场景理解上，尽管联合估计可以提高语义映射的准确性。本文提出了一种密集的RGB-D语义映射系统，该系统具有Pixel-Voxel网络，可以进行密集的三维映射，同时对3D地图中的每个点进行识别和语义标注。所提出的Pixel-Voxel网络通过使用PixelNet来利用RGB图像来获得全局上下文信息，同时利用VoxelNet来保存准确的局部形状信息以利用相应的3D点云。与现有架构融合来自不同模型的评分图的权重相等，我们提出了一个Softmax加权融合堆栈，自适应学习PixelNet和VoxelNet的变化贡献，并根据各自置信度融合两个模型的得分图。所提出的Pixel-Voxel网络在SUN RGB-D基准数据集上实现了最先进的语义分割性能。所提出的系统的运行时间可以被提升到11-12Hz，使用具有Titan X GPU的i7 8核PC实现了接近实时的性能。

##### URL
[https://arxiv.org/abs/1710.00132](https://arxiv.org/abs/1710.00132)

##### PDF
[https://arxiv.org/pdf/1710.00132](https://arxiv.org/pdf/1710.00132)

