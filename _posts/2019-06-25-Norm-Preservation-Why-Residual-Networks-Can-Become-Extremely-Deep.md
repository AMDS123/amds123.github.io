---
layout: post
title: "Norm-Preservation: Why Residual Networks Can Become Extremely Deep?"
date: 2019-06-25 22:05:37
categories: arXiv_CV
tags: arXiv_CV OCR Optimization Classification
author: Alireza Zaeemzadeh, Nazanin Rahnavard, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Augmenting neural networks with skip connections, as introduced in the so-called ResNet architecture, surprised the community by enabling the training of networks of more than 1,000 layers with significant performance gains. This paper deciphers ResNet by analyzing the effect of skip connections, and puts forward new theoretical results on the advantages of identity skip connections in neural networks. We prove that the skip connections in the residual blocks facilitate preserving the norm of the gradient, and lead to stable back-propagation, which is desirable from optimization perspective. We also show that, perhaps surprisingly, as more residual blocks are stacked, the norm-preservation of the network is enhanced. Our theoretical arguments are supported by extensive empirical evidence. Can we push for extra norm-preservation? We answer this question by proposing an efficient method to regularize the singular values of the convolution operator and making the ResNet's transition layers extra norm-preserving. Our numerical investigations demonstrate that the learning dynamics and the classification performance of ResNet can be improved by making it even more norm preserving. Our results and the introduced modification for ResNet, referred to as Procrustes ResNets, can be used as a guide for training deeper networks and can also inspire new deeper architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07477](http://arxiv.org/abs/1805.07477)

##### PDF
[http://arxiv.org/pdf/1805.07477](http://arxiv.org/pdf/1805.07477)

