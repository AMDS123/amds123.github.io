---
layout: post
title: "On the Effectiveness of Low-Rank Matrix Factorization for LSTM Model Compression"
date: 2019-08-27 01:52:07
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Relation
author: Genta Indra Winata, Andrea Madotto, Jamin Shin, Elham J. Barezi, Pascale Fung
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their ubiquity in NLP tasks, Long Short-Term Memory (LSTM) networks suffer from computational inefficiencies caused by inherent unparallelizable recurrences, which further aggravates as LSTMs require more parameters for larger memory capacity. In this paper, we propose to apply low-rank matrix factorization (MF) algorithms to different recurrences in LSTMs, and explore the effectiveness on different NLP tasks and model components. We discover that additive recurrence is more important than multiplicative recurrence, and explain this by identifying meaningful correlations between matrix norms and compression performance. We compare our approach across two settings: 1) compressing core LSTM recurrences in language models, 2) compressing biLSTM layers of ELMo evaluated in three downstream NLP tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09982](http://arxiv.org/abs/1908.09982)

##### PDF
[http://arxiv.org/pdf/1908.09982](http://arxiv.org/pdf/1908.09982)

