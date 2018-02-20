---
layout: post
title: "Gradient-Based Meta-Learning with Learned Layerwise Metric and Subspace"
date: 2018-02-19 07:40:00
categories: arXiv_CV
tags: arXiv_CV Classification Gradient_Descent
author: Yoonho Lee, Seungjin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Gradient-based meta-learning has been shown to be expressive enough to approximate any learning algorithm. While previous such methods have been successful in meta-learning tasks, they resort to simple gradient descent during meta-testing. Our primary contribution is the {\em MT-net}, which enables the meta-learner to learn on each layer's activation space a subspace that the task-specific learner performs gradient descent on. Additionally, a task-specific learner of an {\em MT-net} performs gradient descent with respect to a meta-learned distance metric, which warps the activation space to be more sensitive to task identity. We demonstrate that the dimension of this learned subspace reflects the complexity of the task-specific learner's adaptation task, and also that our model is less sensitive to the choice of initial learning rates than previous gradient-based meta-learning methods. Our method achieves state-of-the-art or comparable performance on few-shot classification and regression tasks.

##### Abstract (translated by Google)
已经证明基于渐变的元学习足以表达任何学习算法。尽管以前的这些方法在元学习任务中取得了成功，但他们在元测试中采用了简单的渐变下降法。我们的主要贡献是{\ em MT-net}，它使得元学习者能够在每个层的激活空间上学习特定任务学习者执行梯度下降的子空间。另外，针对任务特定的{\ em MT-net}学习者相对于元学习距离度量执行梯度下降，这缩小了激活空间对任务身份更敏感。我们证明了这个学习子空间的维度反映了任务特定学习者适应任务的复杂性，并且我们的模型对初始学习率的选择比先前的基于梯度的元学习方法更不敏感。我们的方法在少数分类和回归任务上实现了最先进的或可比较的性能。

##### URL
[http://arxiv.org/abs/1801.05558](http://arxiv.org/abs/1801.05558)

##### PDF
[http://arxiv.org/pdf/1801.05558](http://arxiv.org/pdf/1801.05558)

