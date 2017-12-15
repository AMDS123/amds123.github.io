---
layout: post
title: "Deep learning for extracting protein-protein interactions from biomedical literature"
date: 2017-06-07 00:28:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding CNN Deep_Learning
author: Yifan Peng, Zhiyong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for protein-protein interaction (PPI) extraction are primarily feature-based or kernel-based by leveraging lexical and syntactic information. But how to incorporate such knowledge in the recent deep learning methods remains an open question. In this paper, we propose a multichannel dependency-based convolutional neural network model (McDepCNN). It applies one channel to the embedding vector of each word in the sentence, and another channel to the embedding vector of the head of the corresponding word. Therefore, the model can use richer information obtained from different channels. Experiments on two public benchmarking datasets, AIMed and BioInfer, demonstrate that McDepCNN compares favorably to the state-of-the-art rich-feature and single-kernel based methods. In addition, McDepCNN achieves 24.4% relative improvement in F1-score over the state-of-the-art methods on cross-corpus evaluation and 12% improvement in F1-score over kernel-based methods on "difficult" instances. These results suggest that McDepCNN generalizes more easily over different corpora, and is capable of capturing long distance features in the sentences.

##### Abstract (translated by Google)
用于蛋白质 - 蛋白质相互作用（PPI）提取的最先进的方法主要是基于特征的或基于内核的，通过利用词汇和句法信息。但是如何将这些知识融入到最近的深度学习方法中仍然是一个悬而未决的问题在本文中，我们提出了一个多通道依赖卷积神经网络模型（McDepCNN）。它将一个通道应用到句子中每个单词的嵌入向量，并将另一个通道应用到相应单词的头部的嵌入向量。因此，该模型可以使用从不同渠道获得的更丰富的信息。在两个公开的基准测试数据集AIMed和BioInfer上进行的实验表明，McDepCNN与最先进的基于丰富特征和基于单内核的方法相比，更有优势。此外，McDepCNN在交叉语料库评估方面比现有技术方法的F1分数提高了24.4％，在“困难”情况下，基于内核方法的F1分数提高了12％。这些结果表明，McDepCNN更容易推广到不同的语料库，并能够捕捉句子中的长距离特征。

##### URL
[https://arxiv.org/abs/1706.01556](https://arxiv.org/abs/1706.01556)

##### PDF
[https://arxiv.org/pdf/1706.01556](https://arxiv.org/pdf/1706.01556)

