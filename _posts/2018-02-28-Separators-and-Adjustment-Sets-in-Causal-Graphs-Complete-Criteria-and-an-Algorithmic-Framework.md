---
layout: post
title: "Separators and Adjustment Sets in Causal Graphs: Complete Criteria and an Algorithmic Framework"
date: 2018-02-28 22:28:08
categories: arXiv_AI
tags: arXiv_AI
author: Benito van der Zander (1), Maciej Li&#x15b;kiewicz (1), Johannes Textor (2) ((1) Institute for Theoretical Computer Science, Universit&#xe4;t zu L&#xfc;beck, Germany, (2) Institute for Computing and Information Sciences, Radboud University Nijmegen, Nijmegen, The Netherlands)
mathjax: true
---

* content
{:toc}

##### Abstract
Principled reasoning about the identifiability of causal effects from non-experimental data is an important application of graphical causal models. We present an algorithmic framework for efficiently testing, constructing, and enumerating $m$-separators in ancestral graphs (AGs), a class of graphical causal models that can represent uncertainty about the presence of latent confounders. Furthermore, we prove a reduction from causal effect identification by covariate adjustment to $m$-separation in a subgraph for directed acyclic graphs (DAGs) and maximal ancestral graphs (MAGs). Jointly, these results yield constructive criteria that characterize all adjustment sets as well as all minimal and minimum adjustment sets for identification of a desired causal effect with multivariate exposures and outcomes in the presence of latent confounding. Our results extend several existing solutions for special cases of these problems. Our efficient algorithms allowed us to empirically quantify the identifiability gap between covariate adjustment and the do-calculus in random DAGs, covering a wide range of scenarios. Implementations of our algorithms are provided in the R package dagitty.

##### Abstract (translated by Google)
关于来自非实验数据的因果效应的可识别性的原理推理是图解因果模型的重要应用。我们提出了一个算法框架，用于高效地测试，构造和枚举祖先图（AGs）中的$ m $  - 分离器，这是一类图形因果模型，可以表示潜在混杂因子存在的不确定性。此外，我们证明了从有效无效图（DAG）和最大祖先图（MAG）的子图中的协变量调整到因子效应识别中的$ m $分离。共同地，这些结果产生了具有特征的所有调整集合的建设性标准以及所有最小和最小调整集合，用于在存在潜在混杂的情况下用多变量暴露和结果来确定期望的因果效应。我们的结果扩展了这些问题特殊情况下的几种现有解决方案我们的高效算法使我们能够凭经验量化随机DAG中协变量调整与do-calculus之间的可识别性差距，涵盖了广泛的情景。我们算法的实现在R软件包中提供。

##### URL
[http://arxiv.org/abs/1803.00116](http://arxiv.org/abs/1803.00116)

##### PDF
[http://arxiv.org/pdf/1803.00116](http://arxiv.org/pdf/1803.00116)

