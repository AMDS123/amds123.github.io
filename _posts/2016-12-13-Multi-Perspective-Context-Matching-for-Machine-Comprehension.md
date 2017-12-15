---
layout: post
title: "Multi-Perspective Context Matching for Machine Comprehension"
date: 2016-12-13 14:49:47
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Deep_Learning
author: Zhiguo Wang, Haitao Mi, Wael Hamza, Radu Florian
mathjax: true
---

* content
{:toc}

##### Abstract
Previous machine comprehension (MC) datasets are either too small to train end-to-end deep learning models, or not difficult enough to evaluate the ability of current MC techniques. The newly released SQuAD dataset alleviates these limitations, and gives us a chance to develop more realistic MC models. Based on this dataset, we propose a Multi-Perspective Context Matching (MPCM) model, which is an end-to-end system that directly predicts the answer beginning and ending points in a passage. Our model first adjusts each word-embedding vector in the passage by multiplying a relevancy weight computed against the question. Then, we encode the question and weighted passage by using bi-directional LSTMs. For each point in the passage, our model matches the context of this point against the encoded question from multiple perspectives and produces a matching vector. Given those matched vectors, we employ another bi-directional LSTM to aggregate all the information and predict the beginning and ending points. Experimental result on the test set of SQuAD shows that our model achieves a competitive result on the leaderboard.

##### Abstract (translated by Google)
先前的机器理解（MC）数据集要么太小而不能训练端到端的深度学习模型，要么难以评估当前MC技术的能力。新发布的SQuAD数据集缓解了这些限制，并为我们提供了一个开发更现实的MC模型的机会。基于这个数据集，我们提出了一个多视角上下文匹配（Multi-Perspective Context Matching，MPCM）模型，它是一个端到端的系统，直接预测一个段落中的答案的开始和结束点。我们的模型首先通过乘以针对问题计算的相关权重来调整通道中的每个词嵌入向量。然后，我们使用双向LSTM对问题进行编码并加权传递。对于文章中的每一点，我们的模型都将这个点的上下文与来自多个视角的编码问题进行匹配，并产生一个匹配矢量。给定匹配的向量，我们使用另一个双向LSTM来聚合所有信息并预测起点和终点。在SQUAD测试集上的实验结果表明，我们的模型在排行榜上取得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1612.04211](https://arxiv.org/abs/1612.04211)

##### PDF
[https://arxiv.org/pdf/1612.04211](https://arxiv.org/pdf/1612.04211)

