---
layout: post
title: "Semi-supervised Sequence Learning"
date: 2015-11-04 18:48:36
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification Language_Model
author: Andrew M. Dai, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
We present two approaches that use unlabeled data to improve sequence learning with recurrent networks. The first approach is to predict what comes next in a sequence, which is a conventional language model in natural language processing. The second approach is to use a sequence autoencoder, which reads the input sequence into a vector and predicts the input sequence again. These two algorithms can be used as a "pretraining" step for a later supervised sequence learning algorithm. In other words, the parameters obtained from the unsupervised step can be used as a starting point for other supervised training models. In our experiments, we find that long short term memory recurrent networks after being pretrained with the two approaches are more stable and generalize better. With pretraining, we are able to train long short term memory recurrent networks up to a few hundred timesteps, thereby achieving strong performance in many text classification tasks, such as IMDB, DBpedia and 20 Newsgroups.

##### Abstract (translated by Google)
我们提出了两种使用无标签数据来改进循环网络序列学习的方法。第一种方法是预测在自然语言处理中的传统语言模型序列中接下来会发生什么。第二种方法是使用序列自动编码器，将输入序列读入向量并再次预测输入序列。这两种算法可以用作稍后监督序列学习算法的“预训练”步骤。换句话说，从无监督步骤获得的参数可以用作其他监督训练模型的起点。在我们的实验中，我们发现用这两种方法预训练后的长时间短记忆回归网络更稳定，泛化能力更强。通过预训练，我们能够训练长达几百步的短期记忆循环网络，从而在许多文本分类任务（例如IMDB，DBpedia和20个新闻组）中实现了强大的性能。

##### URL
[https://arxiv.org/abs/1511.01432](https://arxiv.org/abs/1511.01432)

##### PDF
[https://arxiv.org/pdf/1511.01432](https://arxiv.org/pdf/1511.01432)

