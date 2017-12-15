---
layout: post
title: "Zoneout: Regularizing RNNs by Randomly Preserving Hidden Activations"
date: 2017-09-22 20:43:09
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: David Krueger, Tegan Maharaj, János Kramár, Mohammad Pezeshki, Nicolas Ballas, Nan Rosemary Ke, Anirudh Goyal, Yoshua Bengio, Aaron Courville, Chris Pal
mathjax: true
---

* content
{:toc}

##### Abstract
We propose zoneout, a novel method for regularizing RNNs. At each timestep, zoneout stochastically forces some hidden units to maintain their previous values. Like dropout, zoneout uses random noise to train a pseudo-ensemble, improving generalization. But by preserving instead of dropping hidden units, gradient information and state information are more readily propagated through time, as in feedforward stochastic depth networks. We perform an empirical investigation of various RNN regularizers, and find that zoneout gives significant performance improvements across tasks. We achieve competitive results with relatively simple models in character- and word-level language modelling on the Penn Treebank and Text8 datasets, and combining with recurrent batch normalization yields state-of-the-art results on permuted sequential MNIST.

##### Abstract (translated by Google)
我们提出了区域划分，一种新的正则化RNN的方法。在每个时间步，分区随机地强制一些隐藏的单位保持以前的值。就像辍学一样，旷课使用随机噪音来训练一个伪合奏，从而提高泛化能力。但是通过保留而不是丢弃隐藏单元，梯度信息和状态信息更容易随时间传播，就像前馈随机深度网络一样。我们对各种RNN正则化规则进行了实证研究，发现在各个任务中，区域划分显着提高了性能。我们在Penn Treebank和Text8数据集的字符和词汇语言建模中使用相对简单的模型来获得有竞争力的结果，并且与重复的批量归一化相结合，可以在置换的顺序MNIST上得出最新的结果。

##### URL
[https://arxiv.org/abs/1606.01305](https://arxiv.org/abs/1606.01305)

##### PDF
[https://arxiv.org/pdf/1606.01305](https://arxiv.org/pdf/1606.01305)

