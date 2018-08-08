---
layout: post
title: "The Window Validity Problem in Rule-Based Stream Reasoning"
date: 2018-08-07 10:17:11
categories: arXiv_AI
tags: arXiv_AI
author: Alessandro Ronca, Mark Kaminski, Bernardo Cuenca Grau, Ian Horrocks
mathjax: true
---

* content
{:toc}

##### Abstract
Rule-based temporal query languages provide the expressive power and flexibility required to capture in a natural way complex analysis tasks over streaming data. Stream processing applications, however, typically require near real-time response using limited resources. In particular, it becomes essential that the underpinning query language has favourable computational properties and that stream processing algorithms are able to keep only a small number of previously received facts in memory at any point in time without sacrificing correctness. In this paper, we propose a recursive fragment of temporal Datalog with tractable data complexity and study the properties of a generic stream reasoning algorithm for this fragment. We focus on the window validity problem as a way to minimise the number of time points for which the stream reasoning algorithm needs to keep data in memory at any point in time.

##### Abstract (translated by Google)
基于规则的时态查询语言提供了以自然方式捕获流数据上的复杂分析任务所需的表达能力和灵活性。但是，流处理应用程序通常需要使用有限的资源进行近实时响应。特别地，基础查询语言具有有利的计算属性并且流处理算法能够在任何时间点仅在存储器中保留少量先前接收的事实而不牺牲正确性变得必不可少。在本文中，我们提出了一个具有易处理数据复杂性的时间Datalog的递归片段，并研究了该片段的通用流推理算法的属性。我们关注窗口有效性问题，作为最小化流推理算法在任何时间点将数据保存在内存中的时间点数量的方法。

##### URL
[http://arxiv.org/abs/1808.02291](http://arxiv.org/abs/1808.02291)

##### PDF
[http://arxiv.org/pdf/1808.02291](http://arxiv.org/pdf/1808.02291)

