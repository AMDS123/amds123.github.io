---
layout: post
title: "Convolutional RNN: an Enhanced Model for Extracting Features from Sequential Data"
date: 2017-07-20 14:03:16
categories: arXiv_SD
tags: arXiv_SD CNN RNN Classification
author: Gil Keren, Björn Schuller
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional convolutional layers extract features from patches of data by applying a non-linearity on an affine function of the input. We propose a model that enhances this feature extraction process for the case of sequential data, by feeding patches of the data into a recurrent neural network and using the outputs or hidden states of the recurrent units to compute the extracted features. By doing so, we exploit the fact that a window containing a few frames of the sequential data is a sequence itself and this additional structure might encapsulate valuable information. In addition, we allow for more steps of computation in the feature extraction process, which is potentially beneficial as an affine function followed by a non-linearity can result in too simple features. Using our convolutional recurrent layers we obtain an improvement in performance in two audio classification tasks, compared to traditional convolutional layers. Tensorflow code for the convolutional recurrent layers is publicly available in this https URL

##### Abstract (translated by Google)
传统卷积层通过对输入的仿射函数应用非线性来从数据补丁中提取特征。我们提出了一个模型，通过将补丁数据馈送到递归神经网络并使用递归单元的输出或隐藏状态来计算提取的特征，来增强针对顺序数据的特征提取过程。通过这样做，我们利用了这样一个事实，即包含几帧连续数据的窗口本身就是一个序列，这个附加结构可能会封装有价值的信息。另外，我们允许在特征提取过程中进行更多的计算步骤，这是有益的，因为仿射函数后跟非线性会导致太简单的特征。使用我们的卷积递归层，与传统的卷积层相比，我们获得了两个音频分类任务的性能改进。卷积重复图层的Tensorflow代码在这个https URL中是公开的

##### URL
[https://arxiv.org/abs/1602.05875](https://arxiv.org/abs/1602.05875)

##### PDF
[https://arxiv.org/pdf/1602.05875](https://arxiv.org/pdf/1602.05875)

