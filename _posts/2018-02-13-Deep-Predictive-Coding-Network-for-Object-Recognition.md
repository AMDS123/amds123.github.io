---
layout: post
title: "Deep Predictive Coding Network for Object Recognition"
date: 2018-02-13 17:49:33
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Prediction Recognition
author: Haiguang Wen, Kuan Han, Junxing Shi, Yizhen Zhang, Eugenio Culurciello, Zhongming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by predictive coding in neuroscience, we designed a bi-directional and recurrent neural net, namely deep predictive coding networks (PCN). It uses convolutional layers in both feedforward and feedback networks, and recurrent connections within each layer. Feedback connections from a higher layer carry the prediction of its lower-layer representation; feedforward connections carry the prediction errors to its higher-layer. Given image input, PCN runs recursive cycles of bottom-up and top-down computation to update its internal representations to reduce the difference between bottom-up input and top-down prediction at every layer. After multiple cycles of recursive updating, the representation is used for image classification. In training, the classification error backpropagates across layers and in time. With benchmark data (CIFAR-10/100, SVHN, and MNIST), PCN was found to always outperform its feedforward-only counterpart: a model without any mechanism for recurrent dynamics, and its performance tended to improve given more cycles of computation over time. In short, PCN reuses a single architecture to recursively run bottom-up and top-down process, enabling an increasingly longer cascade of non-linear transformation. For image classification, PCN refines its representation over time towards more accurate and definitive recognition.

##### Abstract (translated by Google)
受到神经科学预测编码的启发，我们设计了一个双向和循环神经网络，即深度预测编码网络（PCN）。它在前馈和反馈网络中使用卷积层，并在每层中使用循环连接。来自较高层的反馈连接进行其较低层表示的预测;前馈连接将预测误差带到其更高层。在给定图像输入的情况下，PCN运行自下而上和自上而下计算的递归循环来更新其内部表示，以减少每层的自底向上输入和自顶向下预测之间的差异。在递归更新的多个循环之后，该表示被用于图像分类。在训练中，分类错误反向传播层次和时间。通过基准数据（CIFAR-10/100，SVHN和MNIST），发现PCN总是胜过仅前馈对应模型：一种没有任何反复动态机制的模型，并且随着时间的推移计算更多循环，其性能趋于改善。简而言之，PCN重用单一体系结构以递归方式运行自下而上和自上而下的流程，从而实现日益更长的非线性转换级联。对于图像分类，PCN随着时间的推移提高了其表示的准确性和确定性。

##### URL
[http://arxiv.org/abs/1802.04762](http://arxiv.org/abs/1802.04762)

##### PDF
[http://arxiv.org/pdf/1802.04762](http://arxiv.org/pdf/1802.04762)

