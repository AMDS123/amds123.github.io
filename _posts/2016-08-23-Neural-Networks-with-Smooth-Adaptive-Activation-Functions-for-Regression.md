---
layout: post
title: "Neural Networks with Smooth Adaptive Activation Functions for Regression"
date: 2016-08-23 15:56:08
categories: arXiv_CV
tags: arXiv_CV Classification
author: Le Hou, Dimitris Samaras, Tahsin M. Kurc, Yi Gao, Joel H. Saltz
mathjax: true
---

* content
{:toc}

##### Abstract
In Neural Networks (NN), Adaptive Activation Functions (AAF) have parameters that control the shapes of activation functions. These parameters are trained along with other parameters in the NN. AAFs have improved performance of Neural Networks (NN) in multiple classification tasks. In this paper, we propose and apply AAFs on feedforward NNs for regression tasks. We argue that applying AAFs in the regression (second-to-last) layer of a NN can significantly decrease the bias of the regression NN. However, using existing AAFs may lead to overfitting. To address this problem, we propose a Smooth Adaptive Activation Function (SAAF) with piecewise polynomial form which can approximate any continuous function to arbitrary degree of error. NNs with SAAFs can avoid overfitting by simply regularizing the parameters. In particular, an NN with SAAFs is Lipschitz continuous given a bounded magnitude of the NN parameters. We prove an upper-bound for model complexity in terms of fat-shattering dimension for any Lipschitz continuous regression model. Thus, regularizing the parameters in NNs with SAAFs avoids overfitting. We empirically evaluated NNs with SAAFs and achieved state-of-the-art results on multiple regression datasets.

##### Abstract (translated by Google)
在神经网络（NN）中，自适应激活功能（AAF）具有控制激活函数形状的参数。这些参数与NN中的其他参数一起训练。 AAF在多个分类任务中提高了神经网络（NN）的性能。在本文中，我们提出并应用前馈神经网络的AAF进行回归任务。我们认为，在神经网络的回归（倒数第二）层中应用AAF可以显着降低回归神经网络的偏差。但是，使用现有的AAF可能会导致过度配合。为了解决这个问题，我们提出了一个平滑的自适应激活功能（SAAF）分段多项式的形式，可以逼近任何连续函数的任意程度的错误。具有SAAF的神经网络可以通过简单地调整参数来避免过拟合。特别地，具有SAAF的NN是Lipschitz连续的，给定NN参数的有界幅度。对于任何Lipschitz连续回归模型，我们都证明了模型复杂度的上限是破碎维数。因此，使用SAAF规范神经网络中的参数可避免过拟合。我们用SAAFs经验性地评估了神经网络，并在多元回归数据集上获得了最新的结果。

##### URL
[https://arxiv.org/abs/1608.06557](https://arxiv.org/abs/1608.06557)

##### PDF
[https://arxiv.org/pdf/1608.06557](https://arxiv.org/pdf/1608.06557)

