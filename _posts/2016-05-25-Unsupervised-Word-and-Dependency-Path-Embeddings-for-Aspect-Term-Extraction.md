---
layout: post
title: "Unsupervised Word and Dependency Path Embeddings for Aspect Term Extraction"
date: 2016-05-25 12:01:46
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Yichun Yin, Furu Wei, Li Dong, Kaimeng Xu, Ming Zhang, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a novel approach to aspect term extraction based on unsupervised learning of distributed representations of words and dependency paths. The basic idea is to connect two words (w1 and w2) with the dependency path (r) between them in the embedding space. Specifically, our method optimizes the objective w1 + r = w2 in the low-dimensional space, where the multi-hop dependency paths are treated as a sequence of grammatical relations and modeled by a recurrent neural network. Then, we design the embedding features that consider linear context and dependency context information, for the conditional random field (CRF) based aspect term extraction. Experimental results on the SemEval datasets show that, (1) with only embedding features, we can achieve state-of-the-art results; (2) our embedding method which incorporates the syntactic information among words yields better performance than other representative ones in aspect term extraction.

##### Abstract (translated by Google)
在本文中，我们开发了一种基于无监督学习的单词和依赖路径的分布式表示的方法术语提取的新方法。其基本思想是将两个单词（w1和w2）与它们之间的依赖路径（r）在嵌入空间中相连。具体而言，我们的方法在低维空间中优化目标w1 + r = w2，其中多跳依赖路径被视为一系列语法关系，并由递归神经网络建模。然后，针对基于条件随机场（CRF）的方面项提取，设计考虑线性上下文和依赖上下文信息的嵌入特征。在SemEval数据集上的实验结果表明，（1）只有嵌入特征，才能达到最新的结果; （2）将词间句法信息结合起来的嵌入方法在方面词提取中比其他代表性词汇提取方法有更好的性能。

##### URL
[https://arxiv.org/abs/1605.07843](https://arxiv.org/abs/1605.07843)

##### PDF
[https://arxiv.org/pdf/1605.07843](https://arxiv.org/pdf/1605.07843)

