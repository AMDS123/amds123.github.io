---
layout: post
title: "Intelligent Parameter Tuning in Optimization-based Iterative CT Reconstruction via Deep Reinforcement Learning"
date: 2017-11-01 16:04:24
categories: arXiv_CV
tags: arXiv_CV Regularization Reinforcement_Learning Optimization
author: Chenyang Shen, Yesenia Gonzalez, Liyuan Chen, Steve B. Jiang, Xun Jia
mathjax: true
---

* content
{:toc}

##### Abstract
A number of image-processing problems can be formulated as optimization problems. The objective function typically contains several terms specifically designed for different purposes. Parameters in front of these terms are used to control the relative weights among them. It is of critical importance to tune these parameters, as quality of the solution depends on their values. Tuning parameter is a relatively straightforward task for a human, as one can intelligently determine the direction of parameter adjustment based on the solution quality. Yet manual parameter tuning is not only tedious in many cases, but becomes impractical when a number of parameters exist in a problem. Aiming at solving this problem, this paper proposes an approach that employs deep reinforcement learning to train a system that can automatically adjust parameters in a human-like manner. We demonstrate our idea in an example problem of optimization-based iterative CT reconstruction with a pixel-wise total-variation regularization term. We set up a parameter tuning policy network (PTPN), which maps an CT image patch to an output that specifies the direction and amplitude by which the parameter at the patch center is adjusted. We train the PTPN via an end-to-end reinforcement learning procedure. We demonstrate that under the guidance of the trained PTPN for parameter tuning at each pixel, reconstructed CT images attain quality similar or better than in those reconstructed with manually tuned parameters.

##### Abstract (translated by Google)
许多图像处理问题可以被制定为优化问题。目标函数通常包含专门为不同目的而设计的几个术语。这些术语前面的参数用于控制它们之间的相对权重。调整这些参数非常重要，因为解决方案的质量取决于它们的价值。调谐参数对于人类来说是相对简单的任务，因为人们可以根据解的质量智能地确定参数调整的方向。然而，手动参数调整在许多情况下不仅枯燥乏味，而且在问题中存在多个参数时变得不切实际。针对这个问题，本文提出了一种采用深度强化学习的方法，训练一个能够以类人的方式自动调整参数的系统。我们用基于像素的总变化正则化术语来说明基于优化的迭代CT重建的示例问题中的我们的想法。我们建立了一个参数调整策略网络（PTPN），它将一个CT图像补丁映射到一个指定调整补丁中心参数的方向和幅度的输出。我们通过一个端到端的强化学习程序来训练PTPN。我们证明，在每个像素参数调整训练PTPN的指导下，重建的CT图像获得质量相似或更好的手动调整参数重建的那些。

##### URL
[https://arxiv.org/abs/1711.00414](https://arxiv.org/abs/1711.00414)

##### PDF
[https://arxiv.org/pdf/1711.00414](https://arxiv.org/pdf/1711.00414)

