---
layout: post
title: "Automatically Composing Representation Transformations as a Means for Generalization"
date: 2018-07-12 14:33:49
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Michael B. Chang, Abhishek Gupta, Sergey Levine, Thomas L. Griffiths
mathjax: true
---

* content
{:toc}

##### Abstract
How can we build a learner that can capture the essence of what makes a hard problem more complex than a simple one, break the hard problem along characteristic lines into smaller problems it knows how to solve, and sequentially solve the smaller problems until the larger one is solved? To work towards this goal, we focus on learning to generalize in a particular family of problems that exhibit compositional and recursive structure: their solutions can be found by composing in sequence a set of reusable partial solutions. Our key idea is to recast the problem of generalization as a problem of learning algorithmic procedures: we can formulate a solution to this family as a sequential decision-making process over transformations between representations. Our formulation enables the learner to learn the structure and parameters of its own computation graph with sparse supervision, make analogies between problems by transforming one problem representation to another, and exploit modularity and reuse to scale to problems of varying complexity. Experiments on solving a variety of multilingual arithmetic problems demonstrate that our method discovers the hierarchical decomposition of a problem into its subproblems, generalizes out of distribution to unseen problem classes, and extrapolates to harder versions of the same problem, yielding a 10-fold reduction in sample complexity compared to a monolithic recurrent neural network.

##### Abstract (translated by Google)
我们如何建立一个学习者能够捕捉到使一个难题比一个简单问题更复杂的本质，将特征线上的难题分解为它知道如何解决的小问题，并顺序解决较小的问题，直到较大的问题。解决了？为了实现这一目标，我们专注于学习在具有组合和递归结构的特定系列问题中进行推广：通过按顺序组合一组可重用的部分解决方案，可以找到他们的解决方案。我们的关键思想是将泛化问题重新定义为学习算法程序的问题：我们可以将这个家族的解决方案制定为表示之间转换的顺序决策过程。我们的公式使学习者能够通过稀疏监督来学习自己的计算图的结构和参数，通过将一个问题表示转换为另一个问题表示来对问题进行类比，并利用模块化和重用来扩展到不同复杂度的问题。解决各种多语言算术问题的实验表明，我们的方法发现问题的层次分解为其子问题，将分布推广到看不见的问题类，并推断出同一问题的更难版本，产生10倍的减少。与单片递归神经网络相比，样本复杂性。

##### URL
[http://arxiv.org/abs/1807.04640](http://arxiv.org/abs/1807.04640)

##### PDF
[http://arxiv.org/pdf/1807.04640](http://arxiv.org/pdf/1807.04640)

