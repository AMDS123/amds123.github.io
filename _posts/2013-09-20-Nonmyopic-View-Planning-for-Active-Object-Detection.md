---
layout: post
title: "Nonmyopic View Planning for Active Object Detection"
date: 2013-09-20 21:35:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Nikolay Atanasov, Bharath Sankaran, Jerome Le Ny, George J. Pappas, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
One of the central problems in computer vision is the detection of semantically important objects and the estimation of their pose. Most of the work in object detection has been based on single image processing and its performance is limited by occlusions and ambiguity in appearance and geometry. This paper proposes an active approach to object detection by controlling the point of view of a mobile depth camera. When an initial static detection phase identifies an object of interest, several hypotheses are made about its class and orientation. The sensor then plans a sequence of views, which balances the amount of energy used to move with the chance of identifying the correct hypothesis. We formulate an active hypothesis testing problem, which includes sensor mobility, and solve it using a point-based approximate POMDP algorithm. The validity of our approach is verified through simulation and real-world experiments with the PR2 robot. The results suggest that our approach outperforms the widely-used greedy view point selection and provides a significant improvement over static object detection.

##### Abstract (translated by Google)
计算机视觉中的核心问题之一是检测语义上重要的对象及其姿态的估计。目标检测的大部分工作都是基于单个图像处理，其性能受到外观和几何中的遮挡和模糊限制。本文通过控制移动深度相机的视角提出了一种主动的物体检测方法。当一个初始的静态检测阶段识别出一个感兴趣的对象时，就会对它的类和方向进行几个假设。然后，传感器计划一系列视图，这些视图平衡了用于移动的能量的量和识别正确假设的机会。我们制定了一个主动的假设测试问题，其中包括传感器移动性，并使用基于点的近似POMDP算法来解决它。我们的方法的有效性通过PR2机器人的仿真和实际实验来验证。结果表明，我们的方法胜过广泛使用的贪婪视点选择，并提供了静态对象检测的重大改进。

##### URL
[https://arxiv.org/abs/1309.5401](https://arxiv.org/abs/1309.5401)

