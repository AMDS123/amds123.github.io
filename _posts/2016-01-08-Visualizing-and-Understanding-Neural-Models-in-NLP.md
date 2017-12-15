---
layout: post
title: "Visualizing and Understanding Neural Models in NLP"
date: 2016-01-08 18:10:22
categories: arXiv_CL
tags: arXiv_CL Sentiment RNN
author: Jiwei Li, Xinlei Chen, Eduard Hovy, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
While neural networks have been successfully applied to many NLP tasks the resulting vector-based models are very difficult to interpret. For example it's not clear how they achieve {\em compositionality}, building sentence meaning from the meanings of words and phrases. In this paper we describe four strategies for visualizing compositionality in neural models for NLP, inspired by similar work in computer vision. We first plot unit values to visualize compositionality of negation, intensification, and concessive clauses, allow us to see well-known markedness asymmetries in negation. We then introduce three simple and straightforward methods for visualizing a unit's {\em salience}, the amount it contributes to the final composed meaning: (1) gradient back-propagation, (2) the variance of a token from the average word node, (3) LSTM-style gates that measure information flow. We test our methods on sentiment using simple recurrent nets and LSTMs. Our general-purpose methods may have wide applications for understanding compositionality and other semantic properties of deep networks , and also shed light on why LSTMs outperform simple recurrent nets,

##### Abstract (translated by Google)
虽然神经网络已经成功应用于许多NLP任务，但所得到的基于向量的模型很难解释。例如，他们如何实现“组合性”，从单词和短语的含义来构建句子的含义并不清楚。在本文中，我们描述了四种可视化组合性的NLP神经模型的策略，受到计算机视觉类似工作的启发。我们首先绘制单位价值观来表达否定，强化和让步条款的组合性，使我们能够在否定中看到众所周知的显着性不对称。然后，我们介绍三种简单直接的方法来显示一个单元的显着性，它是对最终组成意义的贡献量：（1）梯度反向传播;（2）来自平均单词节点的一个单词的方差; （3）测量信息流的LSTM式门。我们使用简单的经常性网络和LSTM来测试我们的情绪方法。我们的通用方法可能在理解深度网络的组合性和其他语义特性方面有广泛的应用，同时也阐明了为什么LSTMs胜过简单的经常性网络，

##### URL
[https://arxiv.org/abs/1506.01066](https://arxiv.org/abs/1506.01066)

##### PDF
[https://arxiv.org/pdf/1506.01066](https://arxiv.org/pdf/1506.01066)

