---
layout: post
title: "Neural Best-Buddies: Sparse Cross-Domain Correspondence"
date: 2018-05-10 19:11:04
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Kfir Aberman, Jing Liao, Mingyi Shi, Dani Lischinski, Baoquan Chen, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
Correspondence between images is a fundamental problem in computer vision, with a variety of graphics applications. This paper presents a novel method for sparse cross-domain correspondence. Our method is designed for pairs of images where the main objects of interest may belong to different semantic categories and differ drastically in shape and appearance, yet still contain semantically related or geometrically similar parts. Our approach operates on hierarchies of deep features, extracted from the input images by a pre-trained CNN. Specifically, starting from the coarsest layer in both hierarchies, we search for Neural Best Buddies (NBB): pairs of neurons that are mutual nearest neighbors. The key idea is then to percolate NBBs through the hierarchy, while narrowing down the search regions at each level and retaining only NBBs with significant activations. Furthermore, in order to overcome differences in appearance, each pair of search regions is transformed into a common appearance. We evaluate our method via a user study, in addition to comparisons with alternative correspondence approaches. The usefulness of our method is demonstrated using a variety of graphics applications, including cross-domain image alignment, creation of hybrid images, automatic image morphing, and more.

##### Abstract (translated by Google)
图像之间的对应是计算机视觉中的一个基本问题，具有各种图形应用程序。本文提出了一种稀疏跨域对应的新方法。我们的方法是为图像对设计的，其中感兴趣的主要对象可以属于不同的语义类别，并且在形状和外观上有很大不同，但仍包含语义相关或几何相似的部分。我们的方法运用于深层特征的层次结构，通过预先训练的CNN从输入图像中提取。具体而言，从两个层次中最粗糙的层开始，我们搜索Neural Best Buddies（NBB）：相互最近邻的神经元对。关键的想法是通过层次渗透NBB，同时缩小每个层次的搜索区域并且仅保留具有显着激活的NBB。此外，为了克服外观上的差异，每一对搜索区域被转换成共同的外观。我们通过用户研究来评估我们的方法，以及与其他通信方法的比较。使用各种图形应用程序演示了我们方法的实用性，包括跨域图像对齐，混合图像的创建，自动图像变形等等。

##### URL
[http://arxiv.org/abs/1805.04140](http://arxiv.org/abs/1805.04140)

##### PDF
[http://arxiv.org/pdf/1805.04140](http://arxiv.org/pdf/1805.04140)

