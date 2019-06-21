---
layout: post
title: "PointNLM: Point Nonlocal-Means for vegetation segmentation based on middle echo point clouds"
date: 2019-06-20 07:34:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification Deep_Learning Relation
author: Jonathan Li, Rongren Wu, Yiping Chen, Qing Zhu, Zhipeng Luo, Cheng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Middle-echo, which covers one or a few corresponding points, is a specific type of 3D point cloud acquired by a multi-echo laser scanner. In this paper, we propose a novel approach for automatic segmentation of trees that leverages middle-echo information from LiDAR point clouds. First, using a convolution classification method, the proposed type of point clouds reflected by the middle echoes are identified from all point clouds. The middle-echo point clouds are distinguished from the first and last echoes. Hence, the crown positions of the trees are quickly detected from the huge number of point clouds. Second, to accurately extract trees from all point clouds, we propose a 3D deep learning network, PointNLM, to semantically segment tree crowns. PointNLM captures the long-range relationship between the point clouds via a non-local branch and extracts high-level features via max-pooling applied to unordered points. The whole framework is evaluated using the Semantic 3D reduced-test set. The IoU of tree point cloud segmentation reached 0.864. In addition, the semantic segmentation network was tested using the Paris-Lille-3D dataset. The average IoU outperformed several other popular methods. The experimental results indicate that the proposed algorithm provides an excellent solution for vegetation segmentation from LiDAR point clouds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08476](http://arxiv.org/abs/1906.08476)

##### PDF
[http://arxiv.org/pdf/1906.08476](http://arxiv.org/pdf/1906.08476)

