---
layout: post
title: "What You Sketch Is What You Get: 3D Sketching using Multi-View Deep Volumetric Prediction"
date: 2017-07-27 06:24:49
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Johanna Delanoy, Adrien Bousseau, Mathieu Aubry, Phillip Isola, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
Sketch-based modeling strives to bring the ease and immediacy of drawing to the 3D world. However, while drawings are easy for humans to create, they are very challenging for computers to interpret due to their sparsity and ambiguity. We propose a data-driven approach that tackles this challenge by learning to reconstruct 3D shapes from one or more drawings. At the core of our approach is a deep convolutional neural network (CNN) that predicts occupancy of a voxel grid from a line drawing. This CNN provides us with an initial 3D reconstruction as soon as the user completes a single drawing of the desired shape. We complement this single-view network with an updater CNN that refines an existing prediction given a new drawing of the shape created from a novel viewpoint. A key advantage of our approach is that we can apply the updater iteratively to fuse information from an arbitrary number of viewpoints, without requiring explicit stroke correspondences between the drawings. We train both CNNs by rendering synthetic contour drawings from hand-modeled shape collections as well as from procedurally-generated abstract shapes. Finally, we integrate our CNNs in a minimal modeling interface that allows users to seamlessly draw an object, rotate it to see its 3D reconstruction, and refine it by re-drawing from another vantage point using the 3D reconstruction as guidance. The main strengths of our approach are its robustness to freehand bitmap drawings, its ability to adapt to different object categories, and the continuum it offers between single-view and multi-view sketch-based modeling.

##### Abstract (translated by Google)
基于素描的建模力求将绘制的简易性和即时性带到三维世界。然而，虽然绘图对于人类来说很容易创建，但由于其稀疏性和模糊性，对于计算机来说，它们是非常具有挑战性的。我们提出了一个数据驱动的方法，通过学习从一个或多个图纸重建三维形状来应对这一挑战。我们方法的核心是一个深度卷积神经网络（CNN），可以从线条图中预测体素网格的占用情况。只要用户完成所需形状的单个图形，CNN就为我们提供了初始3D重建。我们用一个更新的CNN补充了这个单视图网络，它改进了现有的预测，给出了一个新的视图创建的形状的新图。我们的方法的一个关键优势是我们可以迭代地应用更新器来融合来自任意数量的视点的信息，而不需要图纸之间明确的笔划对应。我们通过从手工建模的形状集合以及程序生成的抽象形状渲染合成轮廓图来训练CNN。最后，我们将CNN集成到一个最小化的建模界面中，允许用户无缝地绘制对象，旋转它以查看其三维重建，并通过使用三维重建作为指导从另一个有利位置重新绘制来对其进行优化。我们的方法的主要优点是它对自由位图绘图的稳健性，适应不同对象类别的能力以及它在单视图和多视图草图建模之间提供的连续性。

##### URL
[https://arxiv.org/abs/1707.08390](https://arxiv.org/abs/1707.08390)

##### PDF
[https://arxiv.org/pdf/1707.08390](https://arxiv.org/pdf/1707.08390)

