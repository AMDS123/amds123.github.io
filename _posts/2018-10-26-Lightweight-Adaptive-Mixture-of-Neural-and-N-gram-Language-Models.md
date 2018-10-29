---
layout: post
title: "Lightweight Adaptive Mixture of Neural and N-gram Language Models"
date: 2018-10-26 11:37:29
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Anton Bakhtin, Arthur Szlam, Marc&#x27;Aurelio Ranzato, Edouard Grave
mathjax: true
---

* content
{:toc}

##### Abstract
It is often the case that the best performing language model is an ensemble of a neural language model with n-grams. In this work, we propose a method to improve how these two models are combined. By using a small network which predicts the mixture weight between the two models, we adapt their relative importance at each time step. Because the gating network is small, it trains quickly on small amounts of held out data, and does not add overhead at scoring time. Our experiments carried out on the One Billion Word benchmark show a significant improvement over the state of the art ensemble without retraining of the basic modules.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07705](http://arxiv.org/abs/1804.07705)

##### PDF
[http://arxiv.org/pdf/1804.07705](http://arxiv.org/pdf/1804.07705)

