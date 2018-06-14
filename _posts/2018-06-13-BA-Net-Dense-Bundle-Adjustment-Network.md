---
layout: post
title: "BA-Net: Dense Bundle Adjustment Network"
date: 2018-06-13 00:51:48
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Chengzhou Tang, Ping Tan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a neural network to solve the structure-from-motion (SfM) problem via feature bundle adjustment (BA), which explicitly enforces multi-view geometry constraints in the form of feature reprojection error. The whole pipeline is differentiable, so that the network can learn suitable feature representations that make the BA problem more trackable. Furthermore, this work introduces a novel depth parameterization to recover dense per-pixel depth. The network first generates some bases depth maps according to the input image, and optimizes the final depth as a linear combination of these bases via feature BA. The bases depth map generator is also learned via end-to-end training. The whole system nicely combines domain knowledge (i.e. hard-coded multi-view geometry constraints) and machine learning (i.e. feature learning and basis depth map generator learning) to address the challenging SfM problem. Experiments on large scale real data prove the success of the proposed method.

##### Abstract (translated by Google)
本文介绍了一种神经网络，通过特征束调整（BA）来解决运动结构（SfM）问题，该特征束调整以特征重投影误差的形式显式实施多视图几何约束。整个管道是可区分的，因此网络可以学习适当的特征表示，使BA问题更易于追踪。此外，这项工作引入了一种新颖的深度参数化来恢复密集的每像素深度。网络首先根据输入图像生成一些基础深度图，并通过特征BA将这些基础的线性组合优化为最终深度。基础深度图生成器也可以通过端到端的训练来学习。整个系统很好地将领域知识（即，硬编码的多视图几何约束）和机器学习（即特征学习和基础深度图生成器学习）结合起来，以解决具有挑战性的SfM问题。大规模实际数据的实验证明了该方法的成功。

##### URL
[http://arxiv.org/abs/1806.04807](http://arxiv.org/abs/1806.04807)

##### PDF
[http://arxiv.org/pdf/1806.04807](http://arxiv.org/pdf/1806.04807)

