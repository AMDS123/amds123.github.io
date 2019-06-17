---
layout: post
title: "A Signal Propagation Perspective for Pruning Neural Networks at Initialization"
date: 2019-06-14 17:26:29
categories: arXiv_CV
tags: arXiv_CV
author: Namhoon Lee, Thalaiyasingam Ajanthan, Stephen Gould, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Network pruning is a promising avenue for compressing deep neural networks. A typical approach to pruning starts by training a model and removing unnecessary parameters while minimizing the impact on what is learned. Alternatively, a recent approach shows that pruning can be done at initialization prior to training. However, it remains unclear exactly why pruning an untrained, randomly initialized neural network is effective. In this work, we consider the pruning problem from a signal propagation perspective, formally characterizing initialization conditions that ensure faithful signal propagation throughout a network. Based on singular values of a network's input-output Jacobian, we find that orthogonal initialization enables more faithful signal propagation compared to other initialization schemes, thereby enhancing pruning results on a range of modern architectures and datasets. Also, we empirically study the effect of supervision for pruning at initialization, and show that often unsupervised pruning can be as effective as the supervised pruning. Furthermore, we demonstrate that our signal propagation perspective, combined with unsupervised pruning, can indeed be useful in various scenarios where pruning is applied to non-standard arbitrarily-designed architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06307](https://arxiv.org/abs/1906.06307)

##### PDF
[https://arxiv.org/pdf/1906.06307](https://arxiv.org/pdf/1906.06307)

