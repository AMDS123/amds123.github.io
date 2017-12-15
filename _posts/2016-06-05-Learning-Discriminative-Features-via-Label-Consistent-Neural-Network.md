---
layout: post
title: "Learning Discriminative Features via Label Consistent Neural Network"
date: 2016-06-05 02:45:35
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Classification Prediction Recognition
author: Zhuolin Jiang, Yaming Wang, Larry Davis, Walt Andrews, Viktor Rozgic
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNN) enforces supervised information only at the output layer, and hidden layers are trained by back propagating the prediction error from the output layer without explicit supervision. We propose a supervised feature learning approach, Label Consistent Neural Network, which enforces direct supervision in late hidden layers. We associate each neuron in a hidden layer with a particular class label and encourage it to be activated for input signals from the same class. More specifically, we introduce a label consistency regularization called "discriminative representation error" loss for late hidden layers and combine it with classification error loss to build our overall objective function. This label consistency constraint alleviates the common problem of gradient vanishing and tends to faster convergence; it also makes the features derived from late hidden layers discriminative enough for classification even using a simple $k$-NN classifier, since input signals from the same class will have very similar representations. Experimental results demonstrate that our approach achieves state-of-the-art performances on several public benchmarks for action and object category recognition.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）仅在输出层实施监督信息，隐层在没有明确监督的情况下通过反向传播来自输出层的预测误差来训练。我们提出了一个监督特征学习方法，标签一致性神经网络，在后期隐藏层实施直接监督。我们将隐藏层中的每个神经元与一个特定的类别标签相关联，并鼓励它激活来自同一类的输入信号。更具体地说，我们引入了一个标签一致性规则化，称为“判别表示错误”损失的后期隐藏层，并将其与分类错误损失相结合，以建立我们的总体目标函数。这种标签一致性约束缓解了梯度消失的常见问题，趋于更快的收敛;由于来自同一类别的输入信号将具有非常相似的表示，所以即使使用简单的$ k $ -NN分类器，也使得从后期隐层获得的特征足以区分分类。实验结果表明，我们的方法在行动和对象类别识别的几个公共基准上达到了最先进的表现。

##### URL
[https://arxiv.org/abs/1602.01168](https://arxiv.org/abs/1602.01168)

##### PDF
[https://arxiv.org/pdf/1602.01168](https://arxiv.org/pdf/1602.01168)

