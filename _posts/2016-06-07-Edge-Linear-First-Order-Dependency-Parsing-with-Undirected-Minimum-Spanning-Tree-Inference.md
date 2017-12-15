---
layout: post
title: "Edge-Linear First-Order Dependency Parsing with Undirected Minimum Spanning Tree Inference"
date: 2016-06-07 22:07:37
categories: arXiv_CL
tags: arXiv_CL Inference
author: Effi Levi, Roi Reichart, Ari Rappoport
mathjax: true
---

* content
{:toc}

##### Abstract
The run time complexity of state-of-the-art inference algorithms in graph-based dependency parsing is super-linear in the number of input words (n). Recently, pruning algorithms for these models have shown to cut a large portion of the graph edges, with minimal damage to the resulting parse trees. Solving the inference problem in run time complexity determined solely by the number of edges (m) is hence of obvious importance. We propose such an inference algorithm for first-order models, which encodes the problem as a minimum spanning tree (MST) problem in an undirected graph. This allows us to utilize state-of-the-art undirected MST algorithms whose run time is O(m) at expectation and with a very high probability. A directed parse tree is then inferred from the undirected MST and is subsequently improved with respect to the directed parsing model through local greedy updates, both steps running in O(n) time. In experiments with 18 languages, a variant of the first-order MSTParser (McDonald et al., 2005b) that employs our algorithm performs very similarly to the original parser that runs an O(n^2) directed MST inference.

##### Abstract (translated by Google)
基于图形的依赖性分析中的最新推理算法的运行时间复杂度在输入词（n）的数量上是超线性的。最近，这些模型的修剪算法已经显示出削减了很大一部分的图形边缘，对所产生的分析树木的破坏最小。解决单纯由边数（m）决定的运行时间复杂度的推理问题显然是重要的。我们针对一阶模型提出了这样的推理算法，其将该问题编码为无向图中的最小生成树（MST）问题。这使得我们可以在预期和非常高的概率下利用运行时间为O（m）的最先进的无向MST算法。然后从无向MST中推导出有向解析树，并随后通过本地贪婪更新相对于有向解析模型进行改进，两个步骤都在O（n）时间运行。在18种语言的实验中，使用我们的算法的一阶MSTParser（McDonald等人，2005b）的变体与运行O（n ^ 2）定向的MST推理的原始解析器非常相似。

##### URL
[https://arxiv.org/abs/1510.07482](https://arxiv.org/abs/1510.07482)

##### PDF
[https://arxiv.org/pdf/1510.07482](https://arxiv.org/pdf/1510.07482)

