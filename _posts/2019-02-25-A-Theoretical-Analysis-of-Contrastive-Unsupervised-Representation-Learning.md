---
layout: post
title: "A Theoretical Analysis of Contrastive Unsupervised Representation Learning"
date: 2019-02-25 12:32:15
categories: arXiv_AI
tags: arXiv_AI Embedding Represenation_Learning Classification Language_Model
author: Sanjeev Arora, Hrishikesh Khandeparkar, Mikhail Khodak, Orestis Plevrakis, Nikunj Saunshi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent empirical works have successfully used unlabeled data to learn feature representations that are broadly useful in downstream classification tasks. Several of these methods are reminiscent of the well-known word2vec embedding algorithm: leveraging availability of pairs of semantically "similar" data points and "negative samples," the learner forces the inner product of representations of similar pairs with each other to be higher on average than with negative samples. The current paper uses the term contrastive learning for such algorithms and presents a theoretical framework for analyzing them by introducing latent classes and hypothesizing that semantically similar points are sampled from the same latent class. This framework allows us to show provable guarantees on the performance of the learned representations on the average classification task that is comprised of a subset of the same set of latent classes. Our generalization bound also shows that learned representations can reduce (labeled) sample complexity on downstream tasks. We conduct controlled experiments in both the text and image domains to support the theory.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09229](http://arxiv.org/abs/1902.09229)

##### PDF
[http://arxiv.org/pdf/1902.09229](http://arxiv.org/pdf/1902.09229)

