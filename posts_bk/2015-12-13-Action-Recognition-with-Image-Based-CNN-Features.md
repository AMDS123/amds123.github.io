---
layout: post
title: "Action Recognition with Image Based CNN Features"
date: 2015-12-13 00:17:24
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Recognition
author: Mahdyar Ravanbakhsh, Hossein Mousavi, Mohammad Rastegari, Vittorio Murino, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Most of human actions consist of complex temporal compositions of more simple actions. Action recognition tasks usually relies on complex handcrafted structures as features to represent the human action model. Convolutional Neural Nets (CNN) have shown to be a powerful tool that eliminate the need for designing handcrafted features. Usually, the output of the last layer in CNN (a layer before the classification layer -known as fc7) is used as a generic feature for images. In this paper, we show that fc7 features, per se, can not get a good performance for the task of action recognition, when the network is trained only on images. We present a feature structure on top of fc7 features, which can capture the temporal variation in a video. To represent the temporal components, which is needed to capture motion information, we introduced a hierarchical structure. The hierarchical model enables to capture sub-actions from a complex action. At the higher levels of the hierarchy, it represents a coarse capture of action sequence and lower levels represent fine action elements. Furthermore, we introduce a method for extracting key-frames using binary coding of each frame in a video, which helps to improve the performance of our hierarchical model. We experimented our method on several action datasets and show that our method achieves superior results compared to other state-of-the-arts methods.

##### Abstract (translated by Google)
大部分的人类行为都是由更简单的行为的复杂时间构成组成的。动作识别任务通常依靠复杂的手工结构作为表征人类行为模型的特征。卷积神经网络（CNN）已被证明是一个强大的工具，可以消除设计手工功能的需要。通常，CNN中最后一层的输出（分类层之前的一个图层 - 称为fc7）被用作图像的一般特征。在本文中，我们表明，fc7特征，本身，不能得到一个很好的表现，行动识别的任务，当网络只训练在图像上。我们在fc7功能的基础上提出了一个功能结构，可以捕捉视频中的时间变化。为了表示捕获运动信息所需的时间分量，我们引入了分层结构。分层模型能够从复杂的动作中捕获子动作。在层次结构的较高层次上，它表示动作序列的粗略捕捉，较低层次表示精细动作元素。此外，我们介绍一种使用视频中每帧的二进制编码来提取关键帧的方法，这有助于改善我们的分层模型的性能。我们在几个动作数据集上试验了我们的方法，并且证明我们的方法与其他现有技术的方法相比，取得了更好的结果。

##### URL
[https://arxiv.org/abs/1512.03980](https://arxiv.org/abs/1512.03980)

##### PDF
[https://arxiv.org/pdf/1512.03980](https://arxiv.org/pdf/1512.03980)

