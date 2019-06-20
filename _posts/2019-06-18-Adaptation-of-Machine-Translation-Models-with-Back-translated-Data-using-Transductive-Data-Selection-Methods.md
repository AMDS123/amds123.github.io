---
layout: post
title: "Adaptation of Machine Translation Models with Back-translated Data using Transductive Data Selection Methods"
date: 2019-06-18 20:56:11
categories: arXiv_CL
tags: arXiv_CL NMT
author: Alberto Poncelas, Gideon Maillette de Buy Wenniger, Andy Way
mathjax: true
---

* content
{:toc}

##### Abstract
Data selection has proven its merit for improving Neural Machine Translation (NMT), when applied to authentic data. But the benefit of using synthetic data in NMT training, produced by the popular back-translation technique, raises the question if data selection could also be useful for synthetic data? 
 In this work we use Infrequent N-gram Recovery (INR) and Feature Decay Algorithms (FDA), two transductive data selection methods to obtain subsets of sentences from synthetic data. These methods ensure that selected sentences share n-grams with the test set so the NMT model can be adapted to translate it. 
 Performing data selection on back-translated data creates new challenges as the source-side may contain noise originated by the model used in the back-translation. Hence, finding n-grams present in the test set become more difficult. Despite that, in our work we show that adapting a model with a selection of synthetic data is an useful approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07808](http://arxiv.org/abs/1906.07808)

##### PDF
[http://arxiv.org/pdf/1906.07808](http://arxiv.org/pdf/1906.07808)

