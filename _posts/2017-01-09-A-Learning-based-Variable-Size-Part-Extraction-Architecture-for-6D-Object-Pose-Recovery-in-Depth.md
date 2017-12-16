---
layout: post
title: "A Learning-based Variable Size Part Extraction Architecture for 6D Object Pose Recovery in Depth"
date: 2017-01-09 13:20:32
categories: arXiv_CV
tags: arXiv_CV Inference
author: Caner Sahin, Rigas Kouskouridas, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art techniques for 6D object pose recovery depend on occlusion-free point clouds to accurately register objects in 3D space. To deal with this shortcoming, we introduce a novel architecture called Iterative Hough Forest with Histogram of Control Points that is capable of estimating the 6D pose of occluded and cluttered objects given a candidate 2D bounding box. Our Iterative Hough Forest (IHF) is learnt using parts extracted only from the positive samples. These parts are represented with Histogram of Control Points (HoCP), a "scale-variant" implicit volumetric description, which we derive from recently introduced Implicit B-Splines (IBS). The rich discriminative information provided by the scale-variant HoCP features is leveraged during inference. An automatic variable size part extraction framework iteratively refines the object's initial pose that is roughly aligned due to the extraction of coarsest parts, the ones occupying the largest area in image pixels. The iterative refinement is accomplished based on finer (smaller) parts that are represented with more discriminative control point descriptors by using our Iterative Hough Forest. Experiments conducted on a publicly available dataset report that our approach show better registration performance than the state-of-the-art methods.

##### Abstract (translated by Google)
用于6D物体姿态恢复的最先进的技术取决于无遮挡的点云以在3D空间中准确地注册物体。为了解决这个缺点，我们引入了一个叫做迭代霍夫森林的控制点直方图的新颖架构，它能够估计给定候选二维边界框的遮挡和杂乱物体的6D姿态。我们使用仅从正样本中提取的部分来学习迭代霍夫森林（IHF）。这些部分用控制点直方图（HoCP）来表示，这是一个“尺度变量”隐式体积描述，我们从最近引入的隐式B样条（IBS）中得到。在推理过程中利用规模变化的HoCP特征提供的丰富的判别信息。自动可变尺寸部件提取框架通过迭代地改善由于提取最粗糙部分而占据图像像素中最大面积的对象的初始姿态，所述初始姿态大致对齐。迭代细化是基于更精细（更小）的部分来完成的，这些部分通过使用我们的迭代霍夫森林（Iterative Hough Forest）以更具有判别力的控制点描述符来表示。在公开可用的数据集上进行的实验报告显示，我们的方法比最先进的方法显示出更好的注册性能。

##### URL
[https://arxiv.org/abs/1701.02166](https://arxiv.org/abs/1701.02166)

##### PDF
[https://arxiv.org/pdf/1701.02166](https://arxiv.org/pdf/1701.02166)

