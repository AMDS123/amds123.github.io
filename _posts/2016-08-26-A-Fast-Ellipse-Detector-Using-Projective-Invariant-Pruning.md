---
layout: post
title: "A Fast Ellipse Detector Using Projective Invariant Pruning"
date: 2016-08-26 14:25:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Qi Jia, Xin Fan, Zhongxuan Luo, Lianbo Song, Tie Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting elliptical objects from an image is a central task in robot navigation and industrial diagnosis where the detection time is always a critical issue. Existing methods are hardly applicable to these real-time scenarios of limited hardware resource due to the huge number of fragment candidates (edges or arcs) for fitting ellipse equations. In this paper, we present a fast algorithm detecting ellipses with high accuracy. The algorithm leverage a newly developed projective invariant to significantly prune the undesired candidates and to pick out elliptical ones. The invariant is able to reflect the intrinsic geometry of a planar curve, giving the value of -1 on any three collinear points and +1 for any six points on an ellipse. Thus, we apply the pruning and picking by simply comparing these binary values. Moreover, the calculation of the invariant only involves the determinant of a 3*3 matrix. Extensive experiments on three challenging data sets with 650 images demonstrate that our detector runs 20%-50% faster than the state-of-the-art algorithms with the comparable or higher precision.

##### Abstract (translated by Google)
从图像中检测椭圆形物体是机器人导航和工业诊断的中心任务，其中检测时间始终是关键问题。由于用于拟合椭圆方程的片段候选（边或弧）数量庞大，所以现有方法几乎不适用于这些有限硬件资源的实时情况。在本文中，我们提出了一个高精度检测椭圆的快速算法。该算法利用新开发的投影不变量来显着修剪不希望的候选者并挑选出椭圆形的候选者。不变量能够反映平面曲线的固有几何形状，在任意三个共线点上给出-1值，并且在椭圆上给出六个点上的+1。因此，我们通过简单地比较这些二进制值来应用修剪和挑选。此外，不变量的计算仅涉及3 * 3矩阵的行列式。对具有650个图像的三个具有挑战性的数据集的大量实验证明，我们的检测器比具有相当或更高精度的最先进算法运行速度快20％-50％。

##### URL
[https://arxiv.org/abs/1608.07470](https://arxiv.org/abs/1608.07470)

##### PDF
[https://arxiv.org/pdf/1608.07470](https://arxiv.org/pdf/1608.07470)

