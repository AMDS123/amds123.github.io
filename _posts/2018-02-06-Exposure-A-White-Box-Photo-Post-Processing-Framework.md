---
layout: post
title: "Exposure: A White-Box Photo Post-Processing Framework"
date: 2018-02-06 16:47:58
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Deep_Learning Quantitative
author: Yuanming Hu, Hao He, Chenxi Xu, Baoyuan Wang, Stephen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Retouching can significantly elevate the visual appeal of photos, but many casual photographers lack the expertise to do this well. To address this problem, previous works have proposed automatic retouching systems based on supervised learning from paired training images acquired before and after manual editing. As it is difficult for users to acquire paired images that reflect their retouching preferences, we present in this paper a deep learning approach that is instead trained on unpaired data, namely a set of photographs that exhibits a retouching style the user likes, which is much easier to collect. Our system is formulated using deep convolutional neural networks that learn to apply different retouching operations on an input image. Network training with respect to various types of edits is enabled by modeling these retouching operations in a unified manner as resolution-independent differentiable filters. To apply the filters in a proper sequence and with suitable parameters, we employ a deep reinforcement learning approach that learns to make decisions on what action to take next, given the current state of the image. In contrast to many deep learning systems, ours provides users with an understandable solution in the form of conventional retouching edits, rather than just a "black-box" result. Through quantitative comparisons and user studies, we show that this technique generates retouching results consistent with the provided photo set.

##### Abstract (translated by Google)
修饰可以显着提升照片的视觉吸引力，但许多休闲摄影师缺乏这方面的专业知识。为了解决这个问题，以前的作品提出了自动修饰系统的基础上监督学习配对训练图像手动编辑前后采集。由于用户难以获得反映他们修饰喜好的配对图像，我们在本文中提出了一种深入的学习方法，而不是对不成对的数据进行训练，即一组展示用户喜欢的修饰风格的照片，更容易收集。我们的系统使用深度卷积神经网络制定，学习在输入图像上应用不同的修饰操作。通过将这些修饰操作以统一的方式建模为与分辨率无关的可微分过滤器来实现关于各种类型的编辑的网络培训。为了以适当的顺序和适当的参数来应用滤波器，我们采用深度强化学习方法，学习如何根据图像的当前状态来决定下一步要采取的行动。与许多深度学习系统不同的是，我们以传统的修饰编辑形式为用户提供了一个可以理解的解决方案，而不仅仅是一个“黑盒子”的结果。通过定量比较和用户研究，我们表明，这种技术产生与提供的照片集一致的修饰结果。

##### URL
[http://arxiv.org/abs/1709.09602](http://arxiv.org/abs/1709.09602)

##### PDF
[http://arxiv.org/pdf/1709.09602](http://arxiv.org/pdf/1709.09602)

