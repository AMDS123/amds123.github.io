---
layout: post
title: "Learning a smooth kernel regularizer for convolutional neural networks"
date: 2019-03-05 15:07:29
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Relation Recognition
author: Reuben Feinman, Brenden M. Lake
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep neural networks require a tremendous amount of data to train, often needing hundreds or thousands of labeled examples to learn an effective representation. For these networks to work with less data, more structure must be built into their architectures or learned from previous experience. The learned weights of convolutional neural networks (CNNs) trained on large datasets for object recognition contain a substantial amount of structure. These representations have parallels to simple cells in the primary visual cortex, where receptive fields are smooth and contain many regularities. Incorporating smoothness constraints over the kernel weights of modern CNN architectures is a promising way to improve their sample complexity. We propose a smooth kernel regularizer that encourages spatial correlations in convolution kernel weights. The correlation parameters of this regularizer are learned from previous experience, yielding a method with a hierarchical Bayesian interpretation. We show that our correlated regularizer can help constrain models for visual recognition, improving over an L2 regularization baseline.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01882](https://arxiv.org/abs/1903.01882)

##### PDF
[https://arxiv.org/pdf/1903.01882](https://arxiv.org/pdf/1903.01882)

