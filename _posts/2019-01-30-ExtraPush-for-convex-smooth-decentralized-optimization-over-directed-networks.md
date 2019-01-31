---
layout: post
title: "ExtraPush for convex smooth decentralized optimization over directed networks"
date: 2019-01-30 02:21:09
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Jinshan Zeng, Wotao Yin
mathjax: true
---

* content
{:toc}

##### Abstract
In this note, we extend the algorithms Extra and subgradient-push to a new algorithm ExtraPush for consensus optimization with convex differentiable objective functions over a directed network. When the stationary distribution of the network can be computed in advance}, we propose a simplified algorithm called Normalized ExtraPush. Just like Extra, both ExtraPush and Normalized ExtraPush can iterate with a fixed step size. But unlike Extra, they can take a column-stochastic mixing matrix, which is not necessarily doubly stochastic. Therefore, they remove the undirected-network restriction of Extra. Subgradient-push, while also works for directed networks, is slower on the same type of problem because it must use a sequence of diminishing step sizes. 
 We present preliminary analysis for ExtraPush under a bounded sequence assumption. For Normalized ExtraPush, we show that it naturally produces a bounded, linearly convergent sequence provided that the objective function is strongly convex. 
 In our numerical experiments, ExtraPush and Normalized ExtraPush performed similarly well. They are significantly faster than subgradient-push, even when we hand-optimize the step sizes for the latter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1511.02942](http://arxiv.org/abs/1511.02942)

##### PDF
[http://arxiv.org/pdf/1511.02942](http://arxiv.org/pdf/1511.02942)

