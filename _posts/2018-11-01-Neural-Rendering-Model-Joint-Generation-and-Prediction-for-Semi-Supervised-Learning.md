---
layout: post
title: "Neural Rendering Model: Joint Generation and Prediction for Semi-Supervised Learning"
date: 2018-11-01 01:27:37
categories: arXiv_AI
tags: arXiv_AI CNN Inference Classification Prediction
author: Nhat Ho, Tan Nguyen, Ankit Patel, Anima Anandkumar, Michael I. Jordan, Richard G. Baraniuk
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised and semi-supervised learning are important problems that are especially challenging with complex data like natural images. Progress on these problems would accelerate if we had access to appropriate generative models under which to pose the associated inference tasks. Inspired by the success of Convolutional Neural Networks (CNNs) for supervised prediction in images, we design the Neural Rendering Model (NRM), a new probabilistic generative model whose inference calculations correspond to those in a given CNN architecture. The NRM uses the given CNN to design the prior distribution in the probabilistic model. Furthermore, the NRM generates images from coarse to finer scales. It introduces a small set of latent variables at each level, and enforces dependencies among all the latent variables via a conjugate prior distribution. This conjugate prior yields a new regularizer based on paths rendered in the generative model for training CNNs-the Rendering Path Normalization (RPN). We demonstrate that this regularizer improves generalization, both in theory and in practice. In addition, likelihood estimation in the NRM yields training losses for CNNs, and inspired by this, we design a new loss termed as the Max-Min cross entropy which outperforms the traditional cross-entropy loss for object classification. The Max-Min cross entropy suggests a new deep network architecture, namely the Max-Min network, which can learn from less labeled data while maintaining good prediction performance. Our experiments demonstrate that the NRM with the RPN and the Max-Min architecture exceeds or matches the-state-of-art on benchmarks including SVHN, CIFAR10, and CIFAR100 for semi-supervised and supervised learning tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02657](http://arxiv.org/abs/1811.02657)

##### PDF
[http://arxiv.org/pdf/1811.02657](http://arxiv.org/pdf/1811.02657)

