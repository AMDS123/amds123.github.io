---
layout: post
title: "Breaking Sticks and Ambiguities with Adaptive Skip-gram"
date: 2015-11-15 10:36:49
categories: arXiv_SD
tags: arXiv_SD Relation
author: Sergey Bartunov, Dmitry Kondrashkin, Anton Osokin, Dmitry Vetrov
mathjax: true
---

* content
{:toc}

##### Abstract
Recently proposed Skip-gram model is a powerful method for learning high-dimensional word representations that capture rich semantic relationships between words. However, Skip-gram as well as most prior work on learning word representations does not take into account word ambiguity and maintain only single representation per word. Although a number of Skip-gram modifications were proposed to overcome this limitation and learn multi-prototype word representations, they either require a known number of word meanings or learn them using greedy heuristic approaches. In this paper we propose the Adaptive Skip-gram model which is a nonparametric Bayesian extension of Skip-gram capable to automatically learn the required number of representations for all words at desired semantic resolution. We derive efficient online variational learning algorithm for the model and empirically demonstrate its efficiency on word-sense induction task.

##### Abstract (translated by Google)
最近提出的Skip-gram模型是一种学习高维词表示的强大方法，可以捕获单词之间丰富的语义关系。然而，Skip-gram以及大多数以前关于学习单词表示的工作并没有考虑到单词的歧义，并且只保留每个单词的单一表示。尽管为了克服这个限制并且学习了多原型词语表示，提出了许多跳跃词修饰，但它们要么需要已知数量的词义，要么使用贪婪的启发式方法学习它们。在本文中，我们提出的自适应Skip-gram模型是Skip-gram的非参数贝叶斯扩展，能够自动学习所需语义分辨率下所有单词的表示数。我们从模型中得到了高效的在线变分学习算法，并且在词义感应任务上经验性地展示了它的效率。

##### URL
[https://arxiv.org/abs/1502.07257](https://arxiv.org/abs/1502.07257)

##### PDF
[https://arxiv.org/pdf/1502.07257](https://arxiv.org/pdf/1502.07257)

