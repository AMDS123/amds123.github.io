---
layout: post
title: "Learning Semantic Sentence Embeddings using Pair-wise Discriminator"
date: 2018-06-03 15:00:05
categories: arXiv_AI
tags: arXiv_AI Sentiment Embedding
author: Badri N. Patro (1), Vinod K. Kurmi (1), Sandeep Kumar (1), Vinay P. Namboodiri (1) ((1) Indian Institute of Technology, Kanpur)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for obtaining sentence-level embeddings. While the problem of securing word-level embeddings is very well studied, we propose a novel method for obtaining sentence-level embeddings. This is obtained by a simple method in the context of solving the paraphrase generation task. If we use a sequential encoder-decoder model for generating paraphrase, we would like the generated paraphrase to be semantically close to the original sentence. One way to ensure this is by adding constraints for true paraphrase embeddings to be close and unrelated paraphrase candidate sentence embeddings to be far. This is ensured by using a sequential pair-wise discriminator that shares weights with the encoder that is trained with a suitable loss function. Our loss function penalizes paraphrase sentence embedding distances from being too large. This loss is used in combination with a sequential encoder-decoder network. We also validated our method by evaluating the obtained embeddings for a sentiment analysis task. The proposed method results in semantic embeddings and outperforms the state-of-the-art on the paraphrase generation and sentiment analysis task on standard datasets. These results are also shown to be statistically significant.

##### Abstract (translated by Google)
在本文中，我们提出了一种获取句子级嵌入的方法。虽然确保字级嵌入的问题得到了很好的研究，但我们提出了一种获取句级嵌入的新方法。这是通过解决释义生成任务的上下文中的简单方法获得的。如果我们使用顺序编码器 - 解码器模型来生成释义，我们希望生成的释义在语义上接近原始语句。确保这一点的一种方式是通过将真正的释义嵌入的约束添加为接近且无关的释义候选语句嵌入为远。这是通过使用顺序的逐对鉴别器来确保的，该鉴别器与经过适当损失函数训练的编码器共享权重。我们的损失函数惩罚释义句嵌入距离过大。这种损失与一个顺序编码器 - 解码器网络结合使用。我们还通过评估获得的情感分析任务的嵌入验证了我们的方法。所提出的方法导致语义嵌入，并且在标准数据集上的释义生成和情感分析任务上优于现有技术。这些结果也显示出具有统计意义。

##### URL
[http://arxiv.org/abs/1806.00807](http://arxiv.org/abs/1806.00807)

##### PDF
[http://arxiv.org/pdf/1806.00807](http://arxiv.org/pdf/1806.00807)

