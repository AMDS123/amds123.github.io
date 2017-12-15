---
layout: post
title: "Unsupervised Visual Representation Learning by Context Prediction"
date: 2016-01-16 22:09:45
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning Prediction Detection
author: Carl Doersch, Abhinav Gupta, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
This work explores the use of spatial context as a source of free and plentiful supervisory signal for training a rich visual representation. Given only a large, unlabeled image collection, we extract random pairs of patches from each image and train a convolutional neural net to predict the position of the second patch relative to the first. We argue that doing well on this task requires the model to learn to recognize objects and their parts. We demonstrate that the feature representation learned using this within-image context indeed captures visual similarity across images. For example, this representation allows us to perform unsupervised visual discovery of objects like cats, people, and even birds from the Pascal VOC 2011 detection dataset. Furthermore, we show that the learned ConvNet can be used in the R-CNN framework and provides a significant boost over a randomly-initialized ConvNet, resulting in state-of-the-art performance among algorithms which use only Pascal-provided training set annotations.

##### Abstract (translated by Google)
这项工作探讨了空间情境的使用作为一个自由和丰富的监督信号来训练丰富的视觉表示的来源。只给出一个大的，未标记的图像集合，我们从每个图像中提取随机的补丁对，并训练一个卷积神经网络来预测第二个补丁相对于第一个补丁的位置。我们认为做好这个任务需要模型学习识别对象及其部分。我们证明，使用这种图像内上下文所学习的特征表示确实捕获了跨图像的视觉相似性。例如，这种表示使我们可以从Pascal VOC 2011检测数据集中进行无监督的视觉发现，如猫，人，甚至鸟类。此外，我们证明了学习到的ConvNet可以在R-CNN框架中使用，并且对随机初始化的ConvNet提供了显着的提升，从而在仅使用Pascal提供的训练集注释的算法中导致了最先进的性能。

##### URL
[https://arxiv.org/abs/1505.05192](https://arxiv.org/abs/1505.05192)

##### PDF
[https://arxiv.org/pdf/1505.05192](https://arxiv.org/pdf/1505.05192)

