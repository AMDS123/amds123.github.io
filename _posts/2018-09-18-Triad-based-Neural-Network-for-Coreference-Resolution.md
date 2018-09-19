---
layout: post
title: "Triad-based Neural Network for Coreference Resolution"
date: 2018-09-18 00:38:30
categories: arXiv_CL
tags: arXiv_CL Knowledge Prediction
author: Yuanliang Meng, Anna Rumshisky
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a triad-based neural network system that generates affinity scores between entity mentions for coreference resolution. The system simultaneously accepts three mentions as input, taking mutual dependency and logical constraints of all three mentions into account, and thus makes more accurate predictions than the traditional pairwise approach. Depending on system choices, the affinity scores can be further used in clustering or mention ranking. Our experiments show that a standard hierarchical clustering using the scores produces state-of-art results with gold mentions on the English portion of CoNLL 2012 Shared Task. The model does not rely on many handcrafted features and is easy to train and use. The triads can also be easily extended to polyads of higher orders. To our knowledge, this is the first neural network system to model mutual dependency of more than two members at mention level.

##### Abstract (translated by Google)
我们提出了一种基于三元组的神经网络系统，该系统在实体提及之间生成亲和力分数以进行共指消解。系统同时接受三个提及作为输入，考虑所有三个提及的相互依赖和逻辑约束，因此比传统的成对方法做出更准确的预测。根据系统选择，亲和力分数可以进一步用于聚类或提及排名。我们的实验表明，使用这些分数的标准层次聚类可以在CoNLL 2012共享任务的英语部分提供最佳结果。该模型不依赖于许多手工制作的功能，易于训练和使用。三元组也可以很容易地扩展到更高阶的多边形。据我们所知，这是第一个在提及级别上模拟两个以上成员之间相互依赖的神经网络系统。

##### URL
[http://arxiv.org/abs/1809.06491](http://arxiv.org/abs/1809.06491)

##### PDF
[http://arxiv.org/pdf/1809.06491](http://arxiv.org/pdf/1809.06491)

