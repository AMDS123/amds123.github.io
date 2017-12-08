---
layout: post
title: "Avoiding Your Teacher's Mistakes: Training Neural Networks with Controlled Weak Supervision"
date: 2017-12-07 14:30:18
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Classification
author: Mostafa Dehghani, Aliaksei Severyn, Sascha Rothe, Jaap Kamps
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep neural networks requires massive amounts of training data, but for many tasks only limited labeled data is available. This makes weak supervision attractive, using weak or noisy signals like the output of heuristic methods or user click-through data for training. In a semi-supervised setting, we can use a large set of data with weak labels to pretrain a neural network and then fine-tune the parameters with a small amount of data with true labels. This feels intuitively sub-optimal as these two independent stages leave the model unaware about the varying label quality. What if we could somehow inform the model about the label quality? In this paper, we propose a semi-supervised learning method where we train two neural networks in a multi-task fashion: a "target network" and a "confidence network". The target network is optimized to perform a given task and is trained using a large set of unlabeled data that are weakly annotated. We propose to weight the gradient updates to the target network using the scores provided by the second confidence network, which is trained on a small amount of supervised data. Thus we avoid that the weight updates computed from noisy labels harm the quality of the target network model. We evaluate our learning strategy on two different tasks: document ranking and sentiment classification. The results demonstrate that our approach not only enhances the performance compared to the baselines but also speeds up the learning process from weak labels.

##### Abstract (translated by Google)
训练深度神经网络需要大量的训练数据，但是对于许多任务，只有有限的标记数据是可用的。这使弱监督有吸引力，使用弱启发式方法或用户点击数据训练等信号。在一个半监督的环境下，我们可以使用大量的弱标签数据来预训神经网络，然后用少量的真实标签数据对参数进行微调。由于这两个独立的阶段使得模型不知道标签质量的变化，所以这种感觉直觉上是次佳的。如果我们能以某种方式通知模型关于标签质量呢？在本文中，我们提出了一个半监督学习方法，我们训练两个神经网络在多任务的方式：“目标网络”和“信心网络”。目标网络被优化以执行给定的任务，并使用大量未标记的数据进行训练，这些数据被弱注释。我们建议使用由第二个置信网络提供的分数来对目标网络的梯度更新进行加权，所述第二置信网络受到少量监督数据的训练。因此，我们避免从噪声标签计算出的权重更新损害目标网络模型的质量。我们评估我们的学习策略有两个不同的任务：文档排名和情感分类。结果表明，我们的方法不仅提高了与基线相比的性能，而且加速了弱标签的学习过程。

##### URL
[http://arxiv.org/abs/1711.00313](http://arxiv.org/abs/1711.00313)

##### PDF
[http://arxiv.org/pdf/1711.00313](http://arxiv.org/pdf/1711.00313)

