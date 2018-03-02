---
layout: post
title: "Analyzing Uncertainty in Neural Machine Translation"
date: 2018-02-28 19:33:24
categories: arXiv_CL
tags: arXiv_CL
author: Myle Ott, Michael Auli, David Granger, Marc'Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
Machine translation is a popular test bed for research in neural sequence-to-sequence models but despite much recent research, there is still a lack of understanding of these models. Practitioners report performance degradation with large beams, the under-estimation of rare words and a lack of diversity in the final translations. Our study relates some of these issues to the inherent uncertainty of the task, due to the existence of multiple valid translations for a single source sentence, and to the extrinsic uncertainty caused by noisy training data. We propose tools and metrics to assess how uncertainty in the data is captured by the model distribution and how it affects search strategies that generate translations. Our results show that search works remarkably well but that the models tend to spread too much probability mass over the hypothesis space. Next, we propose tools to assess model calibration and show how to easily fix some shortcomings of current models. We release both code and multiple human reference translations for two popular benchmarks.

##### Abstract (translated by Google)
机器翻译是用于研究神经序列 - 序列模型的流行测试平台，但尽管最近的研究很多，但对这些模型仍然缺乏了解。从业人员报告说，大光束下的性能下降，对罕见词语的低估以及最终翻译缺乏多样性。我们的研究将这些问题中的一部分与任务的固有不确定性联系起来，这是由于单个源句子存在多个有效的翻译，以及由于嘈杂的训练数据造成的外在不确定性。我们提出了一些工具和指标来评估数据的不确定性如何被模型分布捕获，以及它如何影响生成翻译的搜索策略。我们的研究结果表明，搜索的效果非常好，但模型倾向于在假设空间传播太多的概率。接下来，我们提出评估模型校准的工具，并展示如何轻松解决当前模型的一些缺点。我们为两个流行的基准测试版本和多个人类参考翻译版本发布。

##### URL
[https://arxiv.org/abs/1803.00047](https://arxiv.org/abs/1803.00047)

##### PDF
[https://arxiv.org/pdf/1803.00047](https://arxiv.org/pdf/1803.00047)

