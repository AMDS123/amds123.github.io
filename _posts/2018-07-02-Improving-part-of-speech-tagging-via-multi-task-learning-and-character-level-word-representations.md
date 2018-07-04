---
layout: post
title: "Improving part-of-speech tagging via multi-task learning and character-level word representations"
date: 2018-07-02 13:04:52
categories: arXiv_CL
tags: arXiv_CL RNN Prediction
author: Daniil Anastasyev, Ilya Gusev, Eugene Indenbom
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore the ways to improve POS-tagging using various types of auxiliary losses and different word representations. As a baseline, we utilized a BiLSTM tagger, which is able to achieve state-of-the-art results on the sequence labelling tasks. We developed a new method for character-level word representation using feedforward neural network. Such representation gave us better results in terms of speed and performance of the model. We also applied a novel technique of pretraining such word representations with existing word vectors. Finally, we designed a new variant of auxiliary loss for sequence labelling tasks: an additional prediction of the neighbour labels. Such loss forces a model to learn the dependencies in-side a sequence of labels and accelerates the process of training. We test these methods on English and Russian languages.

##### Abstract (translated by Google)
在本文中，我们探讨了使用各种类型的辅助损失和不同的单词表示来改进POS标记的方法。作为基线，我们使用了BiLSTM标记器，它能够在序列标记任务中获得最先进的结果。我们开发了一种使用前馈神经网络进行字符级单词表示的新方法。这种表示在模型的速度和性能方面给了我们更好的结果。我们还应用了一种利用现有单词向量预训练这种单词表示的新技术。最后，我们为序列标记任务设计了一种新的辅助损失变体：对邻居标签的附加预测。这种损失迫使模型在标签序列中学习依赖性并加速训练过程。我们用英语和俄语测试这些方法。

##### URL
[https://arxiv.org/abs/1807.00818](https://arxiv.org/abs/1807.00818)

##### PDF
[https://arxiv.org/pdf/1807.00818](https://arxiv.org/pdf/1807.00818)

