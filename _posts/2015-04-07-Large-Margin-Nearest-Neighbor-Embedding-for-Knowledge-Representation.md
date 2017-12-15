---
layout: post
title: "Large Margin Nearest Neighbor Embedding for Knowledge Representation"
date: 2015-04-07 17:50:31
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Classification Prediction Quantitative Gradient_Descent Relation
author: Miao Fan, Qiang Zhou, Thomas Fang Zheng, Ralph Grishman
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional way of storing facts in triplets ({\it head\_entity, relation, tail\_entity}), abbreviated as ({\it h, r, t}), makes the knowledge intuitively displayed and easily acquired by mankind, but hardly computed or even reasoned by AI machines. Inspired by the success in applying {\it Distributed Representations} to AI-related fields, recent studies expect to represent each entity and relation with a unique low-dimensional embedding, which is different from the symbolic and atomic framework of displaying knowledge in triplets. In this way, the knowledge computing and reasoning can be essentially facilitated by means of a simple {\it vector calculation}, i.e. ${\bf h} + {\bf r} \approx {\bf t}$. We thus contribute an effective model to learn better embeddings satisfying the formula by pulling the positive tail entities ${\bf t^{+}}$ to get together and close to {\bf h} + {\bf r} ({\it Nearest Neighbor}), and simultaneously pushing the negatives ${\bf t^{-}}$ away from the positives ${\bf t^{+}}$ via keeping a {\it Large Margin}. We also design a corresponding learning algorithm to efficiently find the optimal solution based on {\it Stochastic Gradient Descent} in iterative fashion. Quantitative experiments illustrate that our approach can achieve the state-of-the-art performance, compared with several latest methods on some benchmark datasets for two classical applications, i.e. {\it Link prediction} and {\it Triplet classification}. Moreover, we analyze the parameter complexities among all the evaluated models, and analytical results indicate that our model needs fewer computational resources on outperforming the other methods.

##### Abstract (translated by Google)
传统的以三联体（{\ it head \ _entity，relation，tail \ _entity}）存储事实的方法，缩写为（{\ it h，r，t}），使得知识直观地被人类展示和获取，由AI机器计算甚至推理。受AI成功应用于AI相关领域的启发，最近的研究期望用独特的低维嵌入来表示每个实体和关系，这与用三联体显示知识的符号和原子框架是不同的。以这种方式，知识计算和推理可以通过简单的{\ it矢量计算}，即$ {\ bf h} + {\ bf r} \ approx {\ bf t} $来实质性地促进。因此，我们提供了一个有效的模型来学习更好的满足公式的嵌入，通过拉正尾实体$ {\ bf t ^ {+}} $在一起并且接近{\ bf h} + {\ bf r}它最近的邻居}），同时通过保持一个{\大的边距}，把负面$ {\ bf t ^ { - }} $从正面$ {\ bf t ^ {+}} $推开。我们还设计了一个相应的学习算法，以迭代方式有效地找到基于{随机梯度下降}的最优解。定量实验表明，我们的方法可以实现最先进的性能，与一些基准数据集上的几种最新的方法相比，这两种经典的应用，即{链路预测}和{三重分类}。此外，我们分析了所有评估模型之间的参数复杂性，分析结果表明，我们的模型在优于其他方法上需要更少的计算资源。

##### URL
[https://arxiv.org/abs/1504.01684](https://arxiv.org/abs/1504.01684)

##### PDF
[https://arxiv.org/pdf/1504.01684](https://arxiv.org/pdf/1504.01684)

