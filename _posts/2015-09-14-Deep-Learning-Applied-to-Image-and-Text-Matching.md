---
layout: post
title: "Deep Learning Applied to Image and Text Matching"
date: 2015-09-14 17:19:33
categories: arXiv_SD
tags: arXiv_SD Image_Retrieval Embedding CNN Deep_Learning
author: Afroze Ibrahim Baqapuri
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to describe images with natural language sentences is the hallmark for image and language understanding. Such a system has wide ranging applications such as annotating images and using natural sentences to search for images.In this project we focus on the task of bidirectional image retrieval: such asystem is capable of retrieving an image based on a sentence (image search) andretrieve sentence based on an image query (image annotation). We present asystem based on a global ranking objective function which uses a combinationof convolutional neural networks (CNN) and multi layer perceptrons (MLP).It takes a pair of image and sentence and processes them in different channels,finally embedding it into a common multimodal vector space. These embeddingsencode abstract semantic information about the two inputs and can be comparedusing traditional information retrieval approaches. For each such pair, the modelreturns a score which is interpretted as a similarity metric. If this score is high,the image and sentence are likely to convey similar meaning, and if the score is low then they are likely not to. The visual input is modeled via deep convolutional neural network. On theother hand we explore three models for the textual module. The first one isbag of words with an MLP. The second one uses n-grams (bigram, trigrams,and a combination of trigram & skip-grams) with an MLP. The third is morespecialized deep network specific for modeling variable length sequences (SSE).We report comparable performance to recent work in the field, even though ouroverall model is simpler. We also show that the training time choice of how wecan generate our negative samples has a significant impact on performance, and can be used to specialize the bi-directional system in one particular task.

##### Abstract (translated by Google)
用自然语言描述图像的能力是形象和语言理解的标志。这种系统具有广泛的应用，如注释图像和使用自然语句来搜索图像。本项目主要研究双向图像检索任务，如系统能够基于句子（图像搜索）检索图像并检索基于图像查询的句子（图像注释）。基于全局排序的目标函数，采用卷积神经网络（CNN）和多层感知器（MLP）相结合的方法，采用一对图像和句子进行处理，最终将其嵌入到一个共同的多模态矢量空间。这些嵌入的关于两个输入的抽象语义信息被嵌入，并且可以用传统的信息检索方法进行比较。对于每一对这样的模型，模型都会得到一个被解释为相似性度量的分数。如果这个分数很高，图像和句子可能会传达类似的意思，如果分数低，那么他们很可能不会。视觉输入通过深度卷积神经网络建模。另一方面，我们探索文本模块的三个模型。第一个是MLP文字袋。第二个使用n-gram（bigram，trigrams，以及trigram和skip-grams的组合）和MLP。第三种是针对变长序列（SSE）建模的更为专门化的深层网络。即使整体模型比较简单，我们也报告了与该领域近期的工作相当的性能。我们还表明，训练时间选择怎样产生负样本对性能有显着的影响，可以用来在一个特定的任务中专门化双向系统。

##### URL
[https://arxiv.org/abs/1601.03478](https://arxiv.org/abs/1601.03478)

##### PDF
[https://arxiv.org/pdf/1601.03478](https://arxiv.org/pdf/1601.03478)

