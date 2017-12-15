---
layout: post
title: "Supervised and Semi-Supervised Text Categorization using LSTM for Region Embeddings"
date: 2016-05-26 15:26:34
categories: arXiv_SD
tags: arXiv_SD Embedding CNN RNN
author: Rie Johnson, Tong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
One-hot CNN (convolutional neural network) has been shown to be effective for text categorization (Johnson & Zhang, 2015). We view it as a special case of a general framework which jointly trains a linear model with a non-linear feature generator consisting of `text region embedding + pooling'. Under this framework, we explore a more sophisticated region embedding method using Long Short-Term Memory (LSTM). LSTM can embed text regions of variable (and possibly large) sizes, whereas the region size needs to be fixed in a CNN. We seek effective and efficient use of LSTM for this purpose in the supervised and semi-supervised settings. The best results were obtained by combining region embeddings in the form of LSTM and convolution layers trained on unlabeled data. The results indicate that on this task, embeddings of text regions, which can convey complex concepts, are more useful than embeddings of single words in isolation. We report performances exceeding the previous best results on four benchmark datasets.

##### Abstract (translated by Google)
单热CNN（卷积神经网络）已被证明是有效的文本分类（Johnson＆Zhang，2015）。我们将其视为一个通用框架的特例，它与一个由“文本区域嵌入+共享”组成的非线性特征生成器联合训练线性模型。在这个框架下，我们探索一个更复杂的使用长期短期记忆（LSTM）的区域嵌入方法。 LSTM可以嵌入可变（可能大）大小的文本区域，而区域大小需要在CNN中固定。为此，我们寻求在监督和半监督环境下有效和高效地使用LSTM。通过结合LSTM形式的区域嵌入和在未标记的数据上训练的卷积层获得最好的结果。结果表明，在这个任务中，能够传达复杂概念的文本区域的嵌入比单独嵌入单个单词更有用。我们在四个基准数据集上报告超过以前最佳结果的表现。

##### URL
[https://arxiv.org/abs/1602.02373](https://arxiv.org/abs/1602.02373)

##### PDF
[https://arxiv.org/pdf/1602.02373](https://arxiv.org/pdf/1602.02373)

