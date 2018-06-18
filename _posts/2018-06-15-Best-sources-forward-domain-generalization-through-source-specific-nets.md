---
layout: post
title: "Best sources forward: domain generalization through source-specific nets"
date: 2018-06-15 05:42:20
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Massimiliano Mancini, Samuel Rota Bul&#xf2;, Barbara Caputo, Elisa Ricci
mathjax: true
---

* content
{:toc}

##### Abstract
A long standing problem in visual object categorization is the ability of algorithms to generalize across different testing conditions. The problem has been formalized as a covariate shift among the probability distributions generating the training data (source) and the test data (target) and several domain adaptation methods have been proposed to address this issue. While these approaches have considered the single source-single target scenario, it is plausible to have multiple sources and require adaptation to any possible target domain. This last scenario, named Domain Generalization (DG), is the focus of our work. Differently from previous DG methods which learn domain invariant representations from source data, we design a deep network with multiple domain-specific classifiers, each associated to a source domain. At test time we estimate the probabilities that a target sample belongs to each source domain and exploit them to optimally fuse the classifiers predictions. To further improve the generalization ability of our model, we also introduced a domain agnostic component supporting the final classifier. Experiments on two public benchmarks demonstrate the power of our approach.

##### Abstract (translated by Google)
视觉对象分类中的一个长期存在的问题是算法在不同测试条件下推广的能力。该问题被形式化为产生训练数据（源）和测试数据（目标）的概率分布之间的协变量，并且已经提出了若干领域适应方法来解决该问题。虽然这些方法考虑了单一来源单一目标场景，但有多个来源并需要适应任何可能的目标域是合理的。这最后一个名为Domain Generalization（DG）的场景是我们工作的重点。与以前从源数据中学习域不变表达的DG方法不同，我们设计了一个具有多个特定于域的分类器的深度网络，每个分类器都与一个源域相关联。在测试时间，我们估计目标样本属于每个源域的概率，并利用它们来最优地融合分类器预测。为了进一步提高我们模型的泛化能力，我们还引入了一个支持最终分类器的领域不可知组件。两个公共基准的实验证明了我们方法的强大功能。

##### URL
[http://arxiv.org/abs/1806.05810](http://arxiv.org/abs/1806.05810)

##### PDF
[http://arxiv.org/pdf/1806.05810](http://arxiv.org/pdf/1806.05810)

