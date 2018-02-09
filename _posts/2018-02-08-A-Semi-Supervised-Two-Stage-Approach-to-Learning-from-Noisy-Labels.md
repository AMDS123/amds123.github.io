---
layout: post
title: "A Semi-Supervised Two-Stage Approach to Learning from Noisy Labels"
date: 2018-02-08 00:35:42
categories: arXiv_CV
tags: arXiv_CV
author: Yifan Ding, Liqiang Wang, Deliang Fan, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The recent success of deep neural networks is powered in part by large-scale well-labeled training data. However, it is a daunting task to laboriously annotate an ImageNet-like dateset. On the contrary, it is fairly convenient, fast, and cheap to collect training images from the Web along with their noisy labels. This signifies the need of alternative approaches to training deep neural networks using such noisy labels. Existing methods tackling this problem either try to identify and correct the wrong labels or reweigh the data terms in the loss function according to the inferred noisy rates. Both strategies inevitably incur errors for some of the data points. In this paper, we contend that it is actually better to ignore the labels of some of the data points than to keep them if the labels are incorrect, especially when the noisy rate is high. After all, the wrong labels could mislead a neural network to a bad local optimum. We suggest a two-stage framework for the learning from noisy labels. In the first stage, we identify a small portion of images from the noisy training set of which the labels are correct with a high probability. The noisy labels of the other images are ignored. In the second stage, we train a deep neural network in a semi-supervised manner. This framework effectively takes advantage of the whole training set and yet only a portion of its labels that are most likely correct. Experiments on three datasets verify the effectiveness of our approach especially when the noisy rate is high.

##### Abstract (translated by Google)
深度神经网络的最近成功部分是由大规模标记良好的训练数据所驱动的。然而，辛辛苦苦地对一个类似ImageNet的日期集进行注释是一项艰巨的任务。相反，从网络上收集训练图像及其嘈杂的标签是相当方便，快速和便宜的。这意味着需要使用这种噪声标签来训练深度神经网络的替代方法。解决这个问题的现有方法要么尝试识别和纠​​正错误的标签，要么根据推断的噪声比率重新计算丢失函数中的数据项。这两种策略都不可避免地导致一些数据点的错误。在本文中，我们认为，如果标签不正确，忽略某些数据点的标签比保留标签更好，特别是在噪声率高的情况下。毕竟，错误的标签可能会误导一个神经网络到一个糟糕的局部最优。我们建议从嘈杂的标签学习两阶段的框架。在第一阶段，我们从高噪音的训练集中识别出一小部分标签正确的图像。其他图像的嘈杂标签被忽略。在第二阶段，我们以半监督的方式训练深度神经网络。这个框架有效地利用了整个训练集，而且只有一部分标签很可能是正确的。三个数据集上的实验验证了我们的方法的有效性，特别是当噪声率高时。

##### URL
[http://arxiv.org/abs/1802.02679](http://arxiv.org/abs/1802.02679)

##### PDF
[http://arxiv.org/pdf/1802.02679](http://arxiv.org/pdf/1802.02679)

