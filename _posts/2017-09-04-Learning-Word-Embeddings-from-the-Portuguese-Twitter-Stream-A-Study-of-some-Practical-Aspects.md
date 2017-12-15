---
layout: post
title: "Learning Word Embeddings from the Portuguese Twitter Stream: A Study of some Practical Aspects"
date: 2017-09-04 13:30:23
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Pedro Saleiro, Luís Sarmento, Eduarda Mendes Rodrigues, Carlos Soares, Eugénio Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a preliminary study for producing and distributing a large-scale database of embeddings from the Portuguese Twitter stream. We start by experimenting with a relatively small sample and focusing on three challenges: volume of training data, vocabulary size and intrinsic evaluation metrics. Using a single GPU, we were able to scale up vocabulary size from 2048 words embedded and 500K training examples to 32768 words over 10M training examples while keeping a stable validation loss and approximately linear trend on training time per epoch. We also observed that using less than 50\% of the available training examples for each vocabulary size might result in overfitting. Results on intrinsic evaluation show promising performance for a vocabulary size of 32768 words. Nevertheless, intrinsic evaluation metrics suffer from over-sensitivity to their corresponding cosine similarity thresholds, indicating that a wider range of metrics need to be developed to track progress.

##### Abstract (translated by Google)
本文介绍了一个从葡萄牙Twitter流生成和发布大型嵌入数据库的初步研究。我们首先尝试一个相对较小的样本，重点关注三个挑战：训练数据量，词汇量和内在评估指标。使用单一GPU，我们可以将词汇大小从嵌入的2048个词汇和500K个训练样本扩展到超过10M个训练样本的32768个词汇，同时保持稳定的验证损失和每个时期的训练时间大致线性的趋势。我们还观察到，对每个词汇量使用少于50％的可用训练样例可能会导致过度拟合。内在评估的结果显示，词汇量为32768字的前景良好。尽管如此，内在评估度量标准对相应的余弦相似度阈值过度敏感，这表明需要开发更多的度量标准来跟踪进度。

##### URL
[https://arxiv.org/abs/1709.00947](https://arxiv.org/abs/1709.00947)

##### PDF
[https://arxiv.org/pdf/1709.00947](https://arxiv.org/pdf/1709.00947)

