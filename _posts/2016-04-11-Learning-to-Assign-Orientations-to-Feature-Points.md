---
layout: post
title: "Learning to Assign Orientations to Feature Points"
date: 2016-04-11 14:03:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Kwang Moo Yi, Yannick Verdie, Pascal Fua, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We show how to train a Convolutional Neural Network to assign a canonical orientation to feature points given an image patch centered on the feature point. Our method improves feature point matching upon the state-of-the art and can be used in conjunction with any existing rotation sensitive descriptors. To avoid the tedious and almost impossible task of finding a target orientation to learn, we propose to use Siamese networks which implicitly find the optimal orientations during training. We also propose a new type of activation function for Neural Networks that generalizes the popular ReLU, maxout, and PReLU activation functions. This novel activation performs better for our task. We validate the effectiveness of our method extensively with four existing datasets, including two non-planar datasets, as well as our own dataset. We show that we outperform the state-of-the-art without the need of retraining for each dataset.

##### Abstract (translated by Google)
我们展示了如何训练一个卷积神经网络，为特征点分配一个规范的方向，给定一个以特征点为中心的图像块。我们的方法改进了现有技术中的特征点匹配，并且可以与任何现有的旋转敏感描述符结合使用。为了避免找到目标学习的单调乏味和几乎不可能的任务，我们建议使用连接网络，它隐式地找到训练期间的最佳方向。我们还提出了一种新型的神经网络激活功能，它推广了流行的ReLU，Maxout和PReLU激活功能。这种新颖的激活对我们的任务表现更好。我们用四个现有数据集（包括两个非平面数据集以及我们自己的数据集）广泛验证了我们方法的有效性。我们表明，我们超越了最先进的技术，而不需要每个数据集的再培训。

##### URL
[https://arxiv.org/abs/1511.04273](https://arxiv.org/abs/1511.04273)

##### PDF
[https://arxiv.org/pdf/1511.04273](https://arxiv.org/pdf/1511.04273)

