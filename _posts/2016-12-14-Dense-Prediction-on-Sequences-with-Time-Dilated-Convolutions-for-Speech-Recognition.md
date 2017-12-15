---
layout: post
title: "Dense Prediction on Sequences with Time-Dilated Convolutions for Speech Recognition"
date: 2016-12-14 08:27:41
categories: arXiv_CL
tags: arXiv_CL Attention GAN Speech_Recognition CNN Classification Language_Model Prediction Recognition
author: Tom Sercu, Vaibhava Goel
mathjax: true
---

* content
{:toc}

##### Abstract
In computer vision pixelwise dense prediction is the task of predicting a label for each pixel in the image. Convolutional neural networks achieve good performance on this task, while being computationally efficient. In this paper we carry these ideas over to the problem of assigning a sequence of labels to a set of speech frames, a task commonly known as framewise classification. We show that dense prediction view of framewise classification offers several advantages and insights, including computational efficiency and the ability to apply batch normalization. When doing dense prediction we pay specific attention to strided pooling in time and introduce an asymmetric dilated convolution, called time-dilated convolution, that allows for efficient and elegant implementation of pooling in time. We show results using time-dilated convolutions in a very deep VGG-style CNN with batch normalization on the Hub5 Switchboard-2000 benchmark task. With a big n-gram language model, we achieve 7.7% WER which is the best single model single-pass performance reported so far.

##### Abstract (translated by Google)
在计算机视觉中，像素级密集预测是预测图像中每个像素的标签的任务。卷积神经网络在这个任务上实现了良好的性能，同时在计算上是高效的。在本文中，我们将这些想法带到将一系列标签分配给一组语音帧的问题上，这一任务通常称为帧分类。我们展示了框架分类的密集预测视图提供了几个优点和见解，包括计算效率和应用批量规范化的能力。在进行密集预测时，我们特别注意分步汇集，并引入一个称为时间扩张卷积的不对称扩张卷积，以便及时高效地实现汇集。我们使用HubG Switchboard-2000基准测试任务中批量规范化的非常深的VGG式CNN，使用时间扩展的卷积显示结果。使用大n元语言模型，我们实现了7.7％的WER，这是迄今为止报告的最好的单模型单通道性能。

##### URL
[https://arxiv.org/abs/1611.09288](https://arxiv.org/abs/1611.09288)

##### PDF
[https://arxiv.org/pdf/1611.09288](https://arxiv.org/pdf/1611.09288)

