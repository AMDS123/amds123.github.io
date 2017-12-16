---
layout: post
title: "3D Shape Reconstruction from Sketches via Multi-view Convolutional Networks"
date: 2017-09-29 05:18:30
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization
author: Zhaoliang Lun, Matheus Gadelha, Evangelos Kalogerakis, Subhransu Maji, Rui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for reconstructing 3D shapes from 2D sketches in the form of line drawings. Our method takes as input a single sketch, or multiple sketches, and outputs a dense point cloud representing a 3D reconstruction of the input sketch(es). The point cloud is then converted into a polygon mesh. At the heart of our method lies a deep, encoder-decoder network. The encoder converts the sketch into a compact representation encoding shape information. The decoder converts this representation into depth and normal maps capturing the underlying surface from several output viewpoints. The multi-view maps are then consolidated into a 3D point cloud by solving an optimization problem that fuses depth and normals across all viewpoints. Based on our experiments, compared to other methods, such as volumetric networks, our architecture offers several advantages, including more faithful reconstruction, higher output surface resolution, better preservation of topology and shape structure.

##### Abstract (translated by Google)
我们提出了一种以线条图的形式从二维草图重建三维形状的方法。我们的方法将一个草图或多个草图作为输入，输出代表输入草图的三维重建的密集点云。点云然后被转换成多边形网格。我们方法的核心是一个深度的编码器 - 解码器网络。编码器将草图转换为编码形状信息的紧凑表示。解码器将这种表示转换为从几个输出视点捕捉下层表面的深度和法线贴图。然后通过求解融合所有视点的深度和法线的优化问题，将多视图贴图合并到3D点云中。基于我们的实验，与体积网络等其他方法相比，我们的体系结构具有更多的忠实重建，更高的输出表面分辨率，更好的拓扑保持和形状结构等优点。

##### URL
[https://arxiv.org/abs/1707.06375](https://arxiv.org/abs/1707.06375)

##### PDF
[https://arxiv.org/pdf/1707.06375](https://arxiv.org/pdf/1707.06375)

