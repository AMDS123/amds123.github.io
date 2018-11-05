---
layout: post
title: "Analysing Dropout and Compounding Errors in Neural Language Models"
date: 2018-11-02 17:31:53
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model
author: James O&#x27; Neill, Danushka Bollegala
mathjax: true
---

* content
{:toc}

##### Abstract
This paper carries out an empirical analysis of various dropout techniques for language modelling, such as Bernoulli dropout, Gaussian dropout, Curriculum Dropout, Variational Dropout and Concrete Dropout. Moreover, we propose an extension of variational dropout to concrete dropout and curriculum dropout with varying schedules. We find these extensions to perform well when compared to standard dropout approaches, particularly variational curriculum dropout with a linear schedule. Largest performance increases are made when applying dropout on the decoder layer. Lastly, we analyze where most of the errors occur at test time as a post-analysis step to determine if the well-known problem of compounding errors is apparent and to what end do the proposed methods mitigate this issue for each dataset. We report results on a 2-hidden layer LSTM, GRU and Highway network with embedding dropout, dropout on the gated hidden layers and the output projection layer for each model. We report our results on Penn-TreeBank and WikiText-2 word-level language modelling datasets, where the former reduces the long-tail distribution through preprocessing and one which preserves rare words in the training and test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00998](http://arxiv.org/abs/1811.00998)

##### PDF
[http://arxiv.org/pdf/1811.00998](http://arxiv.org/pdf/1811.00998)

