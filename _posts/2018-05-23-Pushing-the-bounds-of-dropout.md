---
layout: post
title: "Pushing the bounds of dropout"
date: 2018-05-23 14:55:39
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: G&#xe1;bor Melis, Charles Blundell, Tom&#xe1;&#x161; Ko&#x10d;isk&#xfd;, Karl Moritz Hermann, Chris Dyer, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
We show that dropout training is best understood as performing MAP estimation concurrently for a family of conditional models whose objectives are themselves lower bounded by the original dropout objective. This discovery allows us to pick any model from this family after training, which leads to a substantial improvement on regularisation-heavy language modelling. The family includes models that compute a power mean over the sampled dropout masks, and their less stochastic subvariants with tighter and higher lower bounds than the fully stochastic dropout objective. We argue that since the deterministic subvariant's bound is equal to its objective, and the highest amongst these models, the predominant view of it as a good approximation to MC averaging is misleading. Rather, deterministic dropout is the best available approximation to the true objective.

##### Abstract (translated by Google)
我们表明，退出训练最好理解为同时对一组条件模型同时执行MAP估计，这些条件模型的目标本身是由原始退出目标限制的。这一发现使我们能够在训练后从这个家族中挑选出任何模型，这对正则化语言建模有很大的改进。该家族包括计算采样丢失掩模上的幂平均的模型，以及与完全随机辍学目标相比具有更紧密和更高下限的更少随机子变量。我们认为，由于确定性子变量的约束等于它的目标，并且是这些模型中最高的，所以它作为MC平均的一个很好的近似的主要观点是误导性的。相反，确定性辍学是真正目标的最佳可用近似。

##### URL
[http://arxiv.org/abs/1805.09208](http://arxiv.org/abs/1805.09208)

##### PDF
[http://arxiv.org/pdf/1805.09208](http://arxiv.org/pdf/1805.09208)

