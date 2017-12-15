---
layout: post
title: "Sentiment Classification with Word Attention based on Weakly Supervised Learning with a Convolutional Neural Network"
date: 2017-09-29 01:56:16
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Attention Weakly_Supervised Sentiment_Classification CNN Classification
author: Gichang Lee, Jaeyun Jeong, Seungwan Seo, CzangYeob Kim, Pilsung Kang
mathjax: true
---

* content
{:toc}

##### Abstract
In order to maximize the applicability of sentiment analysis results, it is necessary to not only classify the overall sentiment (positive/negative) of a given document but also to identify the main words that contribute to the classification. However, most datasets for sentiment analysis only have the sentiment label for each document or sentence. In other words, there is no information about which words play an important role in sentiment classification. In this paper, we propose a method for identifying key words discriminating positive and negative sentences by using a weakly supervised learning method based on a convolutional neural network (CNN). In our model, each word is represented as a continuous-valued vector and each sentence is represented as a matrix whose rows correspond to the word vector used in the sentence. Then, the CNN model is trained using these sentence matrices as inputs and the sentiment labels as the output. Once the CNN model is trained, we implement the word attention mechanism that identifies high-contributing words to classification results with a class activation map, using the weights from the fully connected layer at the end of the learned CNN model. In order to verify the proposed methodology, we evaluated the classification accuracy and inclusion rate of polarity words using two movie review datasets. Experimental result show that the proposed model can not only correctly classify the sentence polarity but also successfully identify the corresponding words with high polarity scores.

##### Abstract (translated by Google)
为了最大化情感分析结果的适用性，不仅要对给定文档的总体情绪（正面/负面）进行分类，还要确定对分类有贡献的主要词汇。然而，大多数情感分析数据集只有每个文档或句子的情感标签。换句话说，没有关于哪些词在情感分类中起重要作用的信息。本文提出了一种基于卷积神经网络（CNN）的弱监督学习方法来识别正负句的关键词识别方法。在我们的模型中，每个单词表示为一个连续值矢量，每个句子表示为一个矩阵，其行与句子中使用的单词矢量相对应。然后，使用这些句子矩阵作为输入并将情感标签作为输出来训练CNN模型。一旦CNN模型被训练，我们使用学习CNN模型结束时完全连接层的权重，实现单词注意机制，该机制使用类激活图来识别分类结果的高贡献词。为了验证所提出的方法，我们使用两个电影评论数据集来评估极性词的分类准确性和包含率。实验结果表明，该模型不仅可以正确分类句子的极性，而且能够成功识别具有高极性分数的相应单词。

##### URL
[https://arxiv.org/abs/1709.09885](https://arxiv.org/abs/1709.09885)

##### PDF
[https://arxiv.org/pdf/1709.09885](https://arxiv.org/pdf/1709.09885)

