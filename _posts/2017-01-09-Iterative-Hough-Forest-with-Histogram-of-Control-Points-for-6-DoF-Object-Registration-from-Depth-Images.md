---
layout: post
title: "Iterative Hough Forest with Histogram of Control Points for 6 DoF Object Registration from Depth Images"
date: 2017-01-09 12:43:53
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference
author: Caner Sahin, Rigas Kouskouridas, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art techniques proposed for 6D object pose recovery depend on occlusion-free point clouds to accurately register objects in 3D space. To reduce this dependency, we introduce a novel architecture called Iterative Hough Forest with Histogram of Control Points that is capable of estimating occluded and cluttered objects' 6D pose given a candidate 2D bounding box. Our Iterative Hough Forest is learnt using patches extracted only from the positive samples. These patches are represented with Histogram of Control Points (HoCP), a "scale-variant" implicit volumetric description, which we derive from recently introduced Implicit B-Splines (IBS). The rich discriminative information provided by this scale-variance is leveraged during inference, where the initial pose estimation of the object is iteratively refined based on more discriminative control points by using our Iterative Hough Forest. We conduct experiments on several test objects of a publicly available dataset to test our architecture and to compare with the state-of-the-art.

##### Abstract (translated by Google)
针对6D对象姿态恢复提出的最先进的技术依赖于无遮挡点云以准确地在3D空间中注册对象。为了减少这种依赖性，我们引入了一种叫做迭代霍夫森林的新型结构，它具有控制点直方图，能够在给定候选二维边界框的情况下估计遮挡和杂乱物体的6D姿态。我们的迭代霍夫森林是使用仅从正样本中提取的补丁来学习的。这些补丁用控制点直方图（HoCP）表示，这是一个“尺度变量”隐式体积描述，我们从最近引入的隐式B样条（IBS）中得到。由这个尺度变量提供的丰富的判别信息在推理过程中被利用，其中通过使用我们的迭代霍夫森林，基于更多的判别控制点对对象的初始姿态估计进行迭代改进。我们在一个公开可用的数据集的多个测试对象上进行实验，以测试我们的体系结构并与最新的数据进行比较。

##### URL
[https://arxiv.org/abs/1603.02617](https://arxiv.org/abs/1603.02617)

##### PDF
[https://arxiv.org/pdf/1603.02617](https://arxiv.org/pdf/1603.02617)

