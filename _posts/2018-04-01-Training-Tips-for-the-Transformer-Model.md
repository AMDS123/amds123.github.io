---
layout: post
title: "Training Tips for the Transformer Model"
date: 2018-04-01 01:59:52
categories: arXiv_CL
tags: arXiv_CL Recommendation
author: Martin Popel, Ond&#x159;ej Bojar
mathjax: true
---

* content
{:toc}

##### Abstract
This article describes our experiments in neural machine translation using the recent Tensor2Tensor framework and the Transformer sequence-to-sequence model (Vaswani et al., 2017). We examine some of the critical parameters that affect the final translation quality, memory usage, training stability and training time, concluding each experiment with a set of recommendations for fellow researchers. In addition to confirming the general mantra "more data and larger models", we address scaling to multiple GPUs and provide practical tips for improved training regarding batch size, learning rate, warmup steps, maximum sentence length and checkpoint averaging. We hope that our observations will allow others to get better results given their particular hardware and data constraints.

##### Abstract (translated by Google)
本文介绍了我们在神经机器翻译中的实验，使用最近的Tensor2Tensor框架和Transformer序列 - 序列模型（Vaswani等，2017）。我们研究了影响最终翻译质量，记忆使用率，培训稳定性和培训时间的一些关键参数，并为每个研究人员提供了一系列建议，从而结束每个实验。除了确认“更多数据和更大型号”的通用口头之外，我们还针对多个GPU进行扩展，并提供改进批量，学习速率，预热步骤，最大句子长度和检查点平均的培训的实用技巧。我们希望我们的观察能够让其他人在特定的硬件和数据限制下获得更好的结果。

##### URL
[http://arxiv.org/abs/1804.00247](http://arxiv.org/abs/1804.00247)

##### PDF
[http://arxiv.org/pdf/1804.00247](http://arxiv.org/pdf/1804.00247)

