---
layout: post
title: "Training Dependency Parsers with Partial Annotation"
date: 2016-09-29 08:12:14
categories: arXiv_CL
tags: arXiv_CL
author: Zhenghua Li, Yue Zhang, Jiayuan Chao, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, these has been a surge on studying how to obtain partially annotated data for model supervision. However, there still lacks a systematic study on how to train statistical models with partial annotation (PA). Taking dependency parsing as our case study, this paper describes and compares two straightforward approaches for three mainstream dependency parsers. The first approach is previously proposed to directly train a log-linear graph-based parser (LLGPar) with PA based on a forest-based objective. This work for the first time proposes the second approach to directly training a linear graph-based parse (LGPar) and a linear transition-based parser (LTPar) with PA based on the idea of constrained decoding. We conduct extensive experiments on Penn Treebank under three different settings for simulating PA, i.e., random dependencies, most uncertain dependencies, and dependencies with divergent outputs from the three parsers. The results show that LLGPar is most effective in learning from PA and LTPar lags behind the graph-based counterparts by large margin. Moreover, LGPar and LTPar can achieve best performance by using LLGPar to complete PA into full annotation (FA).

##### Abstract (translated by Google)
最近，在研究如何获得部分注释的模型监督数据方面，这些数据还是激增的。但是，如何利用部分注释（PA）训练统计模型还缺乏系统的研究。本文以依赖关系解析为例，对三种主流依赖关系解析器的两种直接方法进行了描述和比较。先前提出的第一种方法是基于基于森林的目标直接训练带有PA的对数线性基于图的解析器（LLGPar）。这项工作首次提出了基于约束解码思想直接训练基于线性图的语法分析（LGPar）和基于线性转换的语法分析器（LTPar）的第二种方法。我们在Penn TreeBank上进行了三个不同设置的广泛实验来模拟PA，即随机依赖，大多数不确定的依赖，以及三个解析器发散输出的依赖关系。结果表明，LLGPar对PA和LTPar的学习效果最为明显，大大低于图形对象。此外，LGPar和LTPar可以通过使用LLGPar将PA完成注释（FA）来实现最佳性能。

##### URL
[https://arxiv.org/abs/1609.09247](https://arxiv.org/abs/1609.09247)

##### PDF
[https://arxiv.org/pdf/1609.09247](https://arxiv.org/pdf/1609.09247)

