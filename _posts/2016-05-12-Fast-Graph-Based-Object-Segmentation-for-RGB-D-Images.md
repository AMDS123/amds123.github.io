---
layout: post
title: "Fast Graph-Based Object Segmentation for RGB-D Images"
date: 2016-05-12 10:29:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Giorgio Toscana, Stefano Rosa
mathjax: true
---

* content
{:toc}

##### Abstract
Object segmentation is an important capability for robotic systems, in particular for grasping. We present a graph- based approach for the segmentation of simple objects from RGB-D images. We are interested in segmenting objects with large variety in appearance, from lack of texture to strong textures, for the task of robotic grasping. The algorithm does not rely on image features or machine learning. We propose a modified Canny edge detector for extracting robust edges by using depth information and two simple cost functions for combining color and depth cues. The cost functions are used to build an undirected graph, which is partitioned using the concept of internal and external differences between graph regions. The partitioning is fast with O(NlogN) complexity. We also discuss ways to deal with missing depth information. We test the approach on different publicly available RGB-D object datasets, such as the Rutgers APC RGB-D dataset and the RGB-D Object Dataset, and compare the results with other existing methods.

##### Abstract (translated by Google)
对象分割是机器人系统的一个重要功能，特别是抓取。我们提出了一种基于图形的方法来分割RGB-D图像中的简单对象。我们感兴趣的是分割外观变化很大的物体，从缺乏纹理到强壮的纹理，以及抓取机器人的任务。该算法不依赖于图像特征或机器学习。我们提出了一种改进的Canny边缘检测器，通过使用深度信息和两个简单​​的成本函数来组合颜色和深度线索来提取鲁棒边缘。成本函数用于构建一个无向图，该无向图使用图区域之间的内部和外部差异的概念进行划分。 O（NlogN）复杂度高，分区快。我们也讨论如何处理缺失的深度信息。我们在不同的公开可用的RGB-D对象数据集（例如Rutgers APC RGB-D数据集和RGB-D对象数据集）上测试该方法，并将结果与​​其他现有方法进行比较。

##### URL
[https://arxiv.org/abs/1605.03746](https://arxiv.org/abs/1605.03746)

##### PDF
[https://arxiv.org/pdf/1605.03746](https://arxiv.org/pdf/1605.03746)

