---
layout: post
title: "RNNs Implicitly Implement Tensor Product Representations"
date: 2018-12-20 17:44:05
categories: arXiv_CL
tags: arXiv_CL Represenation_Learning RNN
author: R. Thomas McCoy, Tal Linzen, Ewan Dunbar, Paul Smolensky
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) can learn continuous vector representations of symbolic structures such as sequences and sentences; these representations often exhibit linear regularities (analogies). Such regularities motivate our hypothesis that RNNs that show such regularities implicitly compile symbolic structures into tensor product representations (TPRs; Smolensky, 1990), which additively combine tensor products of vectors representing roles (e.g., sequence positions) and vectors representing fillers (e.g., particular words). To test this hypothesis, we introduce Tensor Product Decomposition Networks (TPDNs), which use TPRs to approximate existing vector representations. We demonstrate using synthetic data that TPDNs can successfully approximate linear and tree-based RNN autoencoder representations, suggesting that these representations exhibit interpretable compositional structure; we explore the settings that lead RNNs to induce such structure-sensitive representations. By contrast, further TPDN experiments show that the representations of four models trained to encode naturally-occurring sentences can be largely approximated with a bag-of-words, with only marginal improvements from more sophisticated structures. We conclude that TPDNs provide a powerful method for interpreting vector representations, and that standard RNNs can induce compositional sequence representations that are remarkably well approximated by TPRs; at the same time, existing training tasks for sentence representation learning may not be sufficient for inducing robust structural representations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08718](http://arxiv.org/abs/1812.08718)

##### PDF
[http://arxiv.org/pdf/1812.08718](http://arxiv.org/pdf/1812.08718)

