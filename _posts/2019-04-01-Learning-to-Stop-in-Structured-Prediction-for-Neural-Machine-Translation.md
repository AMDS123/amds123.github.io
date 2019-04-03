---
layout: post
title: "Learning to Stop in Structured Prediction for Neural Machine Translation"
date: 2019-04-01 18:01:08
categories: arXiv_CL
tags: arXiv_CL Optimization Prediction
author: Mingbo Ma, Renjie Zheng, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Beam search optimization resolves many issues in neural machine translation. However, this method lacks principled stopping criteria and does not learn how to stop during training, and the model naturally prefers the longer hypotheses during the testing time in practice since they use the raw score instead of the probability-based score. We propose a novel ranking method which enables an optimal beam search stopping criteria. We further introduce a structured prediction loss function which penalizes suboptimal finished candidates produced by beam search during training. Experiments of neural machine translation on both synthetic data and real languages (German-to-English and Chinese-to-English) demonstrate our proposed methods lead to better length and BLEU score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01032](http://arxiv.org/abs/1904.01032)

##### PDF
[http://arxiv.org/pdf/1904.01032](http://arxiv.org/pdf/1904.01032)

