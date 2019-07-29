---
layout: post
title: "LinearConv: Regenerating Redundancy in Convolution Filters as Linear Combinations for Parameter Reduction"
date: 2019-07-26 08:39:31
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Relation
author: Kumara Kahatapitiya, Ranga Rodrigo
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) show state-of-the-art performance in computer vision tasks. However, convolutional layers of CNNs are known to learn redundant features, still not being efficient in memory requirement. In this work, we explore the redundancy of learned features in the form of correlation between convolutional filters, and propose a novel layer to reproduce it efficiently. The proposed "LinearConv" layer generates a portion of convolutional filters as a learnable linear combination of the rest of the filters and introduces a correlation-based regularization to achieve flexibility and control over the correlation between filters, and the number of parameters, in turn. This is developed as a plug-in layer to conveniently replace a conventional convolutional layer without any modification required in the network architecture. Our experiments verify that the LinearConv-based models are able to achieve a performance on-par with counterparts with up to 50% of parameter reduction, and having same computational requirement in run time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11432](http://arxiv.org/abs/1907.11432)

##### PDF
[http://arxiv.org/pdf/1907.11432](http://arxiv.org/pdf/1907.11432)

