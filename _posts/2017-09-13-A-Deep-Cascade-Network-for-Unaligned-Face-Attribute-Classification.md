---
layout: post
title: "A Deep Cascade Network for Unaligned Face Attribute Classification"
date: 2017-09-13 13:01:25
categories: arXiv_CV
tags: arXiv_CV Attention Face Classification Relation
author: Hui Ding, Hao Zhou, Shaohua Kevin Zhou, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Humans focus attention on different face regions when recognizing face attributes. Most existing face attribute classification methods use the whole image as input. Moreover, some of these methods rely on fiducial landmarks to provide defined face parts. In this paper, we propose a cascade network that simultaneously learns to localize face regions specific to attributes and performs attribute classification without alignment. First, a weakly-supervised face region localization network is designed to automatically detect regions (or parts) specific to attributes. Then multiple part-based networks and a whole-image-based network are separately constructed and combined together by the region switch layer and attribute relation layer for final attribute classification. A multi-net learning method and hint-based model compression is further proposed to get an effective localization model and a compact classification model, respectively. Our approach achieves significantly better performance than state-of-the-art methods on unaligned CelebA dataset, reducing the classification error by 30.9%.

##### Abstract (translated by Google)
识别人脸属性时，人们将注意力集中在不同的人脸区域。大多数现有的人脸属性分类方法都是将整个图像作为输入。而且，这些方法中的一些依靠基准标志来提供定义的面部部分。在本文中，我们提出了一个级联网络，它可以同时学习对属性特定的人脸区域进行本地化，并且执行属性分类而不需要对齐。首先，弱监督人脸区域定位网络被设计为自动检测属性特定的区域（或部分）。然后通过区域切换层和属性关系层将多个部分网络和全图像网络分别构建并组合在一起，进行最终的属性分类。进一步提出一种多网学习方法和基于提示的模型压缩，分别得到一个有效的定位模型和一个紧凑的分类模型。我们的方法比尚未对齐的CelebA数据集上的最先进的方法获得显着更好的性能，将分类错误减少了30.9％。

##### URL
[https://arxiv.org/abs/1709.03851](https://arxiv.org/abs/1709.03851)

##### PDF
[https://arxiv.org/pdf/1709.03851](https://arxiv.org/pdf/1709.03851)

