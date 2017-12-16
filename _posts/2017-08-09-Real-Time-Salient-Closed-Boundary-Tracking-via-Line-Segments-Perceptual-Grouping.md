---
layout: post
title: "Real-Time Salient Closed Boundary Tracking via Line Segments Perceptual Grouping"
date: 2017-08-09 23:44:36
categories: arXiv_CV
tags: arXiv_CV Salient Tracking Detection
author: Xuebin Qin, Shida He, Camilo Perez Quintero, Abhineet Singh, Masood Dehghan, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel real-time method for tracking salient closed boundaries from video image sequences. This method operates on a set of straight line segments that are produced by line detection. The tracking scheme is coherently integrated into a perceptual grouping framework in which the visual tracking problem is tackled by identifying a subset of these line segments and connecting them sequentially to form a closed boundary with the largest saliency and a certain similarity to the previous one. Specifically, we define a new tracking criterion which combines a grouping cost and an area similarity constraint. The proposed criterion makes the resulting boundary tracking more robust to local minima. To achieve real-time tracking performance, we use Delaunay Triangulation to build a graph model with the detected line segments and then reduce the tracking problem to finding the optimal cycle in this graph. This is solved by our newly proposed closed boundary candidates searching algorithm called "Bidirectional Shortest Path (BDSP)". The efficiency and robustness of the proposed method are tested on real video sequences as well as during a robot arm pouring experiment.

##### Abstract (translated by Google)
本文提出了一种新颖的从视频图像序列中跟踪显着封闭边界的实时方法。这种方法运行在由线路检测产生的一组直线段上。跟踪方案被连贯地整合到知觉分组框架中，其中通过识别这些线段的子集并且将它们连续地连接以形成具有最大显着性和与前一个显着性相似的封闭边界来解决视觉跟踪问题。具体而言，我们定义了一个新的跟踪标准，它将分组成本和面积相似性约束相结合。所提出的标准使得由此产生的边界跟踪对局部最小值更为稳健。为了实现实时跟踪性能，我们使用Delaunay三角剖分建立一个检测线段的图模型，然后减少跟踪问题，以找到在这个图中的最佳周期。这是通过我们新提出的称为“双向最短路径（BDSP）”的封闭边界候选搜索算法来解决的。所提出的方法的效率和鲁棒性在真实视频序列以及机器人手臂浇注实验期间被测试。

##### URL
[https://arxiv.org/abs/1705.00360](https://arxiv.org/abs/1705.00360)

##### PDF
[https://arxiv.org/pdf/1705.00360](https://arxiv.org/pdf/1705.00360)

