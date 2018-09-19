---
layout: post
title: "A White-Noise-On-Jerk Motion Prior for Continuous-Time Trajectory Estimation on SE"
date: 2018-09-18 03:36:59
categories: arXiv_RO
tags: arXiv_RO
author: Tim Y. Tang, David J. Yoon, Timothy D. Barfoot
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous trajectory estimation and mapping (STEAM) offers an efficient approach to continuous-time trajectory estimation, by representing the trajectory as a Gaussian process (GP). Previous formulations of the STEAM framework use a GP prior that assumes white-noise-on-acceleration, with the prior mean encouraging constant body-centric velocity. We show that such a prior cannot sufficiently represent trajectory sections with non-zero acceleration, resulting in a bias to the posterior estimates. 
 This paper derives a novel motion prior that assumes white-noise-on-jerk, where the prior mean encourages constant body-centric acceleration. With the new prior, we formulate a variation of STEAM that estimates the pose, body-centric velocity, and body-centric acceleration. By evaluating across several datasets, we show that the new prior greatly outperforms the white-noise-on-acceleration prior in terms of solution accuracy.

##### Abstract (translated by Google)
通过将轨迹表示为高斯过程（GP），同时轨迹估计和映射（STEAM）提供了连续时间轨迹估计的有效方法。 STEAM框架的先前配方使用GP先前假设加速时的白噪声，先前的平均值鼓励恒定的以身体为中心的速度。我们证明这样的先验不能充分地表示具有非零加速度的轨迹部分，导致对后验估计的偏差。
 本文推导出一种新的运动先验，它假设是白噪声，其中先验均值鼓励恒定的以身体为中心的加速度。通过新的先验，我们制定了STEAM的变体，用于估计姿势，身体中心速度和以身体为中心的加速度。通过对几个数据集进行评估，我们发现新的先验在解决方案精度方面大大优于先前的白噪声加速度。

##### URL
[http://arxiv.org/abs/1809.06518](http://arxiv.org/abs/1809.06518)

##### PDF
[http://arxiv.org/pdf/1809.06518](http://arxiv.org/pdf/1809.06518)

