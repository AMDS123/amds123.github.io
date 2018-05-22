---
layout: post
title: "Abstractive Text Classification Using Sequence-to-convolution Neural Networks"
date: 2018-05-20 09:34:20
categories: arXiv_CL
tags: arXiv_CL Text_Classification CNN Classification
author: Taehoon Kim, Jihoon Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new deep neural network model and its training scheme for text classification. Our model Sequence-to-convolution Neural Networks(Seq2CNN) consists of two blocks: Sequential Block that summarizes input texts and Convolution Block that receives summary of input and classifies it to a label. Seq2CNN is trained end-to-end to classify various-length texts without preprocessing inputs into fixed length. We also present Gradual Weight Shift(GWS) method thatstabilize training. GWS is applied to our model's loss function. We compared our model with word-based TextCNN trained with different data preprocessing methods. We obtained significant improvement in classification accuracy over word-based TextCNN without any ensemble or data augmentation. Code is available at this https URL

##### Abstract (translated by Google)
我们提出了一种新的深度神经网络模型及其文本分类的训练方案。我们的模型序列卷积神经网络（Seq2CNN）由两个模块组成：顺序模块，用于汇总输入文本;卷积模块，用于接收输入摘要并将其分类为标签。 Seq2CNN是端对端训练，可以对各种长度的文本进行分类，而无需将输入预处理为固定长度。我们还提出稳定训练的渐进式体重偏移（GWS）方法。 GWS适用于我们模型的损失函数。我们将我们的模型与使用不同数据预处理方法训练的基于单词的TextCNN进行了比较。与基于单词的TextCNN相比，我们在分类准确性方面取得了显着的改进，没有任何集成或数据增强。该代码可在此https URL中找到

##### URL
[https://arxiv.org/abs/1805.07745](https://arxiv.org/abs/1805.07745)

##### PDF
[https://arxiv.org/pdf/1805.07745](https://arxiv.org/pdf/1805.07745)

