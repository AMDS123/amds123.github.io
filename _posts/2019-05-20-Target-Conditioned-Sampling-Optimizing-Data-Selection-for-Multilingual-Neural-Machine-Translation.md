---
layout: post
title: "Target Conditioned Sampling: Optimizing Data Selection for Multilingual Neural Machine Translation"
date: 2019-05-20 16:54:43
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xinyi Wang, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
To improve low-resource Neural Machine Translation (NMT) with multilingual corpora, training on the most related high-resource language only is often more effective than using all data available (Neubig and Hu, 2018). However, it is possible that an intelligent data selection strategy can further improve low-resource NMT with data from other auxiliary languages. In this paper, we seek to construct a sampling distribution over all multilingual data, so that it minimizes the training loss of the low-resource language. Based on this formulation, we propose an efficient algorithm, Target Conditioned Sampling (TCS), which first samples a target sentence, and then conditionally samples its source sentence. Experiments show that TCS brings significant gains of up to 2 BLEU on three of four languages we test, with minimal training overhead.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08212](http://arxiv.org/abs/1905.08212)

##### PDF
[http://arxiv.org/pdf/1905.08212](http://arxiv.org/pdf/1905.08212)

