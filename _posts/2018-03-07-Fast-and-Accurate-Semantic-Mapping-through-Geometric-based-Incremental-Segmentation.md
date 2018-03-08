---
layout: post
title: "Fast and Accurate Semantic Mapping through Geometric-based Incremental Segmentation"
date: 2018-03-07 17:36:34
categories: arXiv_CV
tags: arXiv_CV Segmentation SLAM Recognition
author: Yoshikatsu Nakajima, Keisuke Tateno, Federico Tombari, Hideo Saito
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient and scalable method for incrementally building a dense, semantically annotated 3D map in real-time. The proposed method assigns class probabilities to each region, not each element (e.g., surfel and voxel), of the 3D map which is built up through a robust SLAM framework and incrementally segmented with a geometric-based segmentation method. Differently from all other approaches, our method has a capability of running at over 30Hz while performing all processing components, including SLAM, segmentation, 2D recognition, and updating class probabilities of each segmentation label at every incoming frame, thanks to the high efficiency that characterizes the computationally intensive stages of our framework. By utilizing a specifically designed CNN to improve the frame-wise segmentation result, we can also achieve high accuracy. We validate our method on the NYUv2 dataset by comparing with the state of the art in terms of accuracy and computational efficiency, and by means of an analysis in terms of time and space complexity.

##### Abstract (translated by Google)
我们提出了一种高效可扩展的方法，可以实时构建密集的，语义注释的3D地图。所提出的方法向每个区域分配类别概率，而不是通过稳健的SLAM框架构建的3D地图的每个元素（例如，表面和体素），并且用基于几何的分割方法递增地分割。与所有其他方法不同，我们的方法具有运行速度超过30Hz的能力，同时执行所有处理组件，包括SLAM，分割，2D识别以及更新每个传入帧上每个分割标签的分类概率，这要归功于高性能我们框架的计算密集阶段。通过使用专门设计的CNN来改善帧分割结果，我们也可以实现高精度。我们通过在准确性和计算效率方面与现有技术水平进行比较，并通过对时间和空间复杂度的分析来验证我们的NYUv2数据集的方法。

##### URL
[http://arxiv.org/abs/1803.02784](http://arxiv.org/abs/1803.02784)

##### PDF
[http://arxiv.org/pdf/1803.02784](http://arxiv.org/pdf/1803.02784)

