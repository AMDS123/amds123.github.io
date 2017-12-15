---
layout: post
title: "Fast and Robust Hand Tracking Using Detection-Guided Optimization"
date: 2016-02-12 17:05:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Optimization Detection
author: Srinath Sridhar, Franziska Mueller, Antti Oulasvirta, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Markerless tracking of hands and fingers is a promising enabler for human-computer interaction. However, adoption has been limited because of tracking inaccuracies, incomplete coverage of motions, low framerate, complex camera setups, and high computational requirements. In this paper, we present a fast method for accurately tracking rapid and complex articulations of the hand using a single depth camera. Our algorithm uses a novel detection-guided optimization strategy that increases the robustness and speed of pose estimation. In the detection step, a randomized decision forest classifies pixels into parts of the hand. In the optimization step, a novel objective function combines the detected part labels and a Gaussian mixture representation of the depth to estimate a pose that best fits the depth. Our approach needs comparably less computational resources which makes it extremely fast (50 fps without GPU support). The approach also supports varying static, or moving, camera-to-scene arrangements. We show the benefits of our method by evaluating on public datasets and comparing against previous work.

##### Abstract (translated by Google)
手和手指的无标记跟踪是人机交互的有前景的推动者。然而，由于跟踪不准确，运动覆盖不完整，帧率低，摄像机设置复杂以及计算需求高等原因，采用受到限制。在本文中，我们提出了一种使用单个深度相机精确追踪手部快速和复杂关节的快速方法。我们的算法使用了一种新的检测引导优化策略，增加了姿态估计的鲁棒性和速度。在检测步骤中，随机决策森林将像素分类为手部分。在优化步骤中，新颖的目标函数将检测到的部分标签和深度的高斯混合表示组合以估计最适合深度的姿态。我们的方法需要相对较少的计算资源，这使得它非常快速（不支持GPU的50 fps）。该方法还支持不同的静态或移动摄像机到现场的布置。我们通过对公共数据集进行评估并与之前的工作进行比较来展示我们方法的好处。

##### URL
[https://arxiv.org/abs/1602.04124](https://arxiv.org/abs/1602.04124)

##### PDF
[https://arxiv.org/pdf/1602.04124](https://arxiv.org/pdf/1602.04124)

