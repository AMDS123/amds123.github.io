---
layout: post
title: "Improving Sentence Representations with Consensus Maximisation"
date: 2019-05-03 18:02:53
categories: arXiv_CL
tags: arXiv_CL RNN
author: Shuai Tang, Virginia R. de Sa
mathjax: true
---

* content
{:toc}

##### Abstract
Consensus maximisation learning can provide self-supervision when different views are available of the same data. The distributional hypothesis provides another form of useful self-supervision from adjacent sentences which are plentiful in large unlabelled corpora. Motivated by the observation that different learning architectures tend to emphasise different aspects of sentence meaning, we present a new self-supervised learning framework for learning sentence representations which minimises the disagreement between two views of the same sentence where one view encodes the sentence with a recurrent neural network (RNN), and the other view encodes the same sentence with a simple linear model. After learning, the individual views (networks) result in higher quality sentence representations than their single-view learnt counterparts (learnt using only the distributional hypothesis) as judged by performance on standard downstream tasks. An ensemble of both views provides even better generalisation on both supervised and unsupervised downstream tasks. Also, importantly the ensemble of views trained with consensus maximisation between the two different architectures performs better on downstream tasks than an analogous ensemble made from the single-view trained counterparts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01064](http://arxiv.org/abs/1810.01064)

##### PDF
[http://arxiv.org/pdf/1810.01064](http://arxiv.org/pdf/1810.01064)

