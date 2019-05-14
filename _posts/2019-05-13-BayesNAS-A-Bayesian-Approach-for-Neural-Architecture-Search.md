---
layout: post
title: "BayesNAS: A Bayesian Approach for Neural Architecture Search"
date: 2019-05-13 09:00:13
categories: arXiv_AI
tags: arXiv_AI Sparse NAS CNN
author: Hongpeng Zhou, Minghao Yang, Jun Wang, Wei Pan
mathjax: true
---

* content
{:toc}

##### Abstract
One-Shot Neural Architecture Search (NAS) is a promising method to significantly reduce search time without any separate training. It can be treated as a Network Compression problem on the architecture parameters from an over-parameterized network. However, there are two issues associated with most one-shot NAS methods. First, dependencies between a node and its predecessors and successors are often disregarded which result in improper treatment over zero operations. Second, architecture parameters pruning based on their magnitude is questionable. In this paper, we employ the classic Bayesian learning approach to alleviate these two issues by modeling architecture parameters using hierarchical automatic relevance determination (HARD) priors. Unlike other NAS methods, we train the over-parameterized network for only one epoch then update the architecture. Impressively, this enabled us to find the architecture in both proxy and proxyless tasks on CIFAR-10 within only 0.2 GPU days using a single GPU. As a byproduct, our approach can be transferred directly to compress convolutional neural networks by enforcing structural sparsity which achieves extremely sparse networks without accuracy deterioration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04919](http://arxiv.org/abs/1905.04919)

##### PDF
[http://arxiv.org/pdf/1905.04919](http://arxiv.org/pdf/1905.04919)

