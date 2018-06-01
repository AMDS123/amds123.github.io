---
layout: post
title: "Multi-Resolution 3D Convolutional Neural Networks for Object Recognition"
date: 2018-05-30 22:53:28
categories: arXiv_CV
tags: arXiv_CV Sparse Face CNN Recognition
author: Sambit Ghadai, Xian Lee, Aditya Balu, Soumik Sarkar, Adarsh Krishnamurthy
mathjax: true
---

* content
{:toc}

##### Abstract
Learning from 3D Data is a fascinating idea which is well explored and studied in computer vision. This allows one to learn from very sparse LiDAR data, point cloud data as well as 3D objects in terms of CAD models and surfaces etc. Most of the approaches to learn from such data are limited to uniform 3D volume occupancy grids or octree representations. A major challenge in learning from 3D data is that one needs to define a proper resolution to represent it in a voxel grid and this becomes a bottleneck for the learning algorithms. Specifically, while we focus on learning from 3D data, a fine resolution is very important to capture key features in the object and at the same time the data becomes sparser as the resolution becomes finer. There are numerous applications in computer vision where a multi-resolution representation is used instead of a uniform grid representation in order to make the applications memory efficient. Though such methods are difficult to learn from, they are much more efficient in representing 3D data. In this paper, we explore the challenges in learning from such data representation. In particular, we use a multi-level voxel representation where we define a coarse voxel grid that contains information of important voxels(boundary voxels) and multiple fine voxel grids corresponding to each significant voxel of the coarse grid. A multi-level voxel representation can capture important features in the 3D data in a memory efficient way in comparison to an octree representation. Consequently, learning from a 3D object with high resolution, which is paramount in feature recognition, is made efficient.

##### Abstract (translated by Google)
从3D数据中学习是一个非常有趣的想法，在计算机视觉中有很好的探索和研究。这允许从非常稀疏的LiDAR数据，点云数据以及CAD模型和曲面等方面的3D对象中学习。大多数从这些数据中学习的方法仅限于统一的3D体积占用网格或八叉树表示。从3D数据学习的一个主要挑战是需要定义一个适当的分辨率来表示它在体素网格中，这成为学习算法的瓶颈。具体来说，虽然我们专注于从3D数据中学习，但是精确的分辨率对于捕捉对象中的关键特征非常重要，同时数据在分辨率变得更好时变得更加稀疏。计算机视觉中有许多应用程序，其中使用多分辨率表示而不是均匀网格表示，以便使应用程序内存高效。尽管这些方法很难学习，但它们在表示3D数据方面效率更高。在本文中，我们探讨了从这种数据表示中学习的挑战。特别地，我们使用多级体素表示，其中我们定义粗体素网格，其包含重要体素（边界体素）的信息和与粗网格的每个显着体素对应的多个细体素网格。与八叉树表示法相比，多级体素表示法可以以高效的内存方式捕获3D数据中的重要特征。因此，从高分辨率的3D对象学习，这对于特征识别是至关重要的，是高效的。

##### URL
[http://arxiv.org/abs/1805.12254](http://arxiv.org/abs/1805.12254)

##### PDF
[http://arxiv.org/pdf/1805.12254](http://arxiv.org/pdf/1805.12254)

