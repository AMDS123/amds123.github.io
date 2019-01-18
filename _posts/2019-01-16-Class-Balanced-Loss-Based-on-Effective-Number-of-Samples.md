---
layout: post
title: "Class-Balanced Loss Based on Effective Number of Samples"
date: 2019-01-16 23:03:45
categories: arXiv_CV
tags: arXiv_CV
author: Yin Cui, Menglin Jia, Tsung-Yi Lin, Yang Song, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
With the rapid increase of large-scale, real-world datasets, it becomes critical to address the problem of long-tailed data distribution (i.e., a few classes account for most of the data, while most classes are under-represented). Existing solutions typically adopt class re-balancing strategies such as re-sampling and re-weighting based on the number of observations for each class. In this work, we argue that as the number of samples increases, the additional benefit of a newly added data point will diminish. We introduce a novel theoretical framework to measure data overlap by associating with each sample a small neighboring region rather than a single point. The effective number of samples is defined as the volume of samples and can be calculated by a simple formula $(1-β^{n})/(1-β)$, where $n$ is the number of samples and $β\in [0,1)$ is a hyperparameter. We design a re-weighting scheme that uses the effective number of samples for each class to re-balance the loss, thereby yielding a class-balanced loss. Comprehensive experiments are conducted on artificially induced long-tailed CIFAR datasets and large-scale datasets including ImageNet and iNaturalist. Our results show that when trained with the proposed class-balanced loss, the network is able to achieve significant performance gains on long-tailed datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05555](https://arxiv.org/abs/1901.05555)

##### PDF
[https://arxiv.org/pdf/1901.05555](https://arxiv.org/pdf/1901.05555)

