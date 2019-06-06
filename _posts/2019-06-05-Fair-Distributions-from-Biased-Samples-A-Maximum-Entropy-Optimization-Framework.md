---
layout: post
title: "Fair Distributions from Biased Samples: A Maximum Entropy Optimization Framework"
date: 2019-06-05 17:54:00
categories: arXiv_AI
tags: arXiv_AI Optimization Quantitative
author: L. Elisa Celis, Vijay Keswani, Ozan Yildiz, Nisheeth K. Vishnoi
mathjax: true
---

* content
{:toc}

##### Abstract
One reason for the emergence of bias in AI systems is biased data -- datasets that may not be true representations of the underlying distributions -- and may over or under-represent groups with respect to protected attributes such as gender or race. We consider the problem of correcting such biases and learning distributions that are "fair", with respect to measures such as proportional representation and statistical parity, from the given samples. Our approach is based on a novel formulation of the problem of learning a fair distribution as a maximum entropy optimization problem with a given expectation vector and a prior distribution. Technically, our main contributions are: (1) a new second-order method to compute the (dual of the) maximum entropy distribution over an exponentially-sized discrete domain that turns out to be faster than previous methods, and (2) methods to construct prior distributions and expectation vectors that provably guarantee that the learned distributions satisfy a wide class of fairness criteria. Our results also come with quantitative bounds on the total variation distance between the empirical distribution obtained from the samples and the learned fair distribution. Our experimental results include testing our approach on the COMPAS dataset and showing that the fair distributions not only improve disparate impact values but when used to train classifiers only incur a small loss of accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02164](http://arxiv.org/abs/1906.02164)

##### PDF
[http://arxiv.org/pdf/1906.02164](http://arxiv.org/pdf/1906.02164)

