---
layout: post
title: "Neural Network Quine"
date: 2018-03-17 09:47:43
categories: arXiv_AI
tags: arXiv_AI Image_Classification Optimization Classification Prediction
author: Oscar Chang, Hod Lipson
mathjax: true
---

* content
{:toc}

##### Abstract
Self-replication is a key aspect of biological life that has been largely overlooked in Artificial Intelligence systems. Here we describe how to build and train self-replicating neural networks. The network replicates itself by learning to output its own weights. The network is designed using a loss function that can be optimized with either gradient-based or non-gradient-based methods. We also describe a method we call regeneration to train the network without explicit optimization, by injecting the network with predictions of its own parameters. The best solution for a self-replicating network was found by alternating between regeneration and optimization steps. Finally, we describe a design for a self-replicating neural network that can solve an auxiliary task such as MNIST image classification. We observe that there is a trade-off between the network's ability to classify images and its ability to replicate, but training is biased towards increasing its specialization at image classification at the expense of replication. This is analogous to the trade-off between reproduction and other tasks observed in nature. We suggest that a self-replication mechanism for artificial intelligence is useful because it introduces the possibility of continual improvement through natural selection.

##### Abstract (translated by Google)
自我复制是生物生命的一个关键方面，在人工智能系统中很大程度上被忽视了。这里我们描述如何构建和训练自我复制的神经网络。网络通过学习输出自己的权重来复制自己。该网络的设计使用损失函数，可以使用基于梯度的方法或基于非梯度的方法进行优化。我们还描述了一种我们称之为再生的方法，在没有明确优化的情况下训练网络，通过注入网络来预测其自身参数。自我复制网络的最佳解决方案是通过在再生和优化步骤之间交替发现的。最后，我们描述了一个可以解决诸如MNIST图像分类之类的辅助任务的自我复制神经网络的设计。我们观察到网络对图像进行分类的能力与其复制能力之间存在权衡，但培训偏向于增加其在图像分类方面的专业化，但以复制为代价。这类似于繁殖与自然界观察到的其他任务之间的平衡。我们建议人工智能的自我复制机制是有用的，因为它引入了通过自然选择持续改进的可能性。

##### URL
[https://arxiv.org/abs/1803.05859](https://arxiv.org/abs/1803.05859)

##### PDF
[https://arxiv.org/pdf/1803.05859](https://arxiv.org/pdf/1803.05859)

