---
layout: post
title: "Weakly Supervised Grammatical Error Correction using Iterative Decoding"
date: 2018-10-31 01:31:10
categories: arXiv_CL
tags: arXiv_CL Weakly_Supervised
author: Jared Lichtarge, Christopher Alberti, Shankar Kumar, Noam Shazeer, Niki Parmar
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an approach to Grammatical Error Correction (GEC) that is effective at making use of models trained on large amounts of weakly supervised bitext. We train the Transformer sequence-to-sequence model on 4B tokens of Wikipedia revisions and employ an iterative decoding strategy that is tailored to the loosely-supervised nature of the Wikipedia training corpus. Finetuning on the Lang-8 corpus and ensembling yields an F0.5 of 58.3 on the CoNLL'14 benchmark and a GLEU of 62.4 on JFLEG. The combination of weakly supervised training and iterative decoding obtains an F0.5 of 48.2 on CoNLL'14 even without using any labeled GEC data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01710](http://arxiv.org/abs/1811.01710)

##### PDF
[http://arxiv.org/pdf/1811.01710](http://arxiv.org/pdf/1811.01710)

