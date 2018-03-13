---
layout: post
title: "Exact and approximate inference in graphical models: variable elimination and beyond"
date: 2018-03-12 07:45:08
categories: arXiv_AI
tags: arXiv_AI Review Inference
author: Nathalie Peyrard, Marie-Jos&#xe9;e Cros, Simon de Givry, Alain Franc, St&#xe9;phane Robin, R&#xe9;gis Sabbadin, Thomas Schiex, Matthieu Vignes
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic graphical models offer a powerful framework to account for the dependence structure between variables, which is represented as a graph. However, the dependence between variables may render inference tasks intractable. In this paper we review techniques exploiting the graph structure for exact inference, borrowed from optimisation and computer science. They are built on the principle of variable elimination whose complexity is dictated in an intricate way by the order in which variables are eliminated. The so-called treewidth of the graph characterises this algorithmic complexity: low-treewidth graphs can be processed efficiently. The first message that we illustrate is therefore the idea that for inference in graphical model, the number of variables is not the limiting factor, and it is worth checking for the treewidth before turning to approximate methods. We show how algorithms providing an upper bound of the treewidth can be exploited to derive a 'good' elimination order enabling to perform exact inference. The second message is that when the treewidth is too large, algorithms for approximate inference linked to the principle of variable elimination, such as loopy belief propagation and variational approaches, can lead to accurate results while being much less time consuming than Monte-Carlo approaches. We illustrate the techniques reviewed in this article on benchmarks of inference problems in genetic linkage analysis and computer vision, as well as on hidden variables restoration in coupled Hidden Markov Models.

##### Abstract (translated by Google)
概率图模型提供了一个强大的框架来说明变量之间的依赖结构，这些结构以图形表示。然而，变量之间的依赖性可能使得推理任务难以处理。在本文中，我们将回顾从优化和计算机科学中借鉴图形结构的精确推理技术。它们建立在变量消除的原则之上，其复杂程度取决于消除变量的顺序。图中所谓的树宽表征了这种算法的复杂性：低树宽度图可以被有效地处理。因此，我们要说明的第一个信息是，对于图形模型中的推理，变量的数量不是限制因素，在转向近似方法之前，应该检查树宽。我们展示了如何利用提供树宽度上限的算法来推导出一个“好”消除顺序，从而能够执行精确的推理。第二个信息是，当树宽过大时，与变量消元原理相关的近似推理算法，如loopy置信传播和变分方法，可以产生准确的结果，同时比Monte-Carlo方法耗时更少。我们举例说明了本文中关于遗传连锁分析和计算机视觉推理问题的基准以及耦合隐马尔可夫模型中隐变量恢复的文章。

##### URL
[http://arxiv.org/abs/1506.08544](http://arxiv.org/abs/1506.08544)

##### PDF
[http://arxiv.org/pdf/1506.08544](http://arxiv.org/pdf/1506.08544)

