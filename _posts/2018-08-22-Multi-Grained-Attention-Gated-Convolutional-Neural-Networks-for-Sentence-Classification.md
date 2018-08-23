---
layout: post
title: "Multi-Grained-Attention Gated Convolutional Neural Networks for Sentence Classification"
date: 2018-08-22 12:03:48
categories: arXiv_CL
tags: arXiv_CL Attention CNN Classification Prediction
author: Yang Liu, Lixin Ji, Ruiyang Huang, Tuosiyu Ming
mathjax: true
---

* content
{:toc}

##### Abstract
The classification task of sentences is very challenging because of the limited contextual information they contain. Current methods based on Convolutional Neural Networks (CNNs) for sentence classification do not have a simple and effective mechanism to determine which features in the network are critical and could become large enough that affect the classification result. In this paper, we propose a new CNN model named Multi-Grained-Attention Gated CNN (MGAGCNN), which generates attention weights from the context window of different sizes based on the Multi-Grained-Attention (MGA) gating mechanism. Through the experiments of comparison and attention visualization, we demonstrate that with the help of MGA gating mechanism, our model could learn more meaningful and comprehensive abstract features and adequately identify the critical features, and enhance their influence on the prediction of sentence category. In addition, we propose an activation function named Natural Logarithm rescaled Rectified Linear Unit (NLReLU). Experimental results show that our model could achieve a general accuracy improvement ranging from 0.4% to 1.7% (compared with standard CNN models), and gain competitive results over the strong baseline methods on four out of the six tasks, and NLReLU could achieve comparable performances on MGAGCNN to other well-known activation functions.

##### Abstract (translated by Google)
句子的分类任务非常具有挑战性，因为它们包含的上下文信息有限。当前用于句子分类的基于卷积神经网络（CNN）的方法没有简单有效的机制来确定网络中哪些特征是关键的并且可能变得足够大以影响分类结果。在本文中，我们提出了一种名为Multi-Grained-Attention Gated CNN（MGAGCNN）的新CNN模型，该模型基于多粒度注意（MGA）门控机制从不同大小的上下文窗口生成注意权重。通过比较和注意可视化实验，证明了在MGA门控机制的帮助下，我们的模型可以学习更有意义，更全面的抽象特征，充分识别关键特征，增强其对句类预测的影响。此外，我们提出了一个名为Natural Logarithm rescaled Rectified Linear Unit（NLReLU）的激活函数。实验结果表明，我们的模型可以实现从0.4％到1.7％的一般精度改善（与标准CNN模型相比），并且在六个任务中的四个中获得了比强基线方法更有竞争力的结果，并且NLReLU可以实现相当的性能在MGAGCNN上其他众所周知的激活函数。

##### URL
[http://arxiv.org/abs/1808.07325](http://arxiv.org/abs/1808.07325)

##### PDF
[http://arxiv.org/pdf/1808.07325](http://arxiv.org/pdf/1808.07325)

