---
layout: post
title: "Positive-unlabeled convolutional neural networks for particle picking in cryo-electron micrographs"
date: 2018-03-22 02:24:22
categories: arXiv_CV
tags: arXiv_CV CNN Classification Gradient_Descent
author: Tristan Bepler, Andrew Morin, Alex J. Noble, Julia Brasch, Lawrence Shapiro, Bonnie Berger
mathjax: true
---

* content
{:toc}

##### Abstract
Cryo-electron microscopy (cryoEM) is fast becoming the preferred method for protein structure determination. Particle picking is a significant bottleneck in the solving of protein structures from single particle cryoEM. Hand labeling sufficient numbers of particles can take months of effort and current computationally based approaches are often ineffective. Here, we frame particle picking as a positive-unlabeled classification problem in which we seek to learn a convolutional neural network (CNN) to classify micrograph regions as particle or background from a small number of labeled positive examples and many unlabeled examples. However, model fitting with very few labeled data points is a challenging machine learning problem. To address this, we develop a novel objective function, GE-binomial, for learning model parameters in this context. This objective uses a newly-formulated generalized expectation criteria to learn effectively from unlabeled data when using minibatched stochastic gradient descent optimizers. On a high-quality publicly available cryoEM dataset and a difficult unpublished dataset supplied by the Shapiro lab, we show that CNNs trained with this objective classify particles accurately with very few positive training examples and outperform EMAN2's byRef method by a large margin even with fewer labeled training examples. Furthermore, we show that incorporating an autoencoder improves generalization when very few labeled data points are available. We also compare our GE-binomial method with other positive-unlabeled learning methods never before applied to particle picking. We expect our particle picking tool, Topaz, based on CNNs trained with GE-binomial, to be an essential component of single particle cryoEM analysis and our GE-binomial objective function to be widely applicable to positive-unlabeled classification problems.

##### Abstract (translated by Google)
低温电子显微镜（cryoEM）正在迅速成为蛋白质结构测定的首选方法。粒子挑选是解决单粒子冷冻电镜中蛋白质结构的重要瓶颈。手标记足够数量的粒子可能需要数月的努力，目前基于计算的方法通常无效。在这里，我们将粒子选取作为一个正向未标记的分类问题，其中我们试图学习卷积神经网络（CNN），从少数标记的正例和许多未标记的例子中将显微图像区域分类为粒子或背景。然而，模型拟合几乎没有标记的数据点是一个具有挑战性的机器学习问题。为了解决这个问题，我们开发了一种新的目标函数GE-binomial，用于在这种情况下学习模型参数。该目标使用新制定的广义期望标准来使用小标签随机梯度下降优化器从无标签数据有效地学习。在Shapiro实验室提供的高质量公开可用的cryoEM数据集和难以发表的数据集中，我们显示用该目标进行训练的CNNs通过很少的正面训练实例准确地进行粒子分类，并且在很大程度上优于EMAN2的byRef方法，即使使用较少的标记训练实例。此外，我们表明，只有极少数标记数据点可用时，合并自动编码器可以提高泛化能力。我们还将我们的GE二项式方法与从未应用于粒子拾取之前的其他正向未标记学习方法进行比较。我们期望我们的基于GE二项式培训的CNN的粒子选择工具Topaz成为单粒子冷冻电镜分析的重要组成部分，我们的GE二项目标函数可广泛应用于积极未标记的分类问题。

##### URL
[https://arxiv.org/abs/1803.08207](https://arxiv.org/abs/1803.08207)

##### PDF
[https://arxiv.org/pdf/1803.08207](https://arxiv.org/pdf/1803.08207)

