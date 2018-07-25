---
layout: post
title: "The Variational Homoencoder: Learning to learn high capacity generative models from few examples"
date: 2018-07-24 06:05:43
categories: arXiv_AI
tags: arXiv_AI Face Inference Classification
author: Luke B. Hewitt, Maxwell I. Nye, Andreea Gane, Tommi Jaakkola, Joshua B. Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchical Bayesian methods can unify many related tasks (e.g. k-shot classification, conditional and unconditional generation) as inference within a single generative model. However, when this generative model is expressed as a powerful neural network such as a PixelCNN, we show that existing learning techniques typically fail to effectively use latent variables. To address this, we develop a modification of the Variational Autoencoder in which encoded observations are decoded to new elements from the same class. This technique, which we call a Variational Homoencoder (VHE), produces a hierarchical latent variable model which better utilises latent variables. We use the VHE framework to learn a hierarchical PixelCNN on the Omniglot dataset, which outperforms all existing models on test set likelihood and achieves strong performance on one-shot generation and classification tasks. We additionally validate the VHE on natural images from the YouTube Faces database. Finally, we develop extensions of the model that apply to richer dataset structures such as factorial and hierarchical categories.

##### Abstract (translated by Google)
分层贝叶斯方法可以将许多相关任务（例如，k-shot分类，条件和无条件生成）统一为单个生成模型中的推断。然而，当这种生成模型被表达为强大的神经网络（如PixelCNN）时，我们表明现有的学习技术通常无法有效地使用潜在变量。为了解决这个问题，我们开发了变分自动编码器的修改，其中编码的观测值被解码为来自同一类的新元素。这种技术，我们称之为变分同源编码器（VHE），产生一种分层隐变量模型，可以更好地利用潜变量。我们使用VHE框架在Omniglot数据集上学习分层PixelCNN，它在测试集可能性方面优于所有现有模型，并在一次性生成和分类任务中实现强大的性能。我们还在YouTube Faces数据库中验证自然图像上的VHE。最后，我们开发了适用于更丰富的数据集结构（如阶乘和分层类别）的模型扩展。

##### URL
[https://arxiv.org/abs/1807.08919](https://arxiv.org/abs/1807.08919)

##### PDF
[https://arxiv.org/pdf/1807.08919](https://arxiv.org/pdf/1807.08919)

