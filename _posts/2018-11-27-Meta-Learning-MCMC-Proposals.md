---
layout: post
title: "Meta-Learning MCMC Proposals"
date: 2018-11-27 12:09:11
categories: arXiv_AI
tags: arXiv_AI Inference Recognition
author: Tongzhou Wang, Yi Wu, David A. Moore, Stuart J. Russell
mathjax: true
---

* content
{:toc}

##### Abstract
Effective implementations of sampling-based probabilistic inference often require manually constructed, model-specific proposals. Inspired by recent progresses in meta-learning for training learning agents that can generalize to unseen environments, we propose a meta-learning approach to building effective and generalizable MCMC proposals. We parametrize the proposal as a neural network to provide fast approximations to block Gibbs conditionals. The learned neural proposals generalize to occurrences of common structural motifs across different models, allowing for the construction of a library of learned inference primitives that can accelerate inference on unseen models with no model-specific training required. We explore several applications including open-universe Gaussian mixture models, in which our learned proposals outperform a hand-tuned sampler, and a real-world named entity recognition task, in which our sampler yields higher final F1 scores than classical single-site Gibbs sampling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.06040](http://arxiv.org/abs/1708.06040)

##### PDF
[http://arxiv.org/pdf/1708.06040](http://arxiv.org/pdf/1708.06040)

