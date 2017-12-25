---
layout: post
title: "Variational Attention for Sequence-to-Sequence Models"
date: 2017-12-21 20:47:27
categories: arXiv_CL
tags: arXiv_CL Attention
author: Hareesh Bahuleyan, Lili Mou, Olga Vechtomova, Pascal Poupart
mathjax: true
---

* content
{:toc}

##### Abstract
The variational encoder-decoder (VED) encodes source information as a set of random variables using a neural network, which in turn is decoded into target data using another neural network. In natural language processing, sequence-to-sequence (Seq2Seq) models typically serve as encoder-decoder networks. When combined with a traditional (deterministic) attention mechanism, the variational latent space may be bypassed by the attention model, making the generated sentences less diversified. In our paper, we propose a variational attention mechanism for VED, where the attention vector is modeled as normally distributed random variables. Experiments show that variational attention increases diversity while retaining high quality. We also show that the model is not sensitive to hyperparameters.

##### Abstract (translated by Google)
变分编码器 - 解码器（VED）使用神经网络将源信息编码为一组随机变量，然后使用另一个神经网络将其解码为目标数据。在自然语言处理中，序列到序列（Seq2Seq）模型通常用作编码器 - 解码器网络。当与传统（确定性）的注意机制相结合时，变分潜在空间可能被注意模型所忽略，使生成的句子变得更加多样化。在本文中，我们提出了一个VED的变分注意机制，其中注意向量被建模为正态分布的随机变量。实验表明，变化的关注增加了多样性，同时保持了高质量。我们还表明，模型对超参数不敏感。

##### URL
[https://arxiv.org/abs/1712.08207](https://arxiv.org/abs/1712.08207)

##### PDF
[https://arxiv.org/pdf/1712.08207](https://arxiv.org/pdf/1712.08207)

