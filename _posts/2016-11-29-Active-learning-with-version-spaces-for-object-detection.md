---
layout: post
title: "Active learning with version spaces for object detection"
date: 2016-11-29 06:47:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Soumya Roy, Vinay P. Namboodiri, Arijit Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Given an image, we would like to learn to detect objects belonging to particular object categories. Common object detection methods train on large annotated datasets which are annotated in terms of bounding boxes that contain the object of interest. Previous works on object detection model the problem as a structured regression problem which ranks the correct bounding boxes more than the background ones. In this paper we develop algorithms which actively obtain annotations from human annotators for a small set of images, instead of all images, thereby reducing the annotation effort. Towards this goal, we make the following contributions: 1. We develop a principled version space based active learning method that solves for object detection as a structured prediction problem in a weakly supervised setting 2. We also propose two variants of the margin sampling strategy 3. We analyse the results on standard object detection benchmarks that show that with only 20% of the data we can obtain more than 95% of the localization accuracy of full supervision. Our methods outperform random sampling and the classical uncertainty-based active learning algorithms like entropy

##### Abstract (translated by Google)
给定一个图像，我们希望学习检测属于特定对象类别的对象。通用对象检测方法在大型注释数据集上进行训练，数据集按照包含感兴趣对象的边界框进行注释。以前的作品在物体检测上把这个问题看作是一个结构化的回归问题，它比正确的边界框排序更多。在本文中，我们开发了一些算法，主动从人类注释器获取一小组图像的注释，而不是所有的图像，从而减少了注释的工作量。针对这一目标，我们做出如下贡献：1，我们开发了一个基于原理的版本空间的主动学习方法，在弱监督的环境中将对象检测问题解决为一个结构化的预测问题。2，我们还提出了两个变体边缘抽样策略3我们分析了标准目标检测基准的结果，表明只有20％的数据可以获得95％以上的全面监督的定位精度。我们的方法胜过随机采样和经典的基于不确定性的主动学习算法，如熵

##### URL
[https://arxiv.org/abs/1611.07285](https://arxiv.org/abs/1611.07285)

