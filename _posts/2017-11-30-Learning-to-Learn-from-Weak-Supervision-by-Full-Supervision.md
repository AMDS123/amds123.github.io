---
layout: post
title: "Learning to Learn from Weak Supervision by Full Supervision"
date: 2017-11-30 13:32:45
categories: arXiv_CL
tags: arXiv_CL
author: Mostafa Dehghani, Aliaksei Severyn, Sascha Rothe, Jaap Kamps
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for training neural networks when we have a large set of data with weak labels and a small amount of data with true labels. In our proposed model, we train two neural networks: a target network, the learner and a confidence network, the meta-learner. The target network is optimized to perform a given task and is trained using a large set of unlabeled data that are weakly annotated. We propose to control the magnitude of the gradient updates to the target network using the scores provided by the second confidence network, which is trained on a small amount of supervised data. Thus we avoid that the weight updates computed from noisy labels harm the quality of the target network model.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于在具有弱标签和少量具有真正标签的数据的大量数据时训练神经网络的方法。在我们提出的模型中，我们训练两个神经网络：一个目标网络，学习者和一个信任网络，元学习者。目标网络被优化以执行给定的任务，并且使用大量未标记的数据进行训练，这些数据被弱注释。我们建议使用第二个置信网络提供的分数来控制对目标网络的梯度更新的大小，所述第二置信网络受到少量监督数据的训练。因此，我们避免从噪声标签计算出的权重更新损害目标网络模型的质量。

##### URL
[https://arxiv.org/abs/1711.11383](https://arxiv.org/abs/1711.11383)

