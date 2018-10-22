---
layout: post
title: "Dynamic Sentence Sampling for Efficient Training of Neural Machine Translation"
date: 2018-10-19 00:12:50
categories: arXiv_CL
tags: arXiv_CL NMT
author: Rui Wang, Masao Utiyama, Eiichiro Sumita
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional Neural machine translation (NMT) involves a fixed training procedure where each sentence is sampled once during each epoch. In reality, some sentences are well-learned during the initial few epochs; however, using this approach, the well-learned sentences would continue to be trained along with those sentences that were not well learned for 10-30 epochs, which results in a wastage of time. Here, we propose an efficient method to dynamically sample the sentences in order to accelerate the NMT training. In this approach, a weight is assigned to each sentence based on the measured difference between the training costs of two iterations. Further, in each epoch, a certain percentage of sentences are dynamically sampled according to their weights. Empirical results based on the NIST Chinese-to-English and the WMT English-to-German tasks depict that the proposed method can significantly accelerate the NMT training and improve the NMT performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.00178](http://arxiv.org/abs/1805.00178)

##### PDF
[http://arxiv.org/e-print/1805.00178](http://arxiv.org/e-print/1805.00178)

