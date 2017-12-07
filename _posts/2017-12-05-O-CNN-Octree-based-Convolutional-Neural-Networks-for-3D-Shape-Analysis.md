---
layout: post
title: "O-CNN: Octree-based Convolutional Neural Networks for 3D Shape Analysis"
date: 2017-12-05 09:25:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Peng-Shuai Wang, Yang Liu, Yu-Xiao Guo, Chun-Yu Sun, Xin Tong
mathjax: true
---

* content
{:toc}

##### Abstract
We present O-CNN, an Octree-based Convolutional Neural Network (CNN) for 3D shape analysis. Built upon the octree representation of 3D shapes, our method takes the average normal vectors of a 3D model sampled in the finest leaf octants as input and performs 3D CNN operations on the octants occupied by the 3D shape surface. We design a novel octree data structure to efficiently store the octant information and CNN features into the graphics memory and execute the entire O-CNN training and evaluation on the GPU. O-CNN supports various CNN structures and works for 3D shapes in different representations. By restraining the computations on the octants occupied by 3D surfaces, the memory and computational costs of the O-CNN grow quadratically as the depth of the octree increases, which makes the 3D CNN feasible for high-resolution 3D models. We compare the performance of the O-CNN with other existing 3D CNN solutions and demonstrate the efficiency and efficacy of O-CNN in three shape analysis tasks, including object classification, shape retrieval, and shape segmentation.

##### Abstract (translated by Google)
我们提出O-CNN，一种基于八叉树的卷积神经网络（CNN），用于3D形状分析。建立在三维形状的八叉树表示的基础上，我们的方法是将在最好的叶子八分区中采样的三维模型的平均法向量作为输入，对三维形状曲面所占的八分区进行三维CNN运算。我们设计了一种新颖的八叉树数据结构，将八分信息和CNN特征有效地存储到图形存储器中，并在GPU上执行整个O-CNN训练和评估。 O-CNN支持各种CNN结构，适用于不同表示的3D形状。通过限制三维表面占据的八分圆的计算，随着八叉树深度的增加，O-CNN的记忆和计算成本呈现二次增长，这使得三维CNN在高分辨率三维模型中可行。我们比较O-CNN与其他现有的3D CNN解决方案的性能，并展示O-CNN在三个形状分析任务（包括对象分类，形状检索和形状分割）中的效率和功效。

##### URL
[https://arxiv.org/abs/1712.01537](https://arxiv.org/abs/1712.01537)

##### PDF
[https://arxiv.org/pdf/1712.01537](https://arxiv.org/pdf/1712.01537)

