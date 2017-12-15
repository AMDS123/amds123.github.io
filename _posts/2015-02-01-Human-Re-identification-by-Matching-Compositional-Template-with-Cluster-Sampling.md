---
layout: post
title: "Human Re-identification by Matching Compositional Template with Cluster Sampling"
date: 2015-02-01 13:47:49
categories: arXiv_CV
tags: arXiv_CV Re-identification Relation
author: Yuanlu Xu, Liang Lin, Wei-Shi Zheng, Xiaobai Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at a newly raising task in visual surveillance: re-identifying people at a distance by matching body information, given several reference examples. Most of existing works solve this task by matching a reference template with the target individual, but often suffer from large human appearance variability (e.g. different poses/views, illumination) and high false positives in matching caused by conjunctions, occlusions or surrounding clutters. Addressing these problems, we construct a simple yet expressive template from a few reference images of a certain individual, which represents the body as an articulated assembly of compositional and alternative parts, and propose an effective matching algorithm with cluster sampling. This algorithm is designed within a candidacy graph whose vertices are matching candidates (i.e. a pair of source and target body parts), and iterates in two steps for convergence. (i) It generates possible partial matches based on compatible and competitive relations among body parts. (ii) It confirms the partial matches to generate a new matching solution, which is accepted by the Markov Chain Monte Carlo (MCMC) mechanism. In the experiments, we demonstrate the superior performance of our approach on three public databases compared to existing methods.

##### Abstract (translated by Google)
本文旨在提出一个新的视觉监控任务：通过匹配身体信息在远处重新识别人，给出几个参考例子。现有的大多数作品通过将参考模板与目标个体进行匹配来解决这个任务，但是由于连接，遮挡或者周围的混乱而经常遭受大的人的外观可变性（例如不同的姿势/视图，照明）和高的误匹配。针对这些问题，我们从一个个体的几个参考图像构建了一个简单而富有表现力的模板，将其作为一个组合部分和替代部分的铰接组合，提出了一种有效的聚类抽样匹配算法。该算法设计在候选图中，其顶点与候选匹配（即一对源和目标身体部分），并在两个步骤迭代收敛。 （i）它基于身体部分之间的兼容和竞争关系产生可能的部分匹配。 （ii）确认部分匹配产生一个新的匹配解，这是马尔可夫链蒙特卡罗（MCMC）机制所接受的。在实验中，我们证明了与现有方法相比，我们的方法在三个公共数据库上的优越性能。

##### URL
[https://arxiv.org/abs/1502.00256](https://arxiv.org/abs/1502.00256)

##### PDF
[https://arxiv.org/pdf/1502.00256](https://arxiv.org/pdf/1502.00256)

