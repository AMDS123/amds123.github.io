---
layout: post
title: "Analyzing Uncertainty in Neural Machine Translation"
date: 2018-08-13 17:13:23
categories: arXiv_CL
tags: arXiv_CL
author: Myle Ott, Michael Auli, David Grangier, Marc&#x27;Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
Machine translation is a popular test bed for research in neural sequence-to-sequence models but despite much recent research, there is still a lack of understanding of these models. Practitioners report performance degradation with large beams, the under-estimation of rare words and a lack of diversity in the final translations. Our study relates some of these issues to the inherent uncertainty of the task, due to the existence of multiple valid translations for a single source sentence, and to the extrinsic uncertainty caused by noisy training data. We propose tools and metrics to assess how uncertainty in the data is captured by the model distribution and how it affects search strategies that generate translations. Our results show that search works remarkably well but that models tend to spread too much probability mass over the hypothesis space. Next, we propose tools to assess model calibration and show how to easily fix some shortcomings of current models. As part of this study, we release multiple human reference translations for two popular benchmarks.

##### Abstract (translated by Google)
机器翻译是用于神经序列到序列模型研究的流行测试平台，但尽管最近进行了大量研究，但仍然缺乏对这些模型的理解。从业者报告大梁的性能下降，罕见词的低估和最终翻译缺乏多样性。由于单个源句的多个有效翻译的存在，以及由嘈杂的训练数据引起的外在不确定性，我们的研究将这些问题中的一些与任务的固有不确定性联系起来。我们提出了工具和指标来评估模型分布如何捕获数据的不确定性以及它如何影响生成翻译的搜索策略。我们的结果表明，搜索工作非常好，但模型倾向于在假设空间上传播过多的概率。接下来，我们提出了评估模型校准的工具，并展示了如何轻松修复当前模型的一些缺点。作为本研究的一部分，我们为两个流行的基准测试发布了多个人类参考译文。

##### URL
[http://arxiv.org/abs/1803.00047](http://arxiv.org/abs/1803.00047)

##### PDF
[http://arxiv.org/pdf/1803.00047](http://arxiv.org/pdf/1803.00047)

