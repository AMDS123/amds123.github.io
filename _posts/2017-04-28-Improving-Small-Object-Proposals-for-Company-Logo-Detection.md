---
layout: post
title: "Improving Small Object Proposals for Company Logo Detection"
date: 2017-04-28 11:30:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Christian Eggert, Dan Zecha, Stephan Brehm, Rainer Lienhart
mathjax: true
---

* content
{:toc}

##### Abstract
Many modern approaches for object detection are two-staged pipelines. The first stage identifies regions of interest which are then classified in the second stage. Faster R-CNN is such an approach for object detection which combines both stages into a single pipeline. In this paper we apply Faster R-CNN to the task of company logo detection. Motivated by its weak performance on small object instances, we examine in detail both the proposal and the classification stage with respect to a wide range of object sizes. We investigate the influence of feature map resolution on the performance of those stages. Based on theoretical considerations, we introduce an improved scheme for generating anchor proposals and propose a modification to Faster R-CNN which leverages higher-resolution feature maps for small objects. We evaluate our approach on the FlickrLogos dataset improving the RPN performance from 0.52 to 0.71 (MABO) and the detection performance from 0.52 to 0.67 (mAP).

##### Abstract (translated by Google)
许多现代的物体检测方法是两级管道。第一阶段确定感兴趣的地区，然后分类到第二阶段。更快的R-CNN就是这样一种物体检测方法，它将两个阶段组合成一个单一的管道。在本文中，我们将更快的R-CNN应用于公司标志检测的任务。由于其在小对象实例上表现不佳，我们在广泛的对象大小方面详细研究了提议和分类阶段。我们研究特征映射分辨率对这些阶段性能的影响。基于理论考虑，我们引入了一个改进的方案来生成锚点提案，并提出了一个更快的R-CNN的修改方案，该方法利用了较高分辨率的小对象特征地图。我们在FlickrLogos数据集上评估我们的方法，将RPN性能从0.52提高到0.71（MABO），检测性能从0.52提高到0.67（mAP）。

##### URL
[https://arxiv.org/abs/1704.08881](https://arxiv.org/abs/1704.08881)

