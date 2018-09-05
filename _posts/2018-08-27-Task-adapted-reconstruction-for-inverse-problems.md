---
layout: post
title: "Task adapted reconstruction for inverse problems"
date: 2018-08-27 11:44:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Jonas Adler, Sebastian Lunz, Olivier Verdier, Carola-Bibiane Sch&#xf6;nlieb, Ozan &#xd6;ktem
mathjax: true
---

* content
{:toc}

##### Abstract
The paper considers the problem of performing a task defined on a model parameter that is only observed indirectly through noisy data in an ill-posed inverse problem. A key aspect is to formalize the steps of reconstruction and task as appropriate estimators (non-randomized decision rules) in statistical estimation problems. The implementation makes use of (deep) neural networks to provide a differentiable parametrization of the family of estimators for both steps. These networks are combined and jointly trained against suitable supervised training data in order to minimize a joint differentiable loss function, resulting in an end-to-end task adapted reconstruction method. The suggested framework is generic, yet adaptable, with a plug-and-play structure for adjusting both the inverse problem and the task at hand. More precisely, the data model (forward operator and statistical model of the noise) associated with the inverse problem is exchangeable, e.g., by using neural network architecture given by a learned iterative method. Furthermore, any task that is encodable as a trainable neural network can be used. The approach is demonstrated on joint tomographic image reconstruction, classification and joint tomographic image reconstruction segmentation.

##### Abstract (translated by Google)
本文考虑了执行在模型参数上定义的任务的问题，该任务仅通过不适定的逆问题中的噪声数据间接观察到。一个关键方面是将重建和任务的步骤正式化为统计估计问题中的适当估计（非随机决策规则）。该实现利用（深度）神经网络为两个步骤提供估计器族的可微分参数化。这些网络被组合并针对合适的监督训练数据联合训练，以便最小化联合可微分损失函数，从而产生端到端任务适应的重建方法。建议的框架是通用的，但具有适应性，具有即插即用结构，用于调整逆问题和手头的任务。更确切地说，与逆问题相关联的数据模型（前向算子和噪声的统计模型）是可交换的，例如，通过使用由学习的迭代方法给出的神经网络架构。此外，可以使用任何可编码为可训练神经网络的任务。该方法在联合断层图像重建，分类和联合断层图像重建分割上得到证明。

##### URL
[http://arxiv.org/abs/1809.00948](http://arxiv.org/abs/1809.00948)

##### PDF
[http://arxiv.org/pdf/1809.00948](http://arxiv.org/pdf/1809.00948)

