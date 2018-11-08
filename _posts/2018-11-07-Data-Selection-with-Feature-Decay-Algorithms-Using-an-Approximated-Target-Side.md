---
layout: post
title: "Data Selection with Feature Decay Algorithms Using an Approximated Target Side"
date: 2018-11-07 17:50:05
categories: arXiv_CL
tags: arXiv_CL NMT
author: Alberto Poncelas, Gideon Maillette de Buy Wenniger, Andy Way
mathjax: true
---

* content
{:toc}

##### Abstract
Data selection techniques applied to neural machine translation (NMT) aim to increase the performance of a model by retrieving a subset of sentences for use as training data. 
 One of the possible data selection techniques are transductive learning methods, which select the data based on the test set, i.e. the document to be translated. A limitation of these methods to date is that using the source-side test set does not by itself guarantee that sentences are selected with correct translations, or translations that are suitable given the test-set domain. Some corpora, such as subtitle corpora, may contain parallel sentences with inaccurate translations caused by localization or length restrictions. 
 In order to try to fix this problem, in this paper we propose to use an approximated target-side in addition to the source-side when selecting suitable sentence-pairs for training a model. This approximated target-side is built by pre-translating the source-side. 
 In this work, we explore the performance of this general idea for one specific data selection approach called Feature Decay Algorithms (FDA). 
 We train German-English NMT models on data selected by using the test set (source), the approximated target side, and a mixture of both. Our findings reveal that models built using a combination of outputs of FDA (using the test set and an approximated target side) perform better than those solely using the test set. We obtain a statistically significant improvement of more than 1.5 BLEU points over a model trained with all data, and more than 0.5 BLEU points over a strong FDA baseline that uses source-side information only.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03039](http://arxiv.org/abs/1811.03039)

##### PDF
[http://arxiv.org/pdf/1811.03039](http://arxiv.org/pdf/1811.03039)

