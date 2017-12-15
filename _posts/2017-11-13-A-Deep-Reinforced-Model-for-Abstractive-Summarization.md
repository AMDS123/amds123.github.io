---
layout: post
title: "A Deep Reinforced Model for Abstractive Summarization"
date: 2017-11-13 20:11:26
categories: arXiv_CL
tags: arXiv_CL Attention Summarization Reinforcement_Learning RNN Prediction
author: Romain Paulus, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Attentional, RNN-based encoder-decoder models for abstractive summarization have achieved good performance on short input and output sequences. For longer documents and summaries however these models often include repetitive and incoherent phrases. We introduce a neural network model with a novel intra-attention that attends over the input and continuously generated output separately, and a new training method that combines standard supervised word prediction and reinforcement learning (RL). Models trained only with supervised learning often exhibit "exposure bias" - they assume ground truth is provided at each step during training. However, when standard word prediction is combined with the global sequence prediction training of RL the resulting summaries become more readable. We evaluate this model on the CNN/Daily Mail and New York Times datasets. Our model obtains a 41.16 ROUGE-1 score on the CNN/Daily Mail dataset, an improvement over previous state-of-the-art models. Human evaluation also shows that our model produces higher quality summaries.

##### Abstract (translated by Google)
注意，基于RNN的抽象汇总编码器 - 解码器模型在短的输入和输出序列上取得了良好的性能。对于较长的文档和摘要，这些模型通常包含重复和不连贯的短语。我们引入了一种新的内部注意力的神经网络模型，分别注意输入和连续产生的输出，以及结合标准监督词预测和强化学习（RL）的新的训练方法。仅受监督学习训练的模型往往表现出“暴露偏倚” - 他们假设在训练期间的每一步都提供了基本事实。然而，当标准词预测与RL的全局序列预测训练相结合时，所得总结变得更可读。我们在CNN /每日邮报和纽约时报数据集上评估这个模型。我们的模型在CNN / Daily Mail数据集上获得了41.16的ROUGE-1分数，这是对先前模型的改进。人类评估也显示我们的模型产生更高质量的摘要。

##### URL
[https://arxiv.org/abs/1705.04304](https://arxiv.org/abs/1705.04304)

##### PDF
[https://arxiv.org/pdf/1705.04304](https://arxiv.org/pdf/1705.04304)

