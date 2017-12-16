---
layout: post
title: "Segmentation-Aware Convolutional Networks Using Local Attention Masks"
date: 2017-08-15 17:55:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Embedding CNN Semantic_Segmentation Classification Prediction
author: Adam W. Harley, Konstantinos G. Derpanis, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approach to integrate segmentation information within a convolutional neural network (CNN). This counter-acts the tendency of CNNs to smooth information across regions and increases their spatial precision. To obtain segmentation information, we set up a CNN to provide an embedding space where region co-membership can be estimated based on Euclidean distance. We use these embeddings to compute a local attention mask relative to every neuron position. We incorporate such masks in CNNs and replace the convolution operation with a "segmentation-aware" variant that allows a neuron to selectively attend to inputs coming from its own region. We call the resulting network a segmentation-aware CNN because it adapts its filters at each image point according to local segmentation cues. We demonstrate the merit of our method on two widely different dense prediction tasks, that involve classification (semantic segmentation) and regression (optical flow). Our results show that in semantic segmentation we can match the performance of DenseCRFs while being faster and simpler, and in optical flow we obtain clearly sharper responses than networks that do not use local attention masks. In both cases, segmentation-aware convolution yields systematic improvements over strong baselines. Source code for this work is available online at this http URL

##### Abstract (translated by Google)
我们介绍一种在卷积神经网络（CNN）中整合分割信息的方法。这反映了有线电视新闻网络平滑跨地区信息的趋势，并增加其空间精度。为了获得分割信息，我们建立了一个CNN来提供一个基于欧氏距离估计区域共同成员的嵌入空间。我们使用这些嵌入来计算相对于每个神经元位置的本地注意掩码。我们将这些掩码纳入CNN中，并用“分段感知”变体代替卷积操作，允许神经元选择性地关注来自其自己区域的输入。我们将所得到的网络称为分割感知CNN，因为它根据本地分割线索在每个图像点调整其滤波器。我们证明了我们的方法在两个广泛不同的密集预测任务，包括分类（语义分割）和回归（光流）的优点。我们的结果表明，在语义分割中，我们可以在更快，更简单的情况下匹配DenseCRFs的性能，并且在光流中，我们比没有使用本地注意力掩码的网络获得更清晰的响应。在这两种情况下，分割感知卷积都可以在强基线上进行系统改进。这个工作的源代码可以在这个http URL上在线获得

##### URL
[https://arxiv.org/abs/1708.04607](https://arxiv.org/abs/1708.04607)

##### PDF
[https://arxiv.org/pdf/1708.04607](https://arxiv.org/pdf/1708.04607)

