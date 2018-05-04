---
layout: post
title: "Matryoshka Networks: Predicting 3D Geometry via Nested Shape Layers"
date: 2018-04-29 18:33:21
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Stephan R. Richter, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop novel, efficient 2D encodings for 3D geometry, which enable reconstructing full 3D shapes from a single image at high resolution. The key idea is to pose 3D shape reconstruction as a 2D prediction problem. To that end, we first develop a simple baseline network that predicts entire voxel tubes at each pixel of a reference view. By leveraging well-proven architectures for 2D pixel-prediction tasks, we attain state-of-the-art results, clearly outperforming purely voxel-based approaches. We scale this baseline to higher resolutions by proposing a memory-efficient shape encoding, which recursively decomposes a 3D shape into nested shape layers, similar to the pieces of a Matryoshka doll. This allows reconstructing highly detailed shapes with complex topology, as demonstrated in extensive experiments; we clearly outperform previous octree-based approaches despite having a much simpler architecture using standard network components. Our Matryoshka networks further enable reconstructing shapes from IDs or shape similarity, as well as shape sampling.

##### Abstract (translated by Google)
在本文中，我们开发了新颖，高效的3D几何体编码，可以从高分辨率的单个图像重建完整的三维形状。关键的想法是将三维形状重建作为二维预测问题。为此，我们首先开发一个简单的基线网络，可以在参考视图的每个像素处预测整个体素管。通过利用经过验证的二维像素预测任务架构，我们获得了最先进的结果，明显优于纯粹的基于体素的方法。我们通过提出一种高效的内存形状编码来将这个基线扩展到更高的分辨率，这种编码将3D形状递归分解为嵌套形状图层，类似于Matryoshka娃娃的片段。这可以通过复杂的拓扑结构重建高度详细的形状，如广泛的实验所证明的那样;尽管采用标准网络组件的架构简单得多，但我们明显优于以前的基于八叉树的方法。我们的Matryoshka网络进一步支持从ID或形状相似性以及形状抽样重建形状。

##### URL
[https://arxiv.org/abs/1804.10975](https://arxiv.org/abs/1804.10975)

##### PDF
[https://arxiv.org/pdf/1804.10975](https://arxiv.org/pdf/1804.10975)

