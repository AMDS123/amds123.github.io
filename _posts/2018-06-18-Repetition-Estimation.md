---
layout: post
title: "Repetition Estimation"
date: 2018-06-18 23:30:23
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Tom F.H. Runia, Cees G.M. Snoek, Arnold W.M. Smeulders
mathjax: true
---

* content
{:toc}

##### Abstract
Visual repetition is ubiquitous in our world. It appears in human activity (sports, cooking), animal behavior (a bee's waggle dance), natural phenomena (leaves in the wind) and in urban environments (flashing lights). Estimating visual repetition from realistic video is challenging as periodic motion is rarely perfectly static and stationary. To better deal with realistic video, we elevate the static and stationary assumptions often made by existing work. Our spatiotemporal filtering approach, established on the theory of periodic motion, effectively handles a wide variety of appearances and requires no learning. Starting from motion in 3D we derive three periodic motion types by decomposition of the motion field into its fundamental components. In addition, three temporal motion continuities emerge from the field's temporal dynamics. For the 2D perception of 3D motion we consider the viewpoint relative to the motion; what follows are 18 cases of recurrent motion perception. To estimate repetition under all circumstances, our theory implies constructing a mixture of differential motion maps: gradient, divergence and curl. We temporally convolve the motion maps with wavelet filters to estimate repetitive dynamics. Our method is able to spatially segment repetitive motion directly from the temporal filter responses densely computed over the motion maps. For experimental verification of our claims, we use our novel dataset for repetition estimation, better-reflecting reality with non-static and non-stationary repetitive motion. On the task of repetition counting, we obtain favorable results compared to a deep learning alternative.

##### Abstract (translated by Google)
视觉重复在我们的世界中无处不在。它出现在人类活动（运动，烹饪），动物行为（一只蜜蜂的摇摆舞），自然现象（风中的叶子）和城市环境（闪烁的灯光）中。由于周期性运动很少完全静止且静止，因此从逼真视频估计视觉重复是具有挑战性的。为了更好地处理逼真的视频，我们提高了现有工作常常做出的静态和静态假设。我们根据周期性运动理论建立的时空滤波方法有效地处理了各种各样的外观并且不需要学习。从3D运动开始，我们通过将运动场分解为其基本成分来导出三种周期性运动类型。另外，三个时间运动连续性从场的时间动态出现。对于3D运动的2D感知，我们考虑相对于运动的视点;接下来是18例复发性运动知觉。为了估计在所有情况下的重复，我们的理论意味着构建差分运动图的混合：梯度，发散和卷曲。我们用小波滤波器对运动图进行时间卷积以估计重复动态。我们的方法能够直接根据在运动图上密集计算的时间滤波器响应在空间上分割重复运动。为了对我们的权利要求进行实验验证，我们使用我们的新颖数据集进行重复估计，更好地反映非静态和非静态重复运动的真实情况。关于重复计数的任务，与深度学习替代方法相比，我们获得了有利的结果。

##### URL
[http://arxiv.org/abs/1806.06984](http://arxiv.org/abs/1806.06984)

##### PDF
[http://arxiv.org/pdf/1806.06984](http://arxiv.org/pdf/1806.06984)

