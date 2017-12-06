---
layout: post
title: "Scalable Bayesian Optimization Using Deep Neural Networks"
date: 2015-07-13 15:47:13
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Recognition
author: Jasper Snoek, Oren Rippel, Kevin Swersky, Ryan Kiros, Nadathur Satish, Narayanan Sundaram, Md. Mostofa Ali Patwary, Prabhat, Ryan P. Adams
---

* content
{:toc}

##### Abstract
Bayesian optimization is an effective methodology for the global optimization of functions with expensive evaluations. It relies on querying a distribution over functions defined by a relatively cheap surrogate model. An accurate model for this distribution over functions is critical to the effectiveness of the approach, and is typically fit using Gaussian processes (GPs). However, since GPs scale cubically with the number of observations, it has been challenging to handle objectives whose optimization requires many evaluations, and as such, massively parallelizing the optimization. In this work, we explore the use of neural networks as an alternative to GPs to model distributions over functions. We show that performing adaptive basis function regression with a neural network as the parametric form performs competitively with state-of-the-art GP-based approaches, but scales linearly with the number of data rather than cubically. This allows us to achieve a previously intractable degree of parallelism, which we apply to large scale hyperparameter optimization, rapidly finding competitive models on benchmark object recognition tasks using convolutional networks, and image caption generation using neural language models.

##### Abstract (translated by Google)
贝叶斯优化是对昂贵的评估功能进行全局优化的有效方法。它依赖于查询由相对便宜的代理模型定义的函数的分布。这种功能分布的准确模型对于该方法的有效性至关重要，并且通常使用高斯过程（GPs）来拟合。然而，由于全球定位系统与观测数量成正比，因此要处理优化需要许多评估的目标是非常具有挑战性的，因此大规模优化并行化。在这项工作中，我们探索使用神经网络作为GP的替代模型分布函数。我们展示了使用神经网络执行自适应基函数回归作为参数形式与最先进的基于GP的方法竞争性地执行，但是与数据的数量成线性地而非立体地缩放。这使我们能够实现先前难以处理的并行性，我们将其应用于大规模超参数优化，使用卷积网络快速找到基准对象识别任务的竞争模型，以及使用神经语言模型生成图像标题。

##### URL
[https://arxiv.org/abs/1502.05700](https://arxiv.org/abs/1502.05700)

