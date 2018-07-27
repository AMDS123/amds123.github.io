---
layout: post
title: "Learning to guide task and motion planning using score-space representation"
date: 2018-07-26 05:35:18
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Beomjoon Kim, Zi Wang, Leslie Pack Kaelbling, Tomas Lozano-Perez
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a learning algorithm that speeds up the search in task and motion planning problems. Our algorithm proposes solutions to three different challenges that arise in learning to improve planning efficiency: what to predict, how to represent a planning problem instance, and how to transfer knowledge from one problem instance to another. We propose a method that predicts constraints on the search space based on a generic representation of a planning problem instance, called score-space, where we represent a problem instance in terms of the performance of a set of solutions attempted so far. Using this representation, we transfer knowledge, in the form of constraints, from previous problems based on the similarity in score space. We design a sequential algorithm that efficiently predicts these constraints, and evaluate it in three different challenging task and motion planning problems. Results indicate that our approach performs orders of magnitudes faster than an unguided planner

##### Abstract (translated by Google)
在本文中，我们提出了一种学习算法，可加快任务和运动规划问题的搜索速度。我们的算法为学习提高计划效率时出现的三个不同挑战提出了解决方案：预测内容，如何表示计划问题实例，以及如何将知识从一个问题实例转移到另一个问题实例。我们提出了一种方法，该方法基于规划问题实例的通用表示来预测对搜索空间的约束，称为得分空间，其中我们根据到目前为止尝试的一组解决方案的性能来表示问题实例。使用这种表示，我们以约束的形式从基于得分空间相似性的先前问题转移知识。我们设计了一种有效预测这些约束的顺序算法，并在三个不同的挑战任务和运动规划问题中对其进行评估。结果表明，我们的方法比非制导计划者执行的数量级更快

##### URL
[http://arxiv.org/abs/1807.09962](http://arxiv.org/abs/1807.09962)

##### PDF
[http://arxiv.org/pdf/1807.09962](http://arxiv.org/pdf/1807.09962)

