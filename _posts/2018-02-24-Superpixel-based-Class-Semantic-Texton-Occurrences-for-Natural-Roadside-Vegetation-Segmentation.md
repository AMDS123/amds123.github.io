---
layout: post
title: "Superpixel based Class-Semantic Texton Occurrences for Natural Roadside Vegetation Segmentation"
date: 2018-02-24 01:51:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Ligang Zhang, Brijesh Verma
mathjax: true
---

* content
{:toc}

##### Abstract
Vegetation segmentation from roadside data is a field that has received relatively little attention in present studies, but can be of great potentials in a wide range of real-world applications, such as road safety assessment and vegetation condition monitoring. In this paper, we present a novel approach that generates class-semantic color-texture textons and aggregates superpixel based texton occurrences for vegetation segmentation in natural roadside images. Pixel-level class-semantic textons are first learnt by generating two individual sets of bag-of-word visual dictionaries from color and filter-bank texture features separately for each object class using manually cropped training data. For a testing image, it is first oversegmented into a set of homogeneous superpixels. The color and texture features of all pixels in each superpixel are extracted and further mapped to one of the learnt textons using the nearest distance metric, resulting in a color and a texture texton occurrence matrix. The color and texture texton occurrences are aggregated using a linear mixing method over each superpixel and the segmentation is finally achieved using a simple yet effective majority voting strategy. Evaluations on two public image datasets from videos collected by the Department of Transport and Main Roads (DTMR), Queensland, Australia, and a public roadside grass dataset show high accuracy of the proposed approach. We also demonstrate the effectiveness of the approach for vegetation segmentation in real-world scenarios.

##### Abstract (translated by Google)
路边数据中的植被分割是一个在当前研究中较少受到关注的领域，但在广泛的现实应用中，如道路安全评估和植被状况监测，具有很大的潜力。在本文中，我们提出了一种新颖的方法，生成类语义颜色纹理textons和聚合超像素为基础的texttone发生植被分割自然路边图像。首先通过使用手动裁剪的训练数据为每个对象类别分别生成来自颜色和滤波器组纹理特征的两组单词视觉词典来学习像素级别语义文本。对于测试图像，它首先被分解为一组均匀的超像素。提取每个超像素中所有像素的颜色和纹理特征，并使用最近的距离度量将其进一步映射到学习的文本之一，从而产生颜色和纹理文本产生矩阵。在每个超像素上使用线性混合方法来聚合颜色和纹理文本出现，并且使用简单而有效的多数投票策略最终实现分割。澳大利亚昆士兰州交通和主要道路部门（DTMR）收集的视频和公共路边草地数据集中的两幅公共图像数据集的评估显示了该方法的高精度。我们还展示了真实世界中植被分割方法的有效性。

##### URL
[http://arxiv.org/abs/1802.08781](http://arxiv.org/abs/1802.08781)

##### PDF
[http://arxiv.org/pdf/1802.08781](http://arxiv.org/pdf/1802.08781)

