---
layout: post
title: "Spectral Filter Tracking"
date: 2017-07-18 10:40:08
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Relation
author: Zhen Cui (1), You yi Cai (2 and 3), Wen ming Zheng (3), Jian Yang (1) ((1) School of Computer Science and Engineering, Nanjing University of Science and Technology, Nanjing, China (2) the Department of Information Science and Engineering, Southeast University, Nanjing, China (3) the Key Laboratory of Child Development and Learning Science of Ministry of Education, Research Center for Learning Science, Southeast University, Nanjing, China)
mathjax: true
---

* content
{:toc}

##### Abstract
Visual object tracking is a challenging computer vision task with numerous real-world applications. Here we propose a simple but efficient Spectral Filter Tracking (SFT)method. To characterize rotational and translation invariance of tracking targets, the candidate image region is models as a pixelwise grid graph. Instead of the conventional graph matching, we convert the tracking into a plain least square regression problem to estimate the best center coordinate of the target. But different from the holistic regression of correlation filter based methods, SFT can operate on localized surrounding regions of each pixel (i.e.,vertex) by using spectral graph filters, which thus is more robust to resist local variations and cluttered background.To bypass the eigenvalue decomposition problem of the graph Laplacian matrix L, we parameterize spectral graph filters as the polynomial of L by spectral graph theory, in which L k exactly encodes a k-hop local neighborhood of each vertex. Finally, the filter parameters (i.e., polynomial coefficients) as well as feature projecting functions are jointly integrated into the regression model.

##### Abstract (translated by Google)
视觉对象跟踪是具有许多实际应用的具有挑战性的计算机视觉任务。这里我们提出一个简单而有效的光谱滤波跟踪（SFT）方法。为了表征跟踪目标的旋转和平移不变性，候选图像区域被模型化为像素方式的网格图。我们将跟踪转换成一个简单的最小二乘回归问题来替代传统的图匹配，以估计目标的最佳中心坐标。但是与基于相关滤波器的方法的整体回归不同，SFT可以通过使用谱图滤波器对每个像素（即顶点）的局部周围区域进行操作，从而更加稳健地抵抗局部变化和杂乱的背景。绕过特征值通过谱图理论将图谱滤波器参数化为L的多项式，其中L k精确地编码每个顶点的k跳局部邻域。最后，将滤波器参数（即多项式系数）以及特征投影函数联合地整合到回归模型中。

##### URL
[https://arxiv.org/abs/1707.05553](https://arxiv.org/abs/1707.05553)

##### PDF
[https://arxiv.org/pdf/1707.05553](https://arxiv.org/pdf/1707.05553)

