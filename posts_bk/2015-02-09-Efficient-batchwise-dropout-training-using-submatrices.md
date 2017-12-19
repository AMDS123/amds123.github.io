---
layout: post
title: "Efficient batchwise dropout training using submatrices"
date: 2015-02-09 13:29:48
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Ben Graham, Jeremy Reizenstein, Leigh Robinson
mathjax: true
---

* content
{:toc}

##### Abstract
Dropout is a popular technique for regularizing artificial neural networks. Dropout networks are generally trained by minibatch gradient descent with a dropout mask turning off some of the units---a different pattern of dropout is applied to every sample in the minibatch. We explore a very simple alternative to the dropout mask. Instead of masking dropped out units by setting them to zero, we perform matrix multiplication using a submatrix of the weight matrix---unneeded hidden units are never calculated. Performing dropout batchwise, so that one pattern of dropout is used for each sample in a minibatch, we can substantially reduce training times. Batchwise dropout can be used with fully-connected and convolutional neural networks.

##### Abstract (translated by Google)
辍学是调整人工神经网络的流行技术。辍学网络通常由小班梯度下降训练，使用一个辍学面具关闭一些单位---一个不同的辍学模式适用于小班的每个样本。我们探索一个非常简单的选择到辍学面具。我们不用通过设置零来屏蔽掉出的单位，而是使用权重矩阵的子矩阵进行矩阵乘法---不需要计算不需要的隐藏单位。以批处理的方式进行退出，以便在一个小批次中为每个样本使用一个退出模式，我们可以大大减少训练时间。分段丢失可以用于全连接和卷积神经网络。

##### URL
[https://arxiv.org/abs/1502.02478](https://arxiv.org/abs/1502.02478)

##### PDF
[https://arxiv.org/pdf/1502.02478](https://arxiv.org/pdf/1502.02478)

