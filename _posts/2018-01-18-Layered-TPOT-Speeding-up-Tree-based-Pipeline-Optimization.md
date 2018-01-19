---
layout: post
title: "Layered TPOT: Speeding up Tree-based Pipeline Optimization"
date: 2018-01-18 13:36:51
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Pieter Gijsbers, Joaquin Vanschoren, Randal S. Olson
mathjax: true
---

* content
{:toc}

##### Abstract
With the demand for machine learning increasing, so does the demand for tools which make it easier to use. Automated machine learning (AutoML) tools have been developed to address this need, such as the Tree-Based Pipeline Optimization Tool (TPOT) which uses genetic programming to build optimal pipelines. We introduce Layered TPOT, a modification to TPOT which aims to create pipelines equally good as the original, but in significantly less time. This approach evaluates candidate pipelines on increasingly large subsets of the data according to their fitness, using a modified evolutionary algorithm to allow for separate competition between pipelines trained on different sample sizes. Empirical evaluation shows that, on sufficiently large datasets, Layered TPOT indeed finds better models faster.

##### Abstract (translated by Google)
随着对机器学习的需求不断增加，工具的使用也变得更加容易。已经开发了自动化机器学习（AutoML）工具来满足这种需求，例如基于树的管线优化工具（TPOT），它使用遗传编程来建立最佳管线。我们引入了层状TPOT，这是对TPOT的修改，旨在创建与原始管道相同的管道，但时间明显缩短。这种方法根据数据的适应性评估日益庞大的数据子集上的候选流水线，使用修改后的演化算法，允许不同样本量的流水线之间进行单独的竞争。经验性的评估表明，在足够大的数据集上，分层TPOT确实可以更快找到更好的模型。

##### URL
[http://arxiv.org/abs/1801.06007](http://arxiv.org/abs/1801.06007)

##### PDF
[http://arxiv.org/pdf/1801.06007](http://arxiv.org/pdf/1801.06007)

