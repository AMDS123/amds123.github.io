---
layout: post
title: "Policy Gradient as a Proxy for Dynamic Oracles in Constituency Parsing"
date: 2018-06-08 17:45:13
categories: arXiv_CL
tags: arXiv_CL
author: Daniel Fried, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic oracles provide strong supervision for training constituency parsers with exploration, but must be custom defined for a given parser's transition system. We explore using a policy gradient method as a parser-agnostic alternative. In addition to directly optimizing for a tree-level metric such as F1, policy gradient has the potential to reduce exposure bias by allowing exploration during training; moreover, it does not require a dynamic oracle for supervision. On four constituency parsers in three languages, the method substantially outperforms static oracle likelihood training in almost all settings. For parsers where a dynamic oracle is available (including a novel oracle which we define for the transition system of Dyer et al. 2016), policy gradient typically recaptures a substantial fraction of the performance gain afforded by the dynamic oracle.

##### Abstract (translated by Google)
动态过程为通过探索训练选区解析器提供强有力的监督，但必须为给定解析器的过渡系统定制定义。我们探讨使用策略梯度方法作为解析器不可知的替代方法。除了直接针对树状指标（如F1）进行优化之外，政策梯度还可以通过允许在培训期间进行探索来降低暴露偏差;而且，它不需要一个动态监督的预言。在三种语言的四个选区解析器中，该方法在几乎所有环境中都大大优于静态oracle可能性训练。对于具有动态oracle的解析器（包括我们为Dyer et al。2016的转换系统定义的新型oracle），策略梯度通常会重新获得动态oracle提供的性能增益的相当大的一部分。

##### URL
[http://arxiv.org/abs/1806.03290](http://arxiv.org/abs/1806.03290)

##### PDF
[http://arxiv.org/pdf/1806.03290](http://arxiv.org/pdf/1806.03290)

