---
layout: post
title: "Automated Pruning for Deep Neural Network Compression"
date: 2019-01-06 14:19:12
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Optimization Recognition
author: Franco Manessi, Alessandro Rozza, Simone Bianco, Paolo Napoletano, Raimondo Schettini
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we present a method to improve the pruning step of the current state-of-the-art methodology to compress neural networks. The novelty of the proposed pruning technique is in its differentiability, which allows pruning to be performed during the backpropagation phase of the network training. This enables an end-to-end learning and strongly reduces the training time. The technique is based on a family of differentiable pruning functions and a new regularizer specifically designed to enforce pruning. The experimental results show that the joint optimization of both the thresholds and the network weights permits to reach a higher compression rate, reducing the number of weights of the pruned network by a further 14% to 33% compared to the current state-of-the-art. Furthermore, we believe that this is the first study where the generalization capabilities in transfer learning tasks of the features extracted by a pruned network are analyzed. To achieve this goal, we show that the representations learned using the proposed pruning methodology maintain the same effectiveness and generality of those learned by the corresponding non-compressed network on a set of different recognition tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.01721](http://arxiv.org/abs/1712.01721)

##### PDF
[http://arxiv.org/pdf/1712.01721](http://arxiv.org/pdf/1712.01721)

