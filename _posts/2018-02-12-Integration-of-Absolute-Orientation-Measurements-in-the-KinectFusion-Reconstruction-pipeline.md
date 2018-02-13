---
layout: post
title: "Integration of Absolute Orientation Measurements in the KinectFusion Reconstruction pipeline"
date: 2018-02-12 11:18:40
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Silvio Giancola, Jens Schneider, Peter Wonka, Bernard S. Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we show how absolute orientation measurements provided by low-cost but high-fidelity IMU sensors can be integrated into the KinectFusion pipeline. We show that integration improves both runtime, robustness and quality of the 3D reconstruction. In particular, we use this orientation data to seed and regularize the ICP registration technique. We also present a technique to filter the pairs of 3D matched points based on the distribution of their distances. This filter is implemented efficiently on the GPU. Estimating the distribution of the distances helps control the number of iterations necessary for the convergence of the ICP algorithm. Finally, we show experimental results that highlight improvements in robustness, a speed-up of almost 12%, and a gain in tracking quality of 53% for the ATE metric on the Freiburg benchmark.

##### Abstract (translated by Google)
在本文中，我们将展示如何将低成本，高保真IMU传感器提供的绝对定向测量集成到KinectFusion流水线中。我们表明，集成提高了三维重建的运行时间，鲁棒性和质量。特别是，我们使用这种定向数据来种子和正规化ICP注册技术。我们还提出了一种基于距离分布对3D匹配点进行滤波的技术。该过滤器在GPU上高效实施。估计距离的分布有助于控制ICP算法收敛所需的迭代次数。最后，我们展示的实验结果强调了稳健性方面的改进，加速了近12％，并且在弗莱堡基准测试中的ATE指标上追踪质量的提高了53％。

##### URL
[http://arxiv.org/abs/1802.03980](http://arxiv.org/abs/1802.03980)

##### PDF
[http://arxiv.org/pdf/1802.03980](http://arxiv.org/pdf/1802.03980)

