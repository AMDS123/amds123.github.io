---
layout: post
title: "Controlling the privacy loss with the input feature maps of the layers in convolutional neural networks"
date: 2018-12-05 12:03:32
categories: arXiv_CV
tags: arXiv_CV CNN
author: Woohyung Chun, Sung-Min Hong, Junho Huh, Inyup Kang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the method to sanitize the privacy of the IFM(Input Feature Map)s that are fed into the layers of CNN(Convolutional Neural Network)s. The method introduces the degree of the sanitization that makes the application using a CNN be able to control the privacy loss represented as the ratio of the probabilistic accuracies for original IFM and sanitized IFM. For the sanitization of an IFM, the sample-and-hold based approximation scheme is devised to satisfy an application-specific degree of the sanitization. The scheme approximates an IFM by replacing all the samples in a window with the non-zero sample closest to the mean of the sampling window. It also removes the dependency on CNN configuration by unfolding multi-dimensional IFM tensors into one-dimensional streams to be approximated.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.03444](http://arxiv.org/abs/1805.03444)

##### PDF
[http://arxiv.org/pdf/1805.03444](http://arxiv.org/pdf/1805.03444)

