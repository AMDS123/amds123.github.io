---
layout: post
title: "Robust Text-to-SQL Generation with Execution-Guided Decoding"
date: 2018-09-09 21:55:52
categories: arXiv_CL
tags: arXiv_CL
author: Chenglong Wang, Kedar Tatwawadi, Marc Brockschmidt, Po-Sen Huang, Yi Mao, Oleksandr Polozov, Rishabh Singh
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of neural semantic parsing, which translates natural language questions into executable SQL queries. We introduce a new mechanism, execution guidance, to leverage the semantics of SQL. It detects and excludes faulty programs during the decoding procedure by conditioning on the execution of partially generated program. The mechanism can be used with any autoregressive generative model, which we demonstrate on four state-of-the-art recurrent or template-based semantic parsing models. We demonstrate that execution guidance universally improves model performance on various text-to-SQL datasets with different scales and query complexity: WikiSQL, ATIS, and GeoQuery. As a result, we achieve new state-of-the-art execution accuracy of 83.8% on WikiSQL.

##### Abstract (translated by Google)
我们考虑神经语义分析的问题，它将自然语言问题转换为可执行的SQL查询。我们引入了一种新的机制，执行指南，以利用SQL的语义。它通过调节部分生成的程序的执行来检测和排除在解码过程期间的错误程序。该机制可以与任何自回归生成模型一起使用，我们在四种最先进的循环或基于模板的语义分析模型上进行了演示。我们证明了执行指南普遍提高了具有不同规模和查询复杂性的各种文本到SQL数据集的模型性能：WikiSQL，ATIS和GeoQuery。因此，我们在WikiSQL上实现了83.8％的最新执行精度。

##### URL
[http://arxiv.org/abs/1807.03100](http://arxiv.org/abs/1807.03100)

##### PDF
[http://arxiv.org/pdf/1807.03100](http://arxiv.org/pdf/1807.03100)

