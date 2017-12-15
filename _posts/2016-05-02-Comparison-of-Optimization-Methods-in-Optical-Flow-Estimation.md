---
layout: post
title: "Comparison of Optimization Methods in Optical Flow Estimation"
date: 2016-05-02 17:21:22
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Noranart Vesdapunt, Utkarsh Sinha
mathjax: true
---

* content
{:toc}

##### Abstract
Optical flow estimation is a widely known problem in computer vision introduced by Gibson, J.J(1950) to describe the visual perception of human by stimulus objects. Estimation of optical flow model can be achieved by solving for the motion vectors from region of interest in the the different timeline. In this paper, we assumed slightly uniform change of velocity between two nearby frames, and solve the optical flow problem by traditional method, Lucas-Kanade(1981). This method performs minimization of errors between template and target frame warped back onto the template. Solving minimization steps requires optimization methods which have diverse convergence rate and error. We explored first and second order optimization methods, and compare their results with Gauss-Newton method in Lucas-Kanade. We generated 105 videos with 10,500 frames by synthetic objects, and 10 videos with 1,000 frames from real world footage. Our experimental results could be used as tuning parameters for Lucas-Kanade method.

##### Abstract (translated by Google)
光流估计是Gibson，J.J（1950）介绍的计算机视觉中众所周知的一个问题，用来描述刺激物体对人的视觉感受。光流模型的估计可以通过在不同时间线上求解来自感兴趣区域的运动矢量来实现。在本文中，我们假设两个相邻帧之间的速度稍微变化一致，并用传统方法Lucas-Kanade（1981）解决光流问题。该方法执行模板和目标框架之间的错误的最小化。求解最小化步骤需要具有不同收敛速度和误差的优化方法。我们探索了一阶和二阶优化方法，并将其结果与卢卡斯 - 卡纳德的Gauss-Newton方法进行比较。我们通过合成对象生成了105个105帧的视频，以及来自真实世界素材的1000帧的10个视频。我们的实验结果可以用作Lucas-Kanade方法的调整参数。

##### URL
[https://arxiv.org/abs/1605.00572](https://arxiv.org/abs/1605.00572)

##### PDF
[https://arxiv.org/pdf/1605.00572](https://arxiv.org/pdf/1605.00572)

