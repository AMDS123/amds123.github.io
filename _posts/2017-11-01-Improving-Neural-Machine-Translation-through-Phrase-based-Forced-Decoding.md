---
layout: post
title: "Improving Neural Machine Translation through Phrase-based Forced Decoding"
date: 2017-11-01 12:25:20
categories: arXiv_CL
tags: arXiv_CL NMT
author: Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Compared to traditional statistical machine translation (SMT), neural machine translation (NMT) often sacrifices adequacy for the sake of fluency. We propose a method to combine the advantages of traditional SMT and NMT by exploiting an existing phrase-based SMT model to compute the phrase-based decoding cost for an NMT output and then using this cost to rerank the n-best NMT outputs. The main challenge in implementing this approach is that NMT outputs may not be in the search space of the standard phrase-based decoding algorithm, because the search space of phrase-based SMT is limited by the phrase-based translation rule table. We propose a soft forced decoding algorithm, which can always successfully find a decoding path for any NMT output. We show that using the forced decoding cost to rerank the NMT outputs can successfully improve translation quality on four different language pairs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.00309](https://arxiv.org/abs/1711.00309)

##### PDF
[https://arxiv.org/pdf/1711.00309](https://arxiv.org/pdf/1711.00309)

