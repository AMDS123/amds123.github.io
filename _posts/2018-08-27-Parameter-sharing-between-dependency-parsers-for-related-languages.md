---
layout: post
title: "Parameter sharing between dependency parsers for related languages"
date: 2018-08-27 22:47:59
categories: arXiv_CL
tags: arXiv_CL RNN
author: Miryam de Lhoneux, Johannes Bjerva, Isabelle Augenstein, Anders S&#xf8;gaard
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work has suggested that parameter sharing between transition-based neural dependency parsers for related languages can lead to better performance, but there is no consensus on what parameters to share. We present an evaluation of 27 different parameter sharing strategies across 10 languages, representing five pairs of related languages, each pair from a different language family. We find that sharing transition classifier parameters always helps, whereas the usefulness of sharing word and/or character LSTM parameters varies. Based on this result, we propose an architecture where the transition classifier is shared, and the sharing of word and character parameters is controlled by a parameter that can be tuned on validation data. This model is linguistically motivated and obtains significant improvements over a monolingually trained baseline. We also find that sharing transition classifier parameters helps when training a parser on unrelated language pairs, but we find that, in the case of unrelated languages, sharing too many parameters does not help.

##### Abstract (translated by Google)
以前的工作表明，基于转换的相关语言神经依赖解析器之间的参数共享可以带来更好的性能，但是没有就要共享的参数达成共识。我们对10种语言的27种不同参数共享策略进行了评估，代表了5对相关语言，每对来自不同的语言家族。我们发现共享转换分类器参数总是有帮助，而共享单词和/或字符LSTM参数的有用性会有所不同。基于此结果，我们提出了一种架构，其中共享转换分类器，并且通过可以在验证数据上调整的参数来控制字和字符参数的共享。该模型具有语言学上的动机，并且在单一训练基线上获得显着改善。我们还发现共享转换分类器参数有助于在无关语言对上训练解析器，但我们发现，在不相关语言的情况下，共享太多参数无济于事。

##### URL
[http://arxiv.org/abs/1808.09055](http://arxiv.org/abs/1808.09055)

##### PDF
[http://arxiv.org/pdf/1808.09055](http://arxiv.org/pdf/1808.09055)

