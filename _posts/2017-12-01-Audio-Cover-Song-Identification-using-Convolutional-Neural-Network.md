---
layout: post
title: "Audio Cover Song Identification using Convolutional Neural Network"
date: 2017-12-01 02:45:46
categories: arXiv_SD
tags: arXiv_SD CNN Relation
author: Sungkyun Chang, Juheon Lee, Sang Keun Choe, Kyogu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new approach to cover song identification using a CNN (convolutional neural network). Most previous studies extract the feature vectors that characterize the cover song relation from a pair of songs and used it to compute the (dis)similarity between the two songs. Based on the observation that there is a meaningful pattern between cover songs and that this can be learned, we have reformulated the cover song identification problem in a machine learning framework. To do this, we first build the CNN using as an input a cross-similarity matrix generated from a pair of songs. We then construct the data set composed of cover song pairs and non-cover song pairs, which are used as positive and negative training samples, respectively. The trained CNN outputs the probability of being in the cover song relation given a cross-similarity matrix generated from any two pieces of music and identifies the cover song by ranking on the probability. Experimental results show that the proposed algorithm achieves performance better than or comparable to the state-of-the-art.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来覆盖使用CNN（卷积神经网络）的歌曲识别。大多数以前的研究从一对歌曲中提取表征封面歌曲关系的特征向量，并用它来计算两首歌曲之间的（非）相似性。基于观察到在覆盖歌曲之间存在一个有意义的模式并且可以学习，我们在机器学习框架中重新形成了覆盖歌曲识别问题。为此，我们首先使用一对歌曲生成的交叉相似矩阵作为输入建立CNN。然后，我们构造由封面歌曲对和非封面歌曲对组成的数据集，分别作为正面和负面的训练样本。被训练的CNN输出在给定由任何两个音乐产生的交叉相似性矩阵的情况下处于覆盖歌曲关系的概率，并且通过对概率进行排序来识别覆盖歌曲。实验结果表明，该算法实现的性能优于现有技术或与现有技术相媲美。

##### URL
[https://arxiv.org/abs/1712.00166](https://arxiv.org/abs/1712.00166)

##### PDF
[https://arxiv.org/pdf/1712.00166](https://arxiv.org/pdf/1712.00166)

