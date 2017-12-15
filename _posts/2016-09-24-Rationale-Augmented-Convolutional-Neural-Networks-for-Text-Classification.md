---
layout: post
title: "Rationale-Augmented Convolutional Neural Networks for Text Classification"
date: 2016-09-24 16:35:57
categories: arXiv_CL
tags: arXiv_CL Text_Classification CNN Classification Prediction
author: Ye Zhang, Iain Marshall, Byron C. Wallace
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new Convolutional Neural Network (CNN) model for text classification that jointly exploits labels on documents and their component sentences. Specifically, we consider scenarios in which annotators explicitly mark sentences (or snippets) that support their overall document categorization, i.e., they provide rationales. Our model exploits such supervision via a hierarchical approach in which each document is represented by a linear combination of the vector representations of its component sentences. We propose a sentence-level convolutional model that estimates the probability that a given sentence is a rationale, and we then scale the contribution of each sentence to the aggregate document representation in proportion to these estimates. Experiments on five classification datasets that have document labels and associated rationales demonstrate that our approach consistently outperforms strong baselines. Moreover, our model naturally provides explanations for its predictions.

##### Abstract (translated by Google)
我们提出了一个新的文本分类的卷积神经网络（CNN）模型，共同利用文档及其组成句子上的标签。具体而言，我们考虑了注释者明确标记支持其整体文档分类的句子（或摘录）的情况，即它们提供了理由。我们的模型通过分层方法来实现这种监督，其中每个文档由其组成句子的向量表示的线性组合表示。我们提出了一个句子层次的卷积模型来估计一个给定的句子是一个基本原理的概率，然后我们按照这些估计比例来衡量每个句子对总体文件表示的贡献。对具有文档标签和相关理由的五个分类数据集的实验表明，我们的方法始终优于强基线。而且，我们的模型自然会为其预测提供解释。

##### URL
[https://arxiv.org/abs/1605.04469](https://arxiv.org/abs/1605.04469)

##### PDF
[https://arxiv.org/pdf/1605.04469](https://arxiv.org/pdf/1605.04469)

