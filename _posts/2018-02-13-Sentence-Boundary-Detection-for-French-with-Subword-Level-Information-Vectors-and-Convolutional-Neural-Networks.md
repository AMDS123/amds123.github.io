---
layout: post
title: "Sentence Boundary Detection for French with Subword-Level Information Vectors and Convolutional Neural Networks"
date: 2018-02-13 11:04:07
categories: arXiv_CL
tags: arXiv_CL Embedding CNN Classification Detection
author: Carlos-Emiliano Gonz&#xe1;lez-Gallardo, Juan-Manuel Torres-Moreno
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we tackle the problem of sentence boundary detection applied to French as a binary classification task ("sentence boundary" or "not sentence boundary"). We combine convolutional neural networks with subword-level information vectors, which are word embedding representations learned from Wikipedia that take advantage of the words morphology; so each word is represented as a bag of their character n-grams. 
 We decide to use a big written dataset (French Gigaword) instead of standard size transcriptions to train and evaluate the proposed architectures with the intention of using the trained models in posterior real life ASR transcriptions. 
 Three different architectures are tested showing similar results; general accuracy for all models overpasses 0.96. All three models have good F1 scores reaching values over 0.97 regarding the "not sentence boundary" class. However, the "sentence boundary" class reflects lower scores decreasing the F1 metric to 0.778 for one of the models. 
 Using subword-level information vectors seem to be very effective leading to conclude that the morphology of words encoded in the embeddings representations behave like pixels in an image making feasible the use of convolutional neural network architectures.

##### Abstract (translated by Google)
在这项工作中，我们解决了应用于法语作为二元分类任务（“句子边界”或“非句子边界”）的句子边界检测问题。我们将卷积神经网络与子词级别的信息向量结合起来，这些向量是从维基百科学习到的利用单词形态学的词嵌入表示;所以每个单词都被表示为一包字符n-gram。
 我们决定使用一个大的书面数据集（法语Gigaword）而不是标准尺寸的转录来训练和评估所提出的体系结构，目的是在后现实生活的ASR转录中使用训练过的模型。
 测试了三种不同的架构，显示了类似的结果;所有型号的一般准确度超过0.96。所有三个模型都具有良好的F1分数，关于“非句子边界”类别，其值超过0.97。然而，“句子边界”类反映了其中一个模型的F1评分降低到0.778的较低分数。
 使用子字级信息向量似乎是非常有效的，从而得出结论：在嵌入表示中编码的单词的形态行为与图像中的像素类似，使得卷积神经网络体系结构的使用成为可能。

##### URL
[http://arxiv.org/abs/1802.04559](http://arxiv.org/abs/1802.04559)

##### PDF
[http://arxiv.org/pdf/1802.04559](http://arxiv.org/pdf/1802.04559)

