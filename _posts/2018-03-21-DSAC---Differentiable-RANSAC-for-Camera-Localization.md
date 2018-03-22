---
layout: post
title: "DSAC - Differentiable RANSAC for Camera Localization"
date: 2018-03-21 13:16:09
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Optimization Deep_Learning
author: Eric Brachmann, Alexander Krull, Sebastian Nowozin, Jamie Shotton, Frank Michel, Stefan Gumhold, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
RANSAC is an important algorithm in robust optimization and a central building block for many computer vision applications. In recent years, traditionally hand-crafted pipelines have been replaced by deep learning pipelines, which can be trained in an end-to-end fashion. However, RANSAC has so far not been used as part of such deep learning pipelines, because its hypothesis selection procedure is non-differentiable. In this work, we present two different ways to overcome this limitation. The most promising approach is inspired by reinforcement learning, namely to replace the deterministic hypothesis selection by a probabilistic selection for which we can derive the expected loss w.r.t. to all learnable parameters. We call this approach DSAC, the differentiable counterpart of RANSAC. We apply DSAC to the problem of camera localization, where deep learning has so far failed to improve on traditional approaches. We demonstrate that by directly minimizing the expected loss of the output camera poses, robustly estimated by RANSAC, we achieve an increase in accuracy. In the future, any deep learning pipeline can use DSAC as a robust optimization component.

##### Abstract (translated by Google)
RANSAC是稳健优化中的重要算法，也是许多计算机视觉应用的中心构建模块。近年来，传统上手工制作的管道已被深度学习管道所取代，这些管道可以以端到端的方式进行培训。然而，迄今为止，RANSAC并未被用作这种深度学习管道的一部分，因为它的假设选择过程是不可区分的。在这项工作中，我们提出了两种不同的方法来克服这个限制。最有前途的方法受强化学习的启发，即用确定性假设选择替换概率选择，我们可以推导出预期损失w.r.t.到所有可学习的参数。我们将这种方法称为DSAC，即RANSAC的可区分对象。我们将DSAC应用于摄像机本地化问题，到目前为止，深度学习在传统方法上未能改进。我们证明，通过直接最小化输出相机姿态的预期损失，通过RANSAC进行稳健估计，我们实现了准确度的提高。将来，任何深度学习管道都可以使用DSAC作为强大的优化组件。

##### URL
[http://arxiv.org/abs/1611.05705](http://arxiv.org/abs/1611.05705)

##### PDF
[http://arxiv.org/pdf/1611.05705](http://arxiv.org/pdf/1611.05705)

