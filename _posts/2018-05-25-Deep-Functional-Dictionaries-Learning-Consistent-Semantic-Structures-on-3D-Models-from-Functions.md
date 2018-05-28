---
layout: post
title: "Deep Functional Dictionaries: Learning Consistent Semantic Structures on 3D Models from Functions"
date: 2018-05-25 03:07:15
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Minhyuk Sung, Hao Su, Ronald Yu, Leonidas Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Various 3D semantic attributes such as segmentation masks, geometric features, keypoints, and materials can be encoded as per-point probe functions on 3D geometries. Given a collection of related 3D shapes, we consider how to jointly analyze such probe functions over different shapes, and how to discover common latent structures using a neural network --- even in the absence of any correspondence information. Our network is trained on point cloud representations of shape geometry and associated semantic functions on that point cloud. These functions express a shared semantic understanding of the shapes but are not coordinated in any way. For example, in a segmentation task, the functions can be indicator functions of arbitrary sets of shape parts, with the particular combination involved not known to the network. Our network is able to produce a small dictionary of basis functions for each shape, a dictionary whose span includes the semantic functions provided for that shape. Even though our shapes have independent discretizations and no functional correspondences are provided, the network is able to generate latent bases, in a consistent order, that reflect the shared semantic structure among the shapes. We demonstrate the effectiveness of our technique in various segmentation and keypoint selection applications.

##### Abstract (translated by Google)
各种3D语义属性（如分割蒙版，几何特征，关键点和材质）可以编码为3D几何上的按点探测功能。考虑到相关三维形状的集合，我们考虑如何联合分析不同形状的探测函数，以及如何使用神经网络发现常见的潜在结构 - 即使没有任何对应信息。我们的网络接受关于该点云上的形状几何形状和相关语义函数的点云表示的训练。这些功能表达对形状的共同语义理解，但不以任何方式协调。例如，在分段任务中，这些功能可以是任意形状部件组的指示器功能，其中特定的组合不涉及网络。我们的网络能够为每个形状生成一个小型基础函数字典，一个字典，其范围包括为该形状提供的语义函数。尽管我们的形状具有独立的离散性，并且没有提供函数对应关系，但网络能够以一致的顺序生成潜在基，以反映形状之间共享的语义结构。我们证明了我们的技术在各种分段和关键点选择应用中的有效性。

##### URL
[http://arxiv.org/abs/1805.09957](http://arxiv.org/abs/1805.09957)

##### PDF
[http://arxiv.org/pdf/1805.09957](http://arxiv.org/pdf/1805.09957)

