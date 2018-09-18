---
layout: post
title: "Efficient Multitask Feature and Relationship Learning"
date: 2018-09-16 21:35:41
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Han Zhao, Otilia Stretcu, Alex Smola, Geoff Gordon
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a multitask learning problem, in which several predictors are learned jointly. Prior research has shown that learning the relations between tasks, and between the input features, together with the predictor, can lead to better generalization and interpretability, which proved to be useful for applications in many domains. In this paper, we consider a formulation of multitask learning that learns the relationships both between tasks and between features, represented through a task covariance and a feature covariance matrix, respectively. First, we demonstrate that existing methods proposed for this problem present an issue that may lead to ill-posed optimization. We then propose an alternative formulation, as well as an efficient algorithm to optimize it. Using ideas from optimization and graph theory, we propose an efficient coordinate-wise minimization algorithm that has a closed form solution for each block subproblem. Our experiments show that the proposed optimization method is orders of magnitude faster than its competitors. We also provide a nonlinear extension that is able to achieve better generalization than existing methods.

##### Abstract (translated by Google)
我们考虑一个多任务学习问题，其中共同学习了几个预测因子。先前的研究表明，学习任务之间以及输入特征之间的关系以及预测器可以导致更好的泛化和可解释性，这被证明对许多领域中的应用有用。在本文中，我们考虑一种多任务学习的公式，它分别通过任务协方差和特征协方差矩阵来学习任务之间和特征之间的关系。首先，我们证明为此问题提出的现有方法存在可能导致不适当优化的问题。然后，我们提出了一种替代配方，以及一种优化它的有效算法。使用来自优化和图论的思想，我们提出了一种有效的坐标最小化算法，该算法具有针对每个块子问题的闭合形式解。我们的实验表明，所提出的优化方法比竞争对手快几个数量级。我们还提供了一种非线性扩展，能够比现有方法实现更好的泛化。

##### URL
[http://arxiv.org/abs/1702.04423](http://arxiv.org/abs/1702.04423)

##### PDF
[http://arxiv.org/pdf/1702.04423](http://arxiv.org/pdf/1702.04423)

