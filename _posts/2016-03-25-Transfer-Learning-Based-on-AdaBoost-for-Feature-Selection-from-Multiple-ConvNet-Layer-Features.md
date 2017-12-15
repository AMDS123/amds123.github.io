---
layout: post
title: "Transfer Learning Based on AdaBoost for Feature Selection from Multiple ConvNet Layer Features"
date: 2016-03-25 12:03:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Transfer_Learning Classification
author: Jumabek Alikhanov, Myeong Hyeon Ga, Seunghyun Ko, Geun-Sik Jo
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Networks (ConvNets) are powerful models that learn hierarchies of visual features, which could also be used to obtain image representations for transfer learning. The basic pipeline for transfer learning is to first train a ConvNet on a large dataset (source task) and then use feed-forward units activation of the trained ConvNet as image representation for smaller datasets (target task). Our key contribution is to demonstrate superior performance of multiple ConvNet layer features over single ConvNet layer features. Combining multiple ConvNet layer features will result in more complex feature space with some features being repetitive. This requires some form of feature selection. We use AdaBoost with single stumps to implicitly select only distinct features that are useful towards classification from concatenated ConvNet features. Experimental results show that using multiple ConvNet layer activation features instead of single ConvNet layer features consistently will produce superior performance. Improvements becomes significant as we increase the distance between source task and the target task.

##### Abstract (translated by Google)
卷积网络（ConvNets）是强大的模型，可以学习视觉特征的层次结构，也可以用来获取图像表示以进行传递学习。转移学习的基本流程是首先在大型数据集（源任务）上训练ConvNet，然后使用训练后的ConvNet的前馈单元作为小数据集（目标任务）的图像表示。我们的主要贡献是演示单个ConvNet层功能的多个ConvNet层功能的优越性能。组合多个ConvNet图层特征将导致更复杂的特征空间，其中一些特征是重复的。这需要某种形式的特征选择。我们使用AdaBoost和单个stumps来隐式地选择对连接的ConvNet特征进行分类有用的不同的特征。实验结果表明，使用多个ConvNet层激活特性而不是单个ConvNet层特性将会产生出色的性能。当我们增加源任务和目标任务之间的距离时，改进变得显着。

##### URL
[https://arxiv.org/abs/1602.00417](https://arxiv.org/abs/1602.00417)

##### PDF
[https://arxiv.org/pdf/1602.00417](https://arxiv.org/pdf/1602.00417)

