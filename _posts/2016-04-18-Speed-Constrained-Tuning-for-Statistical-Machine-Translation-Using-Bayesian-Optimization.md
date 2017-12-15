---
layout: post
title: "Speed-Constrained Tuning for Statistical Machine Translation Using Bayesian Optimization"
date: 2016-04-18 10:27:49
categories: arXiv_SD
tags: arXiv_SD Optimization
author: Daniel Beck, Adrià de Gispert, Gonzalo Iglesias, Aurelien Waite, Bill Byrne
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of automatically finding the parameters of a statistical machine translation system that maximize BLEU scores while ensuring that decoding speed exceeds a minimum value. We propose the use of Bayesian Optimization to efficiently tune the speed-related decoding parameters by easily incorporating speed as a noisy constraint function. The obtained parameter values are guaranteed to satisfy the speed constraint with an associated confidence margin. Across three language pairs and two speed constraint values, we report overall optimization time reduction compared to grid and random search. We also show that Bayesian Optimization can decouple speed and BLEU measurements, resulting in a further reduction of overall optimization time as speed is measured over a small subset of sentences.

##### Abstract (translated by Google)
我们解决了自动寻找统计机器翻译系统的参数的问题，其使BLEU分数最大化，同时确保解码速度超过最小值。我们建议使用贝叶斯优化，通过简单地将速度作为噪声约束函数进行合并，来有效地调整速度相关的解码参数。所获得的参数值被保证满足速度约束和相关的置信度。在三个语言对和两个速度约束值之间，我们报告与网格和随机搜索相比总体优化时间减少。我们还表明，贝叶斯优化可以解耦速度和BLEU测量，从而导致进一步减少整体优化时间，因为速度是在一小部分句子上测量的。

##### URL
[https://arxiv.org/abs/1604.05073](https://arxiv.org/abs/1604.05073)

##### PDF
[https://arxiv.org/pdf/1604.05073](https://arxiv.org/pdf/1604.05073)

