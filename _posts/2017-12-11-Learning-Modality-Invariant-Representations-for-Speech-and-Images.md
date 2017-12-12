---
layout: post
title: "Learning Modality-Invariant Representations for Speech and Images"
date: 2017-12-11 17:18:34
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding Transfer_Learning
author: Kenneth Leidal, David Harwath, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore the unsupervised learning of a semantic embedding space for co-occurring sensory inputs. Specifically, we focus on the task of learning a semantic vector space for both spoken and handwritten digits using the TIDIGITs and MNIST datasets. Current techniques encode image and audio/textual inputs directly to semantic embeddings. In contrast, our technique maps an input to the mean and log variance vectors of a diagonal Gaussian from which sample semantic embeddings are drawn. In addition to encouraging semantic similarity between co-occurring inputs,our loss function includes a regularization term borrowed from variational autoencoders (VAEs) which drives the posterior distributions over embeddings to be unit Gaussian. We can use this regularization term to filter out modality information while preserving semantic information. We speculate this technique may be more broadly applicable to other areas of cross-modality/domain information retrieval and transfer learning.

##### Abstract (translated by Google)
在这篇文章中，我们探索了一个语义嵌入空间的无监督学习共现感官输入。具体来说，我们着重于使用TIDIGIT和MNIST数据集来学习语音和手写数字的语义向量空间。当前的技术将图像和音频/文本输入直接编码到语义嵌入。相比之下，我们的技术将输入映射到对角高斯的均值和对数方差向量，从中抽取语义嵌入。除了鼓励同现输入之间的语义相似之外，我们的损失函数还包括借助于变分自动编码器（VAEs）的正则化项，其将嵌入后验分布驱动为单位高斯。我们可以使用这个正则化术语来滤除模态信息，同时保留语义信息。我们推测这种技术可能更广泛地适用于跨模态/领域信息检索和转移学习的其他领域。

##### URL
[http://arxiv.org/abs/1712.03897](http://arxiv.org/abs/1712.03897)

##### PDF
[http://arxiv.org/pdf/1712.03897](http://arxiv.org/pdf/1712.03897)

