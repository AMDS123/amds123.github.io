---
layout: post
title: "Learning Deep Networks from Noisy Labels with Dropout Regularization"
date: 2017-05-09 16:42:32
categories: arXiv_CV
tags: arXiv_CV Regularization Gradient_Descent
author: Ishan Jindal, Matthew Nokleby, Xuewen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Large datasets often have unreliable labels-such as those obtained from Amazon's Mechanical Turk or social media platforms-and classifiers trained on mislabeled datasets often exhibit poor performance. We present a simple, effective technique for accounting for label noise when training deep neural networks. We augment a standard deep network with a softmax layer that models the label noise statistics. Then, we train the deep network and noise model jointly via end-to-end stochastic gradient descent on the (perhaps mislabeled) dataset. The augmented model is overdetermined, so in order to encourage the learning of a non-trivial noise model, we apply dropout regularization to the weights of the noise model during training. Numerical experiments on noisy versions of the CIFAR-10 and MNIST datasets show that the proposed dropout technique outperforms state-of-the-art methods.

##### Abstract (translated by Google)
大型数据集通常具有不可靠的标签，例如从亚马逊的土耳其机器人或社交媒体平台获得的标签，而在错误标记的数据集上训练的分类器往往表现不佳。当训练深度神经网络时，我们提出了一种简单有效的标记噪声核算方法。我们用一个模拟标签噪声统计的softmax层来增强一个标准的深度网络。然后，我们通过（可能是错误标记的）数据集上的端到端随机梯度下降联合训练深度网络和噪声模型。为了鼓励非平凡噪声模型的学习，我们在训练过程中将噪声模型的权重应用到正则化中去。在噪声版本的CIFAR-10和MNIST数据集上的数值实验表明，所提出的丢失技术优于最先进的方法。

##### URL
[https://arxiv.org/abs/1705.03419](https://arxiv.org/abs/1705.03419)

##### PDF
[https://arxiv.org/pdf/1705.03419](https://arxiv.org/pdf/1705.03419)

