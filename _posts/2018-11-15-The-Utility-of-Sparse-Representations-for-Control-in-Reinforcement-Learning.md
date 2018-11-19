---
layout: post
title: "The Utility of Sparse Representations for Control in Reinforcement Learning"
date: 2018-11-15 23:23:36
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Vincent Liu, Raksha Kumaraswamy, Lei Le, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate sparse representations for control in reinforcement learning. While these representations are widely used in computer vision, their prevalence in reinforcement learning is limited to sparse coding where extracting representations for new data can be computationally intensive. Here, we begin by demonstrating that learning a control policy incrementally with a representation from a standard neural network fails in classic control domains, whereas learning with a representation obtained from a neural network that has sparsity properties enforced is effective. We provide evidence that the reason for this is that the sparse representation provides locality, and so avoids catastrophic interference, and particularly keeps consistent, stable values for bootstrapping. We then discuss how to learn such sparse representations. We explore the idea of Distributional Regularizers, where the activation of hidden nodes is encouraged to match a particular distribution that results in sparse activation across time. We identify a simple but effective way to obtain sparse representations, not afforded by previously proposed strategies, making it more practical for further investigation into sparse representations for reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06626](http://arxiv.org/abs/1811.06626)

##### PDF
[http://arxiv.org/pdf/1811.06626](http://arxiv.org/pdf/1811.06626)

