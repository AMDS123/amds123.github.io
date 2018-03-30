---
layout: post
title: "Iterative Visual Reasoning Beyond Convolutions"
date: 2018-03-29 17:59:03
categories: arXiv_CV
tags: arXiv_CV Knowledge_Graph Knowledge Attention Prediction Relation Recognition
author: Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel framework for iterative visual reasoning. Our framework goes beyond current recognition systems that lack the capability to reason beyond stack of convolutions. The framework consists of two core modules: a local module that uses spatial memory to store previous beliefs with parallel updates; and a global graph-reasoning module. Our graph module has three components: a) a knowledge graph where we represent classes as nodes and build edges to encode different types of semantic relationships between them; b) a region graph of the current image where regions in the image are nodes and spatial relationships between these regions are edges; c) an assignment graph that assigns regions to classes. Both the local module and the global module roll-out iteratively and cross-feed predictions to each other to refine estimates. The final predictions are made by combining the best of both modules with an attention mechanism. We show strong performance over plain ConvNets, \eg achieving an $8.4\%$ absolute improvement on ADE measured by per-class average precision. Analysis also shows that the framework is resilient to missing regions for reasoning.

##### Abstract (translated by Google)
我们提出了一种新颖的迭代视觉推理框架。我们的框架超越了目前的识别系统，缺乏超越卷积栈的推理能力。该框架由两个核心模块组成：一个本地模块，使用空间内存来存储以前的信念并行更新;和全局图形推理模块。我们的图模块有三个组成部分：a）一个知识图，其中我们将类表示为节点并构建边以对它们之间的不同类型的语义关系进行编码; b）当前图像的区域图，其中图像中的区域是节点并且这些区域之间的空间关系是边缘; c）将区域分配给类的分配图。本地模块和全局模块都会迭代推出并互相交叉预测以优化估算。最终的预测是通过将两个模块中最好的模块与注意机制相结合来完成的。我们在普通网络上表现出了强劲的表现，例如，通过按每班平均精确度衡量的ADE，实现了8.4％的绝对改进。分析还表明，该框架能够适应缺少推理的区域。

##### URL
[http://arxiv.org/abs/1803.11189](http://arxiv.org/abs/1803.11189)

##### PDF
[http://arxiv.org/pdf/1803.11189](http://arxiv.org/pdf/1803.11189)

