---
layout: post
title: "Identifying Clickbait: A Multi-Strategy Approach Using Neural Networks"
date: 2018-08-01 17:17:16
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN RNN Detection
author: Vaibhav Kumar, Dhruv Khattar, Siddhartha Gairola, Yash Kumar Lal, Vasudeva Varma
mathjax: true
---

* content
{:toc}

##### Abstract
Online media outlets, in a bid to expand their reach and subsequently increase revenue through ad monetisation, have begun adopting clickbait techniques to lure readers to click on articles. The article fails to fulfill the promise made by the headline. Traditional methods for clickbait detection have relied heavily on feature engineering which, in turn, is dependent on the dataset it is built for. The application of neural networks for this task has only been explored partially. We propose a novel approach considering all information found in a social media post. We train a bidirectional LSTM with an attention mechanism to learn the extent to which a word contributes to the post's clickbait score in a differential manner. We also employ a Siamese net to capture the similarity between source and target information. Information gleaned from images has not been considered in previous approaches. We learn image embeddings from large amounts of data using Convolutional Neural Networks to add another layer of complexity to our model. Finally, we concatenate the outputs from the three separate components, serving it as input to a fully connected layer. We conduct experiments over a test corpus of 19538 social media posts, attaining an F1 score of 65.37% on the dataset bettering the previous state-of-the-art, as well as other proposed approaches, feature engineering or otherwise.

##### Abstract (translated by Google)
在线媒体机构为了扩大覆盖范围并随后通过广告货币化增加收入，已经开始采用点击技术来吸引读者点击文章。该文不符合标题所作的承诺。用于clickbait检测的传统方法在很大程度上依赖于特征工程，而特征工程又依赖于它所构建的数据集。神经网络在这项任务中的应用仅得到了部分探索。我们提出了一种考虑社交媒体帖子中所有信息的新方法。我们训练具有注意机制的双向LSTM，以便以不同的方式了解单词对帖子的clickbait分数的贡献程度。我们还使用Siamese网来捕获源和目标信息之间的相似性。在以前的方法中没有考虑从图像中收集的信息。我们使用卷积神经网络从大量数据中学习图像嵌入，为我们的模型增加了另一层复杂性。最后，我们连接三个独立组件的输出，将其作为完全连接层的输入。我们对19538个社交媒体帖子的测试语料库进行了实验，在数据集上获得了65.37％的F1评分，从而改进了先前的最新技术水平，以及其他提议的方法，特征工程或其他方法。

##### URL
[http://arxiv.org/abs/1710.01507](http://arxiv.org/abs/1710.01507)

##### PDF
[http://arxiv.org/pdf/1710.01507](http://arxiv.org/pdf/1710.01507)

