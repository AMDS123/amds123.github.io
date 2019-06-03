---
layout: post
title: "Deterministic PAC-Bayesian generalization bounds for deep networks via generalizing noise-resilience"
date: 2019-05-30 22:45:06
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Vaishnavh Nagarajan, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
The ability of overparameterized deep networks to generalize well has been linked to the fact that stochastic gradient descent (SGD) finds solutions that lie in flat, wide minima in the training loss -- minima where the output of the network is resilient to small random noise added to its parameters. So far this observation has been used to provide generalization guarantees only for neural networks whose parameters are either \textit{stochastic} or \textit{compressed}. In this work, we present a general PAC-Bayesian framework that leverages this observation to provide a bound on the original network learned -- a network that is deterministic and uncompressed. What enables us to do this is a key novelty in our approach: our framework allows us to show that if on training data, the interactions between the weight matrices satisfy certain conditions that imply a wide training loss minimum, these conditions themselves {\em generalize} to the interactions between the matrices on test data, thereby implying a wide test loss minimum. We then apply our general framework in a setup where we assume that the pre-activation values of the network are not too small (although we assume this only on the training data). In this setup, we provide a generalization guarantee for the original (deterministic, uncompressed) network, that does not scale with product of the spectral norms of the weight matrices -- a guarantee that would not have been possible with prior approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13344](http://arxiv.org/abs/1905.13344)

##### PDF
[http://arxiv.org/pdf/1905.13344](http://arxiv.org/pdf/1905.13344)

