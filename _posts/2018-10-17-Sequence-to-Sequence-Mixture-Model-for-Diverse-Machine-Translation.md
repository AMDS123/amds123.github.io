---
layout: post
title: "Sequence to Sequence Mixture Model for Diverse Machine Translation"
date: 2018-10-17 05:42:49
categories: arXiv_CL
tags: arXiv_CL Optimization
author: Xuanli He, Gholamreza Haffari, Mohammad Norouzi
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence to sequence (SEQ2SEQ) models often lack diversity in their generated translations. This can be attributed to the limitation of SEQ2SEQ models in capturing lexical and syntactic variations in a parallel corpus resulting from different styles, genres, topics, or ambiguity of the translation process. In this paper, we develop a novel sequence to sequence mixture (S2SMIX) model that improves both translation diversity and quality by adopting a committee of specialized translation models rather than a single translation model. Each mixture component selects its own training dataset via optimization of the marginal loglikelihood, which leads to a soft clustering of the parallel corpus. Experiments on four language pairs demonstrate the superiority of our mixture model compared to a SEQ2SEQ baseline with standard or diversity-boosted beam search. Our mixture model uses negligible additional parameters and incurs no extra computation cost during decoding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07391](http://arxiv.org/abs/1810.07391)

##### PDF
[http://arxiv.org/pdf/1810.07391](http://arxiv.org/pdf/1810.07391)

