---
layout: post
title: "Are Labels Required for Improving Adversarial Robustness?"
date: 2019-05-31 17:19:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Jonathan Uesato*, Jean-Baptiste Alayrac*, Po-Sen Huang*, Robert Stanforth, Alhussein Fawzi, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has uncovered the interesting (and somewhat surprising) finding that training models to be invariant to adversarial perturbations requires substantially larger datasets than those required for standard classification. This result is a key hurdle in the deployment of robust machine learning models in many real world applications where labeled data is expensive. Our main insight is that unlabeled data can be a competitive alternative to labeled data for training adversarially robust models. Theoretically, we show that in a simple statistical setting, the sample complexity for learning an adversarially robust model from unlabeled data matches the fully supervised case up to constant factors. On standard datasets like CIFAR-10, a simple Unsupervised Adversarial Training (UAT) approach using unlabeled data improves robust accuracy by 21.7% over using 4K supervised examples alone, and captures over 95% of the improvement from the same number of labeled examples. Finally, we report an improvement of 4% over the previous state-of-the-art on CIFAR-10 against the strongest known attack by using additional unlabeled data from the uncurated 80 Million Tiny Images dataset. This demonstrates that our finding extends as well to the more realistic case where unlabeled data is also uncurated, therefore opening a new avenue for improving adversarial training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13725](http://arxiv.org/abs/1905.13725)

##### PDF
[http://arxiv.org/pdf/1905.13725](http://arxiv.org/pdf/1905.13725)

