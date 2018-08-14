---
layout: post
title: "Iterative Global Similarity Points : A robust coarse-to-fine integration solution for pairwise 3D point cloud registration"
date: 2018-08-12 06:19:37
categories: arXiv_CV
tags: arXiv_CV
author: Yue Pan, Bisheng Yang, Fuxun Liang, Zhen Dong
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a coarse-to-fine integration solution inspired by the classical ICP algorithm, to pairwise 3D point cloud registration with two improvements of hybrid metric spaces (eg, BSC feature and Euclidean geometry spaces) and globally optimal correspondences matching. First, we detect the keypoints of point clouds and use the Binary Shape Context (BSC) descriptor to encode their local features. Then, we formulate the correspondence matching task as an energy function, which models the global similarity of keypoints on the hybrid spaces of BSC feature and Euclidean geometry. Next, we estimate the globally optimal correspondences through optimizing the energy function by the Kuhn-Munkres algorithm and then calculate the transformation based on the correspondences. Finally,we iteratively refine the transformation between two point clouds by conducting optimal correspondences matching and transformation calculation in a mutually reinforcing manner, to achieve the coarse-to-fine registration under an unified framework.The proposed method is evaluated and compared to several state-of-the-art methods on selected challenging datasets with repetitive, symmetric and incomplete structures.Comprehensive experiments demonstrate that the proposed IGSP algorithm obtains good performance and outperforms the state-of-the-art methods in terms of both rotation and translation errors.

##### Abstract (translated by Google)
在本文中，我们提出了一种灵感来自经典ICP算法的粗到细集成解决方案，成对3D点云配准与混合度量空间的两个改进（例如，BSC特征和欧几里德几何空间）和全局最优对应匹配。首先，我们检测点云的关键点，并使用二进制形状上下文（BSC）描述符对其局部特征进行编码。然后，我们将对应匹配任务表示为能量函数，模拟了BSC特征和欧几里德几何的混合空间上关键点的全局相似性。接下来，我们通过Kuhn-Munkres算法优化能量函数来估计全局最优对应关系，然后基于对应关系计算变换。最后，我们通过相互加强的方式进行最优对应匹配和变换计算，迭代地完善两点云之间的转换，在统一框架下实现粗到精的配准。提出的方法进行了评估，并与几个状态进行了比较 - 选择具有重复性，对称性和不完整结构的挑战性数据集的最新方法。综合实验表明，所提出的IGSP算法在旋转和平移误差方面都获得了良好的性能并且优于最先进的方法。

##### URL
[http://arxiv.org/abs/1808.03899](http://arxiv.org/abs/1808.03899)

##### PDF
[http://arxiv.org/pdf/1808.03899](http://arxiv.org/pdf/1808.03899)

