---
layout: post
title: "Analysis of Confident-Classifiers for Out-of-distribution Detection"
date: 2019-04-27 22:33:34
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Detection
author: Sachin Vernekar, Ashish Gaurav, Taylor Denouden, Buu Phan, Vahdat Abdelzad, Rick Salay, Krzysztof Czarnecki
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminatively trained neural classifiers can be trusted, only when the input data comes from the training distribution (in-distribution). Therefore, detecting out-of-distribution (OOD) samples is very important to avoid classification errors. In the context of OOD detection for image classification, one of the recent approaches proposes training a classifier called "confident-classifier" by minimizing the standard cross-entropy loss on in-distribution samples and minimizing the KL divergence between the predictive distribution of OOD samples in the low-density regions of in-distribution and the uniform distribution (maximizing the entropy of the outputs). Thus, the samples could be detected as OOD if they have low confidence or high entropy. In this paper, we analyze this setting both theoretically and experimentally. We conclude that the resulting confident-classifier still yields arbitrarily high confidence for OOD samples far away from the in-distribution. We instead suggest training a classifier by adding an explicit "reject" class for OOD samples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12220](http://arxiv.org/abs/1904.12220)

##### PDF
[http://arxiv.org/pdf/1904.12220](http://arxiv.org/pdf/1904.12220)

