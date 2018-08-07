---
layout: post
title: "Large Scale Language Modeling: Converging on 40GB of Text in Four Hours"
date: 2018-08-03 21:44:29
categories: arXiv_CL
tags: arXiv_CL Review Knowledge CNN RNN Deep_Learning Language_Model
author: Raul Puri, Robert Kirby, Nikolai Yakovenko, Bryan Catanzaro
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown how to train Convolutional Neural Networks (CNNs) rapidly on large image datasets, then transfer the knowledge gained from these models to a variety of tasks. Following [Radford 2017], in this work, we demonstrate similar scalability and transfer for Recurrent Neural Networks (RNNs) for Natural Language tasks. By utilizing mixed precision arithmetic and a 32k batch size distributed across 128 NVIDIA Tesla V100 GPUs, we are able to train a character-level 4096-dimension multiplicative LSTM (mLSTM) for unsupervised text reconstruction over 3 epochs of the 40 GB Amazon Reviews dataset in four hours. This runtime compares favorably with previous work taking one month to train the same size and configuration for one epoch over the same dataset. Converging large batch RNN models can be challenging. Recent work has suggested scaling the learning rate as a function of batch size, but we find that simply scaling the learning rate as a function of batch size leads either to significantly worse convergence or immediate divergence for this problem. We provide a learning rate schedule that allows our model to converge with a 32k batch size. Since our model converges over the Amazon Reviews dataset in hours, and our compute requirement of 128 Tesla V100 GPUs, while substantial, is commercially available, this work opens up large scale unsupervised NLP training to most commercial applications and deep learning researchers. A model can be trained over most public or private text datasets overnight.

##### Abstract (translated by Google)
最近的工作已经展示了如何在大型图像数据集上快速训练卷积神经网络（CNN），然后将从这些模型中获得的知识转移到各种任务中。在[Radford 2017]之后，在这项工作中，我们展示了针对自然语言任务的回归神经网络（RNN）的类似可扩展性和传输。通过利用混合精度算法和分布在128个NVIDIA Tesla V100 GPU上的32k批量大小，我们能够训练一个字符级4096维乘法LSTM（mLSTM），用于在40 GB亚马逊评估数据集的3个时期内进行无监督的文本重建。四个小时。此运行时与以前的工作相比，在一个月内为同一数据集上的一个纪元训练相同的大小和配置。聚合大批量RNN模型可能具有挑战性。最近的工作已经建议将学习速率作为批量大小的函数来缩放，但是我们发现简单地将学习速率作为批量大小的函数来缩放导致该问题的收敛明显更差或立即分歧。我们提供学习率计划，允许我们的模型以32k批量大小收敛。由于我们的模型在数小时内收敛于亚马逊评论数据集，而我们的计算需求为128特斯拉V100 GPU，虽然实质性，但已经商业化，这项工作为大多数商业应用和深度学习研究人员开辟了大规模的无监督NLP培训。可以在一夜之间对大多数公共或私人文本数据集进行训练。

##### URL
[http://arxiv.org/abs/1808.01371](http://arxiv.org/abs/1808.01371)

##### PDF
[http://arxiv.org/pdf/1808.01371](http://arxiv.org/pdf/1808.01371)

