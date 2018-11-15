---
layout: post
title: "Dependency Grammar Induction with a Neural Variational Transition-based Parser"
date: 2018-11-14 16:30:22
categories: arXiv_CL
tags: arXiv_CL Regularization Inference
author: Bowen Li, Jianpeng Cheng, Yang Liu, Frank Keller
mathjax: true
---

* content
{:toc}

##### Abstract
Dependency grammar induction is the task of learning dependency syntax without annotated training data. Traditional graph-based models with global inference achieve state-of-the-art results on this task but they require $O(n^3)$ run time. Transition-based models enable faster inference with $O(n)$ time complexity, but their performance still lags behind. In this work, we propose a neural transition-based parser for dependency grammar induction, whose inference procedure utilizes rich neural features with $O(n)$ time complexity. We train the parser with an integration of variational inference, posterior regularization and variance reduction techniques. The resulting framework outperforms previous unsupervised transition-based dependency parsers and achieves performance comparable to graph-based models, both on the English Penn Treebank and on the Universal Dependency Treebank. In an empirical comparison, we show that our approach substantially increases parsing speed over graph-based models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05889](http://arxiv.org/abs/1811.05889)

##### PDF
[http://arxiv.org/pdf/1811.05889](http://arxiv.org/pdf/1811.05889)

