---
layout: post
title: "A Neural Clickbait Detection Engine"
date: 2018-02-09 13:49:13
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN RNN Detection
author: Yash Kumar Lal, Siddhartha Gairola, Vaibhav Kumar, Dhruv Khattar
mathjax: true
---

* content
{:toc}

##### Abstract
In an age where people are becoming increasing likely to trust information found through online media, journalists have begun employing techniques to lure readers to articles by using catchy headlines, called clickbait. These headlines entice the user into clicking through the article whilst not providing information relevant to the headline itself. Previous methods of detecting clickbait have explored techniques heavily dependent on feature engineering, with little experimentation having been tried with neural network architectures. We introduce a novel model combining recurrent neural networks, attention layers and image embeddings. Our model uses a combination of distributed word embeddings derived from unannotated corpora, character level embeddings calculated through Convolutional Neural Networks. These representations are passed through a bidirectional LSTM with an attention layer. The image embeddings are also learnt from large data using CNNs. Experimental results show that our model achieves an F1 score of 65.37% beating the previous benchmark of 55.21%.

##### Abstract (translated by Google)
在一个人们越来越信任通过网络媒体发现的信息的时代，记者们开始运用技术来引诱读者使用引人注目的头条新闻，这些新闻被称为“点击诱饵”。这些标题吸引用户点击文章，而不提供与标题本身相关的信息。先前的检测clickbait的方法已经探索了严重依赖于特征工程的技术，而在神经网络架构中尝试了很少的实验。我们引入一个结合递归神经网络，注意层和图像嵌入的新模型。我们的模型使用从未注释的语料库导出的分布式词嵌入，通过卷积神经网络计算的字符级嵌入的组合。这些表示通过具有关注层的双向LSTM传递。图像嵌入也从使用CNN的大数据中学习。实验结果表明，我们的模型达到了65.37％的F1分数，超过了以前的55.21％的基准。

##### URL
[http://arxiv.org/abs/1710.01507](http://arxiv.org/abs/1710.01507)

##### PDF
[http://arxiv.org/pdf/1710.01507](http://arxiv.org/pdf/1710.01507)

