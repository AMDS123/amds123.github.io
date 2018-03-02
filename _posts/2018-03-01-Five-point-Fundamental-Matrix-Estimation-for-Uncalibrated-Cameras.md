---
layout: post
title: "Five-point Fundamental Matrix Estimation for Uncalibrated Cameras"
date: 2018-03-01 09:08:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Daniel Barath
mathjax: true
---

* content
{:toc}

##### Abstract
We aim at estimating the fundamental matrix in two views from five correspondences of rotation invariant features obtained by e.g.\ the SIFT detector. The proposed minimal solver first estimates a homography from three correspondences assuming that they are co-planar and exploiting their rotational components. Then the fundamental matrix is obtained from the homography and two additional point pairs in general position. The proposed approach, combined with robust estimators like Graph-Cut RANSAC, is superior to other state-of-the-art algorithms both in terms of accuracy and number of iterations required. This is validated on synthesized data and $561$ real image pairs. Moreover, the tests show that requiring three points on a plane is not too restrictive in urban environment and locally optimized robust estimators lead to accurate estimates even if the points are not entirely co-planar. As a potential application, we show that using the proposed method makes two-view multi-motion estimation more accurate.

##### Abstract (translated by Google)
我们的目标是根据由SIFT检测器获得的旋转不变特征的五个对应关系估计两个视图中的基本矩阵。所提出的最小求解器首先根据三种对应关系估计单应性，假定它们是共面的并利用它们的旋转分量。然后，基本矩阵从单应性和两个附加点对在一般位置获得。所提出的方法与诸如Graph-Cut RANSAC的鲁棒估计器相结合，在精度和所需迭代次数方面优于其他最先进的算法。这是验证合成数据和$ 561 $真实图像对。此外，测试表明，在城市环境中，要求飞机上的三个点不是太严格，即使点不是完全共面的，局部优化的鲁棒估计器也能得出准确的估计。作为一种潜在的应用，我们表明使用所提出的方法使得两视图多运动估计更准确。

##### URL
[http://arxiv.org/abs/1803.00260](http://arxiv.org/abs/1803.00260)

##### PDF
[http://arxiv.org/pdf/1803.00260](http://arxiv.org/pdf/1803.00260)

