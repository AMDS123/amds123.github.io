---
layout: post
title: "Efficient Neural Architecture Search via Parameters Sharing"
date: 2018-02-09 14:14:37
categories: arXiv_CV
tags: arXiv_CV
author: Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Efficient Neural Architecture Search (ENAS), a fast and inexpensive approach for automatic model design. In ENAS, a controller learns to discover neural network architectures by searching for an optimal subgraph within a large computational graph. The controller is trained with policy gradient to select a subgraph that maximizes the expected reward on the validation set. Meanwhile the model corresponding to the selected subgraph is trained to minimize a canonical cross entropy loss. Thanks to parameter sharing between child models, ENAS is fast: it delivers strong empirical performances using much fewer GPU-hours than all existing automatic model design approaches, and notably, 1000x less expensive than standard Neural Architecture Search. On the Penn Treebank dataset, ENAS discovers a novel architecture that achieves a test perplexity of 55.8, establishing a new state-of-the-art among all methods without post-training processing. On the CIFAR-10 dataset, ENAS designs novel architectures that achieve a test error of 2.89%, which is on par with NASNet (Zoph et al., 2018), whose test error is 2.65%.

##### Abstract (translated by Google)
我们提出高效的神经架构搜索（ENAS），一种快速和廉价的自动模型设计方法。在ENAS中，控制器学习通过在大型计算图中搜索最佳子图来发现神经网络体系结构。控制器通过策略梯度进行训练，以选择最大化验证集上预期回报的子图。同时，对应于所选择的子图的模型被训练为使规范的交叉熵损失最小化。由于子模型之间的参数共享，ENAS速度很快：它比现有的所有自动模型设计方法使用的GPU时间少得多，尤其是比标准的Neural Architecture Search要便宜1000倍。在Penn Treebank数据集上，ENAS发现了一种新颖的架构，实现了55.8的测试困惑度，在没有训练后处理的所有方法中建立了新的最新技术。在CIFAR-10数据集上，ENAS设计的新型架构的测试误差为2.89％，与NASNet（Zoph等，2018）相当，测试误差为2.65％。

##### URL
[http://arxiv.org/abs/1802.03268](http://arxiv.org/abs/1802.03268)

##### PDF
[http://arxiv.org/pdf/1802.03268](http://arxiv.org/pdf/1802.03268)

