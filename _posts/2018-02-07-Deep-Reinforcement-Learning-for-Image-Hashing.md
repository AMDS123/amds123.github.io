---
layout: post
title: "Deep Reinforcement Learning for Image Hashing"
date: 2018-02-07 15:50:48
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Reinforcement_Learning RNN Relation
author: Jian Zhang, Yuxin Peng, Zhaoda Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Deep hashing methods have received much attention recently, which achieve promising results by taking advantage of the strong representation power of deep networks. However, most existing deep hashing methods learn a whole set of hashing functions independently and directly, while ignore the correlation between different hashing functions that can promote the retrieval accuracy greatly. Inspired by the sequential decision ability of deep reinforcement learning, in this paper, we propose a new Deep Reinforcement Learning approach for Image Hashing (DRLIH). Our proposed DRLIH models the hashing learning problem as a Markov Decision Process (MDP), which learns each hashing function by correcting the errors imposed by previous ones and promotes retrieval accuracy. To the best of our knowledge, this is the first work that tries to address hashing problem from deep reinforcement learning perspective. The main contributions of our proposed DRLIH approach can be summarized as follows: (1) We propose a deep reinforcement learning hashing network. In our proposed DRLIH approach, we utilize recurrent neural network (RNN) as agents to model the hashing functions, which take actions of projecting images into binary codes sequentially, so that current hashing function learning can take previous hashing functions' error into account. (2) We propose a sequential learning strategy based on proposed DRLIH. We define the state as a tuple of internal features of RNN's hidden layers and image features, which can well reflect history decisions made by the agents. We also propose an action group method to enhance the correlation of the hash functions in the same group. Experiments on three widely-used datasets demonstrate the effectiveness of our proposed DRLIH approach.

##### Abstract (translated by Google)
深度散列方法近来备受关注，利用深度网络的强大代表性，取得了较好的效果。然而，大多数现有的深度哈希方法都是独立地，直接地学习一整套哈希函数，而忽略不同哈希函数之间的相关性，可以大大提高检索的准确性。受深度强化学习的顺序决策能力的启发，本文提出了一种新的用于图像哈希的深度强化学习方法（Deep Reinforcement Learning，DRLIH）。我们提出的DRLIH将哈希学习问题作为马尔可夫决策过程（MDP）进行建模，该过程通过纠正以前的错误来学习每个哈希函数，并提高检索的准确性。就我们所知，这是第一个尝试从深入的强化学习的角度来解决哈希问题的工作。我们提出的DRLIH方法的主要贡献可概括如下：（1）我们提出了一个深度强化学习哈希网络。在我们提出的DRLIH方法中，我们利用递归神经网络（RNN）作为代理对哈希函数进行建模，将哈希函数的图像按顺序投影到二进制代码中，使得当前的哈希函数学习可以考虑以前的哈希函数的误差。 （2）提出了基于DRLIH的顺序学习策略。我们将状态定义为RNN隐藏层和图像特征的内部特征元组，能很好地反映代理人做出的历史决策。我们还提出了一个行动组的方法来增强同一组中哈希函数的相关性。三个广泛使用的数据集上的实验证明了我们提出的DRLIH方法的有效性。

##### URL
[http://arxiv.org/abs/1802.02904](http://arxiv.org/abs/1802.02904)

##### PDF
[http://arxiv.org/pdf/1802.02904](http://arxiv.org/pdf/1802.02904)

