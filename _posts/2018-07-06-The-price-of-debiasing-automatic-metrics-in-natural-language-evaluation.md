---
layout: post
title: "The price of debiasing automatic metrics in natural language evaluation"
date: 2018-07-06 00:11:27
categories: arXiv_CL
tags: arXiv_CL Summarization
author: Arun Tejasvi Chaganty, Stephen Mussman, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
For evaluating generation systems, automatic metrics such as BLEU cost nothing to run but have been shown to correlate poorly with human judgment, leading to systematic bias against certain model improvements. On the other hand, averaging human judgments, the unbiased gold standard, is often too expensive. In this paper, we use control variates to combine automatic metrics with human evaluation to obtain an unbiased estimator with lower cost than human evaluation alone. In practice, however, we obtain only a 7-13% cost reduction on evaluating summarization and open-response question answering systems. We then prove that our estimator is optimal: there is no unbiased estimator with lower cost. Our theory further highlights the two fundamental bottlenecks---the automatic metric and the prompt shown to human evaluators---both of which need to be improved to obtain greater cost savings.

##### Abstract (translated by Google)
对于评估发电系统，诸如BLEU之类的自动指标不需要花费任何成本，但已被证明与人类判断相关性较差，导致对某些模型改进的系统偏差。另一方面，平均人类判断，无偏见的黄金标准，往往过于昂贵。在本文中，我们使用控制变量将自动度量与人工评估相结合，以获得一个比人类评估更低成本的无偏估计。然而，在实践中，我们在评估摘要和开放式响应问答系统时仅降低了7-13％的成本。然后我们证明我们的估计是最优的：没有没有偏见的估算器，成本更低。我们的理论进一步突出了两个基本瓶颈 - 自动度量和向人类评估人员展示的提示 - 两者都需要进行改进以获得更大的成本节约。

##### URL
[http://arxiv.org/abs/1807.02202](http://arxiv.org/abs/1807.02202)

##### PDF
[http://arxiv.org/pdf/1807.02202](http://arxiv.org/pdf/1807.02202)

