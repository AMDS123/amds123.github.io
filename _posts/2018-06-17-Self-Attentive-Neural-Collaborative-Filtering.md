---
layout: post
title: "Self-Attentive Neural Collaborative Filtering"
date: 2018-06-17 20:58:12
categories: arXiv_AI
tags: arXiv_AI Attention Relation
author: Yi Tay, Shuai Zhang, Luu Anh Tuan, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
The dominant, state-of-the-art collaborative filtering (CF) methods today mainly comprises neural models. In these models, deep neural networks, e.g.., multi-layered perceptrons (MLP), are often used to model nonlinear relationships between user and item representations. As opposed to shallow models (e.g., factorization-based models), deep models generally provide a greater extent of expressiveness, albeit at the expense of impaired/restricted information flow. Consequently, the performance of most neural CF models plateaus at 3-4 layers, with performance stagnating or even degrading when increasing the model depth. As such, the question of how to train really deep networks in the context of CF remains unclear. To this end, this paper proposes a new technique that enables training neural CF models all the way up to 20 layers and beyond. Our proposed approach utilizes a new hierarchical self-attention mechanism that learns introspective intra-feature similarity across all the hidden layers of a standard MLP model. All in all, our proposed architecture, SA-NCF (Self-Attentive Neural Collaborative Filtering) is a densely connected self-matching model that can be trained up to 24 layers without plateau-ing, achieving wide performance margins against its competitors. On several popular benchmark datasets, our proposed architecture achieves up to an absolute improvement of 23%-58% and 1.3x to 2.8x fold improvement in terms of nDCG@10 and Hit Ratio (HR@10) scores over several strong neural CF baselines.

##### Abstract (translated by Google)
目前主流的最先进的协同过滤（CF）方法主要包括神经模型。在这些模型中，深度神经网络（例如，多层感知器（MLP））经常用于模拟用户和项目表示之间的非线性关系。与浅层模型（例如基于因子分解的模型）相反，深层模型通常提供更大程度的表现力，尽管以损害/限制的信息流为代价。因此，大多数神经CF模型在3-4层时表现平稳，当增加模型深度时性能停滞甚至退化。因此，如何在CF的背景下培养真正深度的网络的问题仍不清楚。为此，本文提出了一种新的技术，可以将神经CF模型一直训练到20层甚至更远。我们提出的方法利用了一种新的层次式自我注意机制，它可以学习标准MLP模型中所有隐藏层的内省内部特征相似性。总而言之，我们提出的架构SA-NCF（Self-Attentive Neural Collaborative Filtering）是一种密集连接的自匹配模型，可以训练多达24层而无需稳定，从而实现了与竞争对手相比的高性能余量。在几个流行的基准数据集中，我们提出的架构在nDCG @ 10和命中率（HR @ 10）分数方面的改进达到绝对改善23％-58％和1.3倍到2.8倍的改进，超过几个强大的神经CF基线。

##### URL
[http://arxiv.org/abs/1806.06446](http://arxiv.org/abs/1806.06446)

##### PDF
[http://arxiv.org/pdf/1806.06446](http://arxiv.org/pdf/1806.06446)

