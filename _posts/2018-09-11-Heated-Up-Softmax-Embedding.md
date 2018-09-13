---
layout: post
title: "Heated-Up Softmax Embedding"
date: 2018-09-11 20:56:02
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Xu Zhang, Felix Xinnan Yu, Svebor Karaman, Wei Zhang, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Metric learning aims at learning a distance which is consistent with the semantic meaning of the samples. The problem is generally solved by learning an embedding for each sample such that the embeddings of samples of the same category are compact while the embeddings of samples of different categories are spread-out in the feature space. We study the features extracted from the second last layer of a deep neural network based classifier trained with the cross entropy loss on top of the softmax layer. We show that training classifiers with different temperature values of softmax function leads to features with different levels of compactness. Leveraging these insights, we propose a "heating-up" strategy to train a classifier with increasing temperatures, leading the corresponding embeddings to achieve state-of-the-art performance on a variety of metric learning benchmarks.

##### Abstract (translated by Google)
度量学习旨在学习与样本的语义含义一致的距离。通常通过学习每个样本的嵌入来解决该问题，使得相同类别的样本的嵌入是紧凑的，而不同类别的样本的嵌入在特征空间中展开。我们研究了从基于深度神经网络的分类器的第二层提取的特征，该分类器在softmax层之上用交叉熵损失训练。我们表明，具有不同温度值softmax功能的训练分类器导致具有不同紧凑程度的特征。利用这些见解，我们提出了一种“加热”策略来训练分类器的温度升高，引导相应的嵌入在各种度量学习基准上实现最先进的性能。

##### URL
[http://arxiv.org/abs/1809.04157](http://arxiv.org/abs/1809.04157)

##### PDF
[http://arxiv.org/pdf/1809.04157](http://arxiv.org/pdf/1809.04157)

