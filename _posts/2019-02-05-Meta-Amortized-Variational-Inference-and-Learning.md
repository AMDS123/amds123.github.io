---
layout: post
title: "Meta-Amortized Variational Inference and Learning"
date: 2019-02-05 22:06:25
categories: arXiv_AI
tags: arXiv_AI Inference
author: Kristy Choi, Mike Wu, Noah Goodman, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
How can we learn to do probabilistic inference in a way that generalizes between models? Amortized variational inference learns for a single model, sharing statistical strength across observations. This benefits scalability and model learning, but does not help with generalization to new models. We propose meta-amortized variational inference, a framework that amortizes the cost of inference over a family of generative models. We apply this approach to deep generative models by introducing the MetaVAE: a variational autoencoder that learns to generalize to new distributions and rapidly solve new unsupervised learning problems using only a small number of target examples. Empirically, we validate the approach by showing that the MetaVAE can: (1) capture relevant sufficient statistics for inference, (2) learn useful representations of data for downstream tasks such as clustering, and (3) perform meta-density estimation on unseen synthetic distributions and out-of-sample Omniglot alphabets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01950](http://arxiv.org/abs/1902.01950)

##### PDF
[http://arxiv.org/pdf/1902.01950](http://arxiv.org/pdf/1902.01950)

