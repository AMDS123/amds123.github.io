---
layout: post
title: "Densely Connected Bidirectional LSTM with Applications to Sentence Classification"
date: 2018-02-03 01:40:20
categories: arXiv_CL
tags: arXiv_CL RNN Classification
author: Zixiang Ding, Rui Xia, Jianfei Yu, Xiang Li, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have recently been shown to achieve highly competitive performance in many computer vision tasks due to their abilities of exploring in a much larger hypothesis space. However, since most deep architectures like stacked RNNs tend to suffer from the vanishing-gradient and overfitting problems, their effects are still understudied in many NLP tasks. Inspired by this, we propose a novel multi-layer RNN model called densely connected bidirectional long short-term memory (DC-Bi-LSTM) in this paper, which essentially represents each layer by the concatenation of its hidden state and all preceding layers' hidden states, followed by recursively passing each layer's representation to all subsequent layers. We evaluate our proposed model on five benchmark datasets of sentence classification. DC-Bi-LSTM with depth up to 20 can be successfully trained and obtain significant improvements over the traditional Bi-LSTM with the same or even less parameters. Moreover, our model has promising performance compared with the state-of-the-art approaches.

##### Abstract (translated by Google)
最近，深度神经网络被证明在许多计算机视觉任务中实现高度竞争的性能，因为它们能够在更大的假设空间中进行探索。然而，由于大多数深层架构（如叠加RNN）倾向于受到消失梯度和过度拟合问题的困扰，因此在许多NLP任务中，其效果仍未得到充分研究。受此启发，本文提出了一种新的多层RNN模型，称为密集连接双向长时间短时记忆（DC-Bi-LSTM），其实质上是通过隐含状态与前面所有层的连接，隐藏状态，然后递归地将每个图层的表示传递给所有后续图层。我们评估我们提出的五个基准数据集的句子分类模型。深度达20的DC-Bi-LSTM可以成功地进行训练，并且相对于传统的Bi-LSTM具有相同甚至更少的参数。而且，与最先进的方法相比，我们的模型具有很好的性能。

##### URL
[http://arxiv.org/abs/1802.00889](http://arxiv.org/abs/1802.00889)

##### PDF
[http://arxiv.org/pdf/1802.00889](http://arxiv.org/pdf/1802.00889)

