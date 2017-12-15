---
layout: post
title: "End-to-End Training Approaches for Discriminative Segmental Models"
date: 2016-10-21 08:45:35
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Hao Tang, Weiran Wang, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on discriminative segmental models has shown that they can achieve competitive speech recognition performance, using features based on deep neural frame classifiers. However, segmental models can be more challenging to train than standard frame-based approaches. While some segmental models have been successfully trained end to end, there is a lack of understanding of their training under different settings and with different losses. We investigate a model class based on recent successful approaches, consisting of a linear model that combines segmental features based on an LSTM frame classifier. Similarly to hybrid HMM-neural network models, segmental models of this class can be trained in two stages (frame classifier training followed by linear segmental model weight training), end to end (joint training of both frame classifier and linear weights), or with end-to-end fine-tuning after two-stage training. We study segmental models trained end to end with hinge loss, log loss, latent hinge loss, and marginal log loss. We consider several losses for the case where training alignments are available as well as where they are not. We find that in general, marginal log loss provides the most consistent strong performance without requiring ground-truth alignments. We also find that training with dropout is very important in obtaining good performance with end-to-end training. Finally, the best results are typically obtained by a combination of two-stage training and fine-tuning.

##### Abstract (translated by Google)
最近有关判别分段模型的研究表明，它们可以使用基于深度神经帧分类器的特征来实现竞争性语音识别性能。然而，与标准的基于框架的方法相比，分段模型可能更难以训练。虽然一些分部模型已经成功地进行了端到端的训练，但是在不同的环境和不同的损失下，他们对训练缺乏了解。我们调查一个基于最近成功的方法的模型类，包括一个线性模型，它结合了基于LSTM帧分类器的分段特征。类似于混合HMM-神经网络模型，可以分两个阶段（帧分类器训练，然后是线性分段模型权重训练），端到端（帧分类器和线性权重的联合训练），或者与两阶段训练后进行端到端的微调。我们研究了端铰链损失，对数损失，潜在铰链损失和边际对数损失的分段模型。我们认为在有可用的培训路线以及不在的地方，会有几处损失。我们发现，一般来说，边际对数损失提供了最一致的强大性能，而不需要地面真实对准。我们还发现，辍学培训对于通过端到端的培训获得良好的业绩非常重要。最后，最好的结果通常是通过两阶段训练和微调的组合来获得的。

##### URL
[https://arxiv.org/abs/1610.06700](https://arxiv.org/abs/1610.06700)

##### PDF
[https://arxiv.org/pdf/1610.06700](https://arxiv.org/pdf/1610.06700)

