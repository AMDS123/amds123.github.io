---
layout: post
title: "Light Source Estimation with Analytical Path-tracing"
date: 2017-01-15 19:15:39
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Mike Kasper, Nima Keivan, Gabe Sibley, Christoffer Heckman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel algorithm for light source estimation in scenes reconstructed with a RGB-D camera based on an analytically-derived formulation of path-tracing. Our algorithm traces the reconstructed scene with a custom path-tracer and computes the analytical derivatives of the light transport equation from principles in optics. These derivatives are then used to perform gradient descent, minimizing the photometric error between one or more captured reference images and renders of our current lighting estimation using an environment map parameterization for light sources. We show that our approach of modeling all light sources as points at infinity approximates lights located near the scene with surprising accuracy. Due to the analytical formulation of derivatives, optimization to the solution is considerably accelerated. We verify our algorithm using both real and synthetic data.

##### Abstract (translated by Google)
我们提出了一种基于分析导出的路径跟踪公式的RGB-D相机重建场景中的光源估计新算法。我们的算法使用自定义路径追踪器追踪重建场景，并根据光学原理计算光传输方程的解析导数。然后使用这些导数来执行梯度下降，最小化一个或多个捕获的参考图像之间的光度误差，并使用光源的环境地图参数化呈现我们当前的照明估计。我们表明，我们将所有光源建模为无穷远点的方法接近位于场景附近的灯具，并且具有惊人的准确性。由于衍生物的分析性制定，对解决方案的优化显着加速。我们使用真实和合成数据来验证我们的算法。

##### URL
[https://arxiv.org/abs/1701.04101](https://arxiv.org/abs/1701.04101)

##### PDF
[https://arxiv.org/pdf/1701.04101](https://arxiv.org/pdf/1701.04101)

