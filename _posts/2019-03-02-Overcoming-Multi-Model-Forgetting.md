---
layout: post
title: "Overcoming Multi-Model Forgetting"
date: 2019-03-02 18:59:39
categories: arXiv_CV
tags: arXiv_CV NAS
author: Yassine Benyahia, Kaicheng Yu, Kamil Bennani-Smires, Martin Jaggi, Anthony Davison, Mathieu Salzmann, Claudiu Musat
mathjax: true
---

* content
{:toc}

##### Abstract
We identify a phenomenon, which we refer to as multi-model forgetting, that occurs when sequentially training multiple deep networks with partially-shared parameters; the performance of previously-trained models degrades as one optimizes a subsequent one, due to the overwriting of shared parameters. To overcome this, we introduce a statistically-justified weight plasticity loss that regularizes the learning of a model's shared parameters according to their importance for the previous models, and demonstrate its effectiveness when training two models sequentially and for neural architecture search. Adding weight plasticity in neural architecture search preserves the best models to the end of the search and yields improved results in both natural language processing and computer vision tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.08232](https://arxiv.org/abs/1902.08232)

##### PDF
[https://arxiv.org/pdf/1902.08232](https://arxiv.org/pdf/1902.08232)

