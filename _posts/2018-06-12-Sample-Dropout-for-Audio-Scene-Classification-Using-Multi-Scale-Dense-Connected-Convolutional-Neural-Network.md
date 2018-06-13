---
layout: post
title: "Sample Dropout for Audio Scene Classification Using Multi-Scale Dense Connected Convolutional Neural Network"
date: 2018-06-12 09:59:11
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Classification
author: Dawei Feng, Kele Xu, Haibo Mi, Feifan Liao, Yan Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic scene classification is an intricate problem for a machine. As an emerging field of research, deep Convolutional Neural Networks (CNN) achieve convincing results. In this paper, we explore the use of multi-scale Dense connected convolutional neural network (DenseNet) for the classification task, with the goal to improve the classification performance as multi-scale features can be extracted from the time-frequency representation of the audio signal. On the other hand, most of previous CNN-based audio scene classification approaches aim to improve the classification accuracy, by employing different regularization techniques, such as the dropout of hidden units and data augmentation, to reduce overfitting. It is widely known that outliers in the training set have a high negative influence on the trained model, and culling the outliers may improve the classification performance, while it is often under-explored in previous studies. In this paper, inspired by the silence removal in the speech signal processing, a novel sample dropout approach is proposed, which aims to remove outliers in the training dataset. Using the DCASE 2017 audio scene classification datasets, the experimental results demonstrates the proposed multi-scale DenseNet providing a superior performance than the traditional single-scale DenseNet, while the sample dropout method can further improve the classification robustness of multi-scale DenseNet.

##### Abstract (translated by Google)
声场分类是机器的一个复杂问题。作为一个新兴的研究领域，深度卷积神经网络（CNN）取得了令人信服的结果。在本文中，我们探索使用多尺度稠密连接卷积神经网络（DenseNet）进行分类任务，目标是提高分类性能，因为可以从音频的时频表示中提取多尺度特征信号。另一方面，以往基于CNN的音频场景分类方法大部分旨在通过采用不同的正则化技术（如隐藏单元丢失和数据增强）来减少过度拟合，从而提高分类精度。众所周知，训练集中的异常值对训练模型具有很大的负面影响，挑选异常值可能会提高分类性能，但在以前的研究中往往没有得到充分研究。在本文中，受语音信号处理中沉默消除的启发，提出了一种新的样本丢失方法，旨在去除训练数据集中的异常值。使用DCASE 2017音频场景分类数据集，实验结果表明提出的多尺度DenseNet提供比传统单尺度DenseNet更优越的性能，而样本丢失方法可以进一步提高多尺度DenseNet的分类鲁棒性。

##### URL
[http://arxiv.org/abs/1806.04422](http://arxiv.org/abs/1806.04422)

##### PDF
[http://arxiv.org/pdf/1806.04422](http://arxiv.org/pdf/1806.04422)

