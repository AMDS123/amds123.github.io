---
layout: post
title: "3D Object Classification via Spherical Projections"
date: 2017-12-12 18:37:34
categories: arXiv_CV
tags: arXiv_CV Classification
author: Zhangjie Cao, Qixing Huang, Karthik Ramani
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new method for classifying 3D objects. Our main idea is to project a 3D object onto a spherical domain centered around its barycenter and develop neural network to classify the spherical projection. We introduce two complementary projections. The first captures depth variations of a 3D object, and the second captures contour-information viewed from different angles. Spherical projections combine key advantages of two main-stream 3D classification methods: image-based and 3D-based. Specifically, spherical projections are locally planar, allowing us to use massive image datasets (e.g, ImageNet) for pre-training. Also spherical projections are similar to voxel-based methods, as they encode complete information of a 3D object in a single neural network capturing dependencies across different views. Our novel network design can fully utilize these advantages. Experimental results on ModelNet40 and ShapeNetCore show that our method is superior to prior methods.

##### Abstract (translated by Google)
在本文中，我们介绍一种分类三维物体的新方法。我们的主要想法是将3D对象投影到以重心为中心的球形域上，并开发神经网络来分类球形投影。我们介绍两个互补的预测。第一个捕捉3D对象的深度变化，第二个捕捉从不同角度观看的轮廓信息。球面投影结合了两种主流3D分类方法的关键优势：基于图像的和基于3D的。具体而言，球面投影是局部平面的，使我们能够使用海量图像数据集（如ImageNet）进行预训练。另外，球面投影与基于体素的方法类似，因为它们在单个神经网络中编码3D对象的完整信息，捕获不同视图之间的依赖关系。我们新颖的网络设计可以充分利用这些优势。 ModelNet40和ShapeNetCore的实验结果表明，我们的方法优于先前的方法。

##### URL
[https://arxiv.org/abs/1712.04426](https://arxiv.org/abs/1712.04426)

##### PDF
[https://arxiv.org/pdf/1712.04426](https://arxiv.org/pdf/1712.04426)

