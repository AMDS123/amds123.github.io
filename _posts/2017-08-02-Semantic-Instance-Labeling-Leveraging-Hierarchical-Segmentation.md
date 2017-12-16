---
layout: post
title: "Semantic Instance Labeling Leveraging Hierarchical Segmentation"
date: 2017-08-02 22:04:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Steven Hickson, Irfan Essa, Henrik Christensen
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the approaches for indoor RGBD semantic la- beling focus on using pixels or superpixels to train a classi- fier. In this paper, we implement a higher level segmentation using a hierarchy of superpixels to obtain a better segmen- tation for training our classifier. By focusing on meaningful segments that conform more directly to objects, regardless of size, we train a random forest of decision trees as a clas- sifier using simple features such as the 3D size, LAB color histogram, width, height, and shape as specified by a his- togram of surface normals. We test our method on the NYU V2 depth dataset, a challenging dataset of cluttered indoor environments. Our experiments using the NYU V2 depth dataset show that our method achieves state of the art re- sults on both a general semantic labeling introduced by the dataset (floor, structure, furniture, and objects) and a more object specific semantic labeling. We show that training a classifier on a segmentation from a hierarchy of super pixels yields better results than training directly on super pixels, patches, or pixels as in previous work.

##### Abstract (translated by Google)
室内RGBD语义标签的大多数方法都着眼于使用像素或超像素来训练分类器。在本文中，我们使用超像素层次来实现更高层次的分割，以获得更好的分割用于训练我们的分类器。通过专注于更直接地适应对象的有意义的片断，不管大小如何，我们都会使用简单的特征（如指定的3D大小，LAB颜色直方图，宽度，高度和形状）来训练决策树的随机森林作为分类器通过表面法线的图表。我们在纽约大学V2深度数据集上测试我们的方法，这是一个混乱的室内环境的挑战性数据集。我们使用NYU V2深度数据集进行的实验表明，我们的方法实现了由数据集（地板，结构，家具和对象）引入的一般语义标注以及更具体的语义标注的最先进的结果。我们表明，训练一个超级像素层次结构的分割分类器会产生比以前的工作直接在超像素，补丁或像素上训练更好的结果。

##### URL
[https://arxiv.org/abs/1708.00946](https://arxiv.org/abs/1708.00946)

##### PDF
[https://arxiv.org/pdf/1708.00946](https://arxiv.org/pdf/1708.00946)

