---
layout: post
title: "Stochastic Gradient Push for Distributed Deep Learning"
date: 2018-11-27 03:47:26
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Mahmoud Assran, Nicolas Loizou, Nicolas Ballas, Michael Rabbat
mathjax: true
---

* content
{:toc}

##### Abstract
Large mini-batch parallel SGD is commonly used for distributed training of deep networks. Approaches that use tightly-coupled exact distributed averaging based on AllReduce are sensitive to slow nodes and high-latency communication. In this work we show the applicability of Stochastic Gradient Push (SGP) for distributed training. SGP uses a gossip algorithm called PushSum for approximate distributed averaging, allowing for much more loosely coupled communications, which can be beneficial in high-latency or high-variability scenarios. The tradeoff is that approximate distributed averaging injects additional noise in the gradient which can affect the train and test accuracies. We prove that SGP converges to a stationary point of smooth, non-convex objective functions. Furthermore, we validate empirically the potential of SGP. For example, using 32 nodes with 8 GPUs per node to train ResNet-50 on ImageNet, where nodes communicate over 10Gbps Ethernet, SGP completes 90 epochs in around 1.6 hours while AllReduce SGD takes over 5 hours, and the top-1 validation accuracy of SGP remains within 1.2% of that obtained using AllReduce SGD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10792](http://arxiv.org/abs/1811.10792)

##### PDF
[http://arxiv.org/pdf/1811.10792](http://arxiv.org/pdf/1811.10792)

