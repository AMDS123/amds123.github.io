---
layout: post
title: "Learning Universal Sentence Representations with Mean-Max Attention Autoencoder"
date: 2018-09-18 08:34:12
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Minghua Zhang, Yunfang Wu, Weikang Li, Wei Li
mathjax: true
---

* content
{:toc}

##### Abstract
In order to learn universal sentence representations, previous methods focus on complex recurrent neural networks or supervised learning. In this paper, we propose a mean-max attention autoencoder (mean-max AAE) within the encoder-decoder framework. Our autoencoder rely entirely on the MultiHead self-attention mechanism to reconstruct the input sequence. In the encoding we propose a mean-max strategy that applies both mean and max pooling operations over the hidden vectors to capture diverse information of the input. To enable the information to steer the reconstruction process dynamically, the decoder performs attention over the mean-max representation. By training our model on a large collection of unlabelled data, we obtain high-quality representations of sentences. Experimental results on a broad range of 10 transfer tasks demonstrate that our model outperforms the state-of-the-art unsupervised single methods, including the classical skip-thoughts and the advanced skip-thoughts+LN model. Furthermore, compared with the traditional recurrent neural network, our mean-max AAE greatly reduce the training time.

##### Abstract (translated by Google)
为了学习通用句子表示，以前的方法关注于复杂的递归神经网络或监督学习。在本文中，我们提出了编码器 - 解码器框架内的均值 - 最大关注自动编码器（mean-max AAE）。我们的自动编码器完全依赖于MultiHead自我关注机制来重建输入序列。在编码中，我们提出了一种均值 - 最大策略，该策略在隐藏向量上应用均值和最大池操作，以捕获输入的各种信息。为了使信息能够动态地引导重建过程，解码器对均值 - 最大表示进行关注。通过在大量未标记数据上训练我们的模型，我们获得了高质量的句子表示。广泛的10个传递任务的实验结果表明，我们的模型优于最先进的无监督单一方法，包括经典的跳过思想和高级跳过思想+ LN模型。此外，与传统的递归神经网络相比，我们的平均最大AAE大大缩短了训练时间。

##### URL
[http://arxiv.org/abs/1809.06590](http://arxiv.org/abs/1809.06590)

##### PDF
[http://arxiv.org/pdf/1809.06590](http://arxiv.org/pdf/1809.06590)

