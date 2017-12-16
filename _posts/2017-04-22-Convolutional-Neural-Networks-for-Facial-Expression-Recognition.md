---
layout: post
title: "Convolutional Neural Networks for Facial Expression Recognition"
date: 2017-04-22 06:27:56
categories: arXiv_CV
tags: arXiv_CV Regularization Face CNN Recognition
author: Shima Alizadeh, Azar Fazel
mathjax: true
---

* content
{:toc}

##### Abstract
We have developed convolutional neural networks (CNN) for a facial expression recognition task. The goal is to classify each facial image into one of the seven facial emotion categories considered in this study. We trained CNN models with different depth using gray-scale images. We developed our models in Torch and exploited Graphics Processing Unit (GPU) computation in order to expedite the training process. In addition to the networks performing based on raw pixel data, we employed a hybrid feature strategy by which we trained a novel CNN model with the combination of raw pixel data and Histogram of Oriented Gradients (HOG) features. To reduce the overfitting of the models, we utilized different techniques including dropout and batch normalization in addition to L2 regularization. We applied cross validation to determine the optimal hyper-parameters and evaluated the performance of the developed models by looking at their training histories. We also present the visualization of different layers of a network to show what features of a face can be learned by CNN models.

##### Abstract (translated by Google)
我们已经开发了用于面部表情识别任务的卷积神经网络（CNN）。目标是将每个面部图像分类为本研究中考虑的七种面部情绪类别之一。我们使用灰度图像对不同深度的CNN模型进行了训练。我们在火炬中开发了我们的模型，并利用图形处理单元（GPU）计算来加速训练过程。除了基于原始像素数据执行的网络之外，我们采用了混合特征策略，通过该策略，我们训练了一个新的CNN模型，结合了原始像素数据和面向梯度直方图（Histogram of Oriented Gradients，HOG）特征。为了减少模型的过拟合，除了L2正则化之外，我们还利用了包括丢失和批量归一化在内的不同技术。我们应用交叉验证来确定最佳超参数，并通过查看他们的训练历史来评估所开发的模型的性能。我们还展示了网络的不同层面的可视化，以显示CNN模型可以学习脸部的特征。

##### URL
[https://arxiv.org/abs/1704.06756](https://arxiv.org/abs/1704.06756)

##### PDF
[https://arxiv.org/pdf/1704.06756](https://arxiv.org/pdf/1704.06756)

