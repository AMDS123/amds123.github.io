---
layout: post
title: "Multi-Target Tracking in Multiple Non-Overlapping Cameras using Constrained Dominant Sets"
date: 2017-06-19 22:34:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Optimization Detection
author: Yonatan Tariku Tesfaye, Eyasu Zemene, Andrea Prati, Marcello Pelillo, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a unified three-layer hierarchical approach for solving tracking problems in multiple non-overlapping cameras is proposed. Given a video and a set of detections (obtained by any person detector), we first solve within-camera tracking employing the first two layers of our framework and, then, in the third layer, we solve across-camera tracking by merging tracks of the same person in all cameras in a simultaneous fashion. To best serve our purpose, a constrained dominant sets clustering (CDSC) technique, a parametrized version of standard quadratic optimization, is employed to solve both tracking tasks. The tracking problem is caste as finding constrained dominant sets from a graph. In addition to having a unified framework that simultaneously solves within- and across-camera tracking, the third layer helps link broken tracks of the same person occurring during within-camera tracking. In this work, we propose a fast algorithm, based on dynamics from evolutionary game theory, which is efficient and salable to large-scale real-world applications.

##### Abstract (translated by Google)
本文提出了一种统一的三层分层方法来解决多重非重叠相机中的跟踪问题。给定一个视频和一组检测器（由任何人检测器获得），我们首先使用我们框架的前两层解决摄像机内跟踪，然后在第三层中，我们通过合并轨迹所有相机中的同一人同时出现。为了最好地服务于我们的目的，采用约束优势集合聚类（CDSC）技术（标准二次优化的参数化版本）来解决两个跟踪任务。跟踪问题就是从图中找出约束支配集。除了具有同时解决摄像机内和摄像机跟踪的统一框架之外，第三层还有助于链接在摄像机内跟踪过程中发生的同一人的损坏轨迹。在这项工作中，我们提出了一个基于演化博弈理论的动态快速算法，它对于大规模的实际应用是高效和可销售的。

##### URL
[https://arxiv.org/abs/1706.06196](https://arxiv.org/abs/1706.06196)

##### PDF
[https://arxiv.org/pdf/1706.06196](https://arxiv.org/pdf/1706.06196)

