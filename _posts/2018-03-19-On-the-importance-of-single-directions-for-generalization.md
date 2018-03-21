---
layout: post
title: "On the importance of single directions for generalization"
date: 2018-03-19 14:42:19
categories: arXiv_AI
tags: arXiv_AI
author: Ari S. Morcos, David G.T. Barrett, Neil C. Rabinowitz, Matthew Botvinick
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their ability to memorize large datasets, deep neural networks often achieve good generalization performance. However, the differences between the learned solutions of networks which generalize and those which do not remain unclear. Additionally, the tuning properties of single directions (defined as the activation of a single unit or some linear combination of units in response to some input) have been highlighted, but their importance has not been evaluated. Here, we connect these lines of inquiry to demonstrate that a network's reliance on single directions is a good predictor of its generalization performance, across networks trained on datasets with different fractions of corrupted labels, across ensembles of networks trained on datasets with unmodified labels, across different hyperparameters, and over the course of training. While dropout only regularizes this quantity up to a point, batch normalization implicitly discourages single direction reliance, in part by decreasing the class selectivity of individual units. Finally, we find that class selectivity is a poor predictor of task importance, suggesting not only that networks which generalize well minimize their dependence on individual units by reducing their selectivity, but also that individually selective units may not be necessary for strong network performance.

##### Abstract (translated by Google)
尽管他们能够记忆大型数据集，但深度神经网络通常可以实现良好的泛化性能。然而，泛化网络的学习解决方案和那些并不清楚的网络解决方案之间的差异。此外，单个方向的调谐特性（定义为响应某些输入的单个单元或某些线性单元组合的激活）已被突出显示，但其重要性尚未得到评估。在这里，我们将这些调查的线路连接起来，以证明网络对单一方向的依赖性能够很好地预测其泛化性能的一个很好的预测因子，跨不同数量的损坏标签的数据集上训练过的网络，跨越使用未修改标签的数据集上训练的网络合奏不同的超参数以及训练过程中。虽然退出只是将这个数量调整到一定程度，但批量标准化隐含地阻止单方向依赖，部分通过降低单个单位的类别选择性。最后，我们发现阶级选择性对于任务重要性来说是一个不好的预测指标，这不仅表明阶级选择性对于任务重要性来说是一个不好的预测指标，这不仅表明阶级选择性很好地预测了任务的重要性，这不仅表明阶级选择性很好地预测了任务的重要性，

##### URL
[http://arxiv.org/abs/1803.06959](http://arxiv.org/abs/1803.06959)

##### PDF
[http://arxiv.org/pdf/1803.06959](http://arxiv.org/pdf/1803.06959)

