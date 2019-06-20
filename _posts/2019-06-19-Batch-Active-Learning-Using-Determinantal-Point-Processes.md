---
layout: post
title: "Batch Active Learning Using Determinantal Point Processes"
date: 2019-06-19 08:45:59
categories: arXiv_AI
tags: arXiv_AI
author: Erdem B&#x131;y&#x131;k, Kenneth Wang, Nima Anari, Dorsa Sadigh
mathjax: true
---

* content
{:toc}

##### Abstract
Data collection and labeling is one of the main challenges in employing machine learning algorithms in a variety of real-world applications with limited data. While active learning methods attempt to tackle this issue by labeling only the data samples that give high information, they generally suffer from large computational costs and are impractical in settings where data can be collected in parallel. Batch active learning methods attempt to overcome this computational burden by querying batches of samples at a time. To avoid redundancy between samples, previous works rely on some ad hoc combination of sample quality and diversity. In this paper, we present a new principled batch active learning method using Determinantal Point Processes, a repulsive point process that enables generating diverse batches of samples. We develop tractable algorithms to approximate the mode of a DPP distribution, and provide theoretical guarantees on the degree of approximation. We further demonstrate that an iterative greedy method for DPP maximization, which has lower computational costs but worse theoretical guarantees, still gives competitive results for batch active learning. Our experiments show the value of our methods on several datasets against state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07975](http://arxiv.org/abs/1906.07975)

##### PDF
[http://arxiv.org/pdf/1906.07975](http://arxiv.org/pdf/1906.07975)

