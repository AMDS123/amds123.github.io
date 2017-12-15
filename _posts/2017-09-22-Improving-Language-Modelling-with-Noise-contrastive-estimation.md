---
layout: post
title: "Improving Language Modelling with Noise-contrastive estimation"
date: 2017-09-22 13:59:17
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Farhana Ferdousi Liza, Marek Grzes
mathjax: true
---

* content
{:toc}

##### Abstract
Neural language models do not scale well when the vocabulary is large. Noise-contrastive estimation (NCE) is a sampling-based method that allows for fast learning with large vocabularies. Although NCE has shown promising performance in neural machine translation, it was considered to be an unsuccessful approach for language modelling. A sufficient investigation of the hyperparameters in the NCE-based neural language models was also missing. In this paper, we showed that NCE can be a successful approach in neural language modelling when the hyperparameters of a neural network are tuned appropriately. We introduced the 'search-then-converge' learning rate schedule for NCE and designed a heuristic that specifies how to use this schedule. The impact of the other important hyperparameters, such as the dropout rate and the weight initialisation range, was also demonstrated. We showed that appropriate tuning of NCE-based neural language models outperforms the state-of-the-art single-model methods on a popular benchmark.

##### Abstract (translated by Google)
当词汇量很大时，神经语言模型不能很好地扩展。噪声对比估计（NCE）是一种基于抽样的方法，可以用大型词汇表进行快速学习。尽管NCE在神经机器翻译中表现出有希望的性能，但它被认为是语言建模的不成功的方法。对基于NCE的神经语言模型中超参数的充分研究也被忽略了。在本文中，我们展示了当神经网络的超参数得到适当调整时，NCE可以成为神经语言建模的成功方法。我们为NCE引入了“搜索 - 然后收敛”的学习速率时间表，并设计了一个启发式方法来指定如何使用这个时间表。其他重要的超参数，如辍学率和体重初始化范围的影响也被证明。我们发现基于NCE的神经语言模型的适当调整胜过了在流行的基准测试中的最先进的单模式方法。

##### URL
[https://arxiv.org/abs/1709.07758](https://arxiv.org/abs/1709.07758)

##### PDF
[https://arxiv.org/pdf/1709.07758](https://arxiv.org/pdf/1709.07758)

