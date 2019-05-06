---
layout: post
title: "Efficient Neural Architecture Search via Parameter Sharing"
date: 2018-02-12 03:34:00
categories: arXiv_CV
tags: arXiv_CV NAS
author: Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Efficient Neural Architecture Search (ENAS), a fast and inexpensive approach for automatic model design. In ENAS, a controller learns to discover neural network architectures by searching for an optimal subgraph within a large computational graph. The controller is trained with policy gradient to select a subgraph that maximizes the expected reward on the validation set. Meanwhile the model corresponding to the selected subgraph is trained to minimize a canonical cross entropy loss. Thanks to parameter sharing between child models, ENAS is fast: it delivers strong empirical performances using much fewer GPU-hours than all existing automatic model design approaches, and notably, 1000x less expensive than standard Neural Architecture Search. On the Penn Treebank dataset, ENAS discovers a novel architecture that achieves a test perplexity of 55.8, establishing a new state-of-the-art among all methods without post-training processing. On the CIFAR-10 dataset, ENAS designs novel architectures that achieve a test error of 2.89%, which is on par with NASNet (Zoph et al., 2018), whose test error is 2.65%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.03268](https://arxiv.org/abs/1802.03268)

##### PDF
[https://arxiv.org/pdf/1802.03268](https://arxiv.org/pdf/1802.03268)

