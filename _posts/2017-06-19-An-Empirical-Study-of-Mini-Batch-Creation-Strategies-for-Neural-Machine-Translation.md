---
layout: post
title: "An Empirical Study of Mini-Batch Creation Strategies for Neural Machine Translation"
date: 2017-06-19 02:38:01
categories: arXiv_CL
tags: arXiv_CL NMT
author: Makoto Morishita, Yusuke Oda, Graham Neubig, Koichiro Yoshino, Katsuhito Sudoh, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Training of neural machine translation (NMT) models usually uses mini-batches for efficiency purposes. During the mini-batched training process, it is necessary to pad shorter sentences in a mini-batch to be equal in length to the longest sentence therein for efficient computation. Previous work has noted that sorting the corpus based on the sentence length before making mini-batches reduces the amount of padding and increases the processing speed. However, despite the fact that mini-batch creation is an essential step in NMT training, widely used NMT toolkits implement disparate strategies for doing so, which have not been empirically validated or compared. This work investigates mini-batch creation strategies with experiments over two different datasets. Our results suggest that the choice of a mini-batch creation strategy has a large effect on NMT training and some length-based sorting strategies do not always work well compared with simple shuffling.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.05765](https://arxiv.org/abs/1706.05765)

##### PDF
[https://arxiv.org/pdf/1706.05765](https://arxiv.org/pdf/1706.05765)

