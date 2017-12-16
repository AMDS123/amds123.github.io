---
layout: post
title: "Towards End-to-End Face Recognition through Alignment Learning"
date: 2017-01-25 06:10:41
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Recognition Face_Recognition
author: Yuanyi Zhong, Jiansheng Chen, Bo Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Plenty of effective methods have been proposed for face recognition during the past decade. Although these methods differ essentially in many aspects, a common practice of them is to specifically align the facial area based on the prior knowledge of human face structure before feature extraction. In most systems, the face alignment module is implemented independently. This has actually caused difficulties in the designing and training of end-to-end face recognition models. In this paper we study the possibility of alignment learning in end-to-end face recognition, in which neither prior knowledge on facial landmarks nor artificially defined geometric transformations are required. Specifically, spatial transformer layers are inserted in front of the feature extraction layers in a Convolutional Neural Network (CNN) for face recognition. Only human identity clues are used for driving the neural network to automatically learn the most suitable geometric transformation and the most appropriate facial area for the recognition task. To ensure reproducibility, our model is trained purely on the publicly available CASIA-WebFace dataset, and is tested on the Labeled Face in the Wild (LFW) dataset. We have achieved a verification accuracy of 99.08\% which is comparable to state-of-the-art single model based methods.

##### Abstract (translated by Google)
在过去的十年里，人们提出了许多有效的方法来进行人脸识别。虽然这些方法在很多方面都有本质的不同，但是通常的做法是在特征提取之前，根据人脸结构的先验知识来特别对齐面部区域。在大多数系统中，人脸对齐模块是独立实施的。这实际上在端到端人脸识别模型的设计和培训方面造成了困难。在本文中，我们研究端对端人脸识别中的对齐学习的可能性，其中既不需要关于面部标志的知识也不需要人工定义的几何变换。具体而言，将空间变换器层插入卷积神经网络（CNN）中的特征提取层的前面以进行人脸识别。只有人的身份线索被用来驱动神经网络自动学习最适合的几何变换和最适合的识别任务的面部区域。为了确保可重复性，我们的模型纯粹在公开可用的CASIA-WebFace数据集上进行训练，并在野外标记人脸（LFW）数据集上进行测试。我们已经达到99.08％的验证准确率，这与现有的基于单模型的方法相当。

##### URL
[https://arxiv.org/abs/1701.07174](https://arxiv.org/abs/1701.07174)

##### PDF
[https://arxiv.org/pdf/1701.07174](https://arxiv.org/pdf/1701.07174)

