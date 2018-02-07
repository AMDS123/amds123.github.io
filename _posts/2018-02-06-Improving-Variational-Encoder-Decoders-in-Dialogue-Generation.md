---
layout: post
title: "Improving Variational Encoder-Decoders in Dialogue Generation"
date: 2018-02-06 16:19:05
categories: arXiv_AI
tags: arXiv_AI Embedding RNN
author: Xiaoyu Shen, Hui Su, Shuzi Niu, Vera Demberg
mathjax: true
---

* content
{:toc}

##### Abstract
Variational encoder-decoders (VEDs) have shown promising results in dialogue generation. However, the latent variable distributions are usually approximated by a much simpler model than the powerful RNN structure used for encoding and decoding, yielding the KL-vanishing problem and inconsistent training objective. In this paper, we separate the training step into two phases: The first phase learns to autoencode discrete texts into continuous embeddings, from which the second phase learns to generalize latent representations by reconstructing the encoded embedding. In this case, latent variables are sampled by transforming Gaussian noise through multi-layer perceptrons and are trained with a separate VED model, which has the potential of realizing a much more flexible distribution. We compare our model with current popular models and the experiment demonstrates substantial improvement in both metric-based and human evaluations.

##### Abstract (translated by Google)
变化的编码器 - 解码器（VED）已经在对话生成中显示出有希望的结果。然而，潜在的变量分布通常比用于编码和解码的强大的RNN结构简单得多，产生KL消失问题和不一致的训练目标。在本文中，我们将训练步骤分为两个阶段：第一个阶段学习将离散文本自动编码为连续嵌入，第二阶段通过重构编码嵌入学习从而推广潜在表示。在这种情况下，通过多层感知器通过转换高斯噪声对潜变量进行采样，并且利用单独的VED模型进行训练，这具有实现更加灵活的分布的潜力。我们将我们的模型与当前流行的模型进行比较，实验显示基于度量和人为评估的实质性改进。

##### URL
[http://arxiv.org/abs/1802.02032](http://arxiv.org/abs/1802.02032)

##### PDF
[http://arxiv.org/pdf/1802.02032](http://arxiv.org/pdf/1802.02032)

