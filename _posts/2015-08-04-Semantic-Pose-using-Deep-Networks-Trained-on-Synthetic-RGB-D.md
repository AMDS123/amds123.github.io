---
layout: post
title: "Semantic Pose using Deep Networks Trained on Synthetic RGB-D"
date: 2015-08-04 17:07:51
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Transfer_Learning
author: Jeremie Papon, Markus Schoeler
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the problem of indoor scene understanding from RGB-D images. Specifically, we propose to find instances of common furniture classes, their spatial extent, and their pose with respect to generalized class models. To accomplish this, we use a deep, wide, multi-output convolutional neural network (CNN) that predicts class, pose, and location of possible objects simultaneously. To overcome the lack of large annotated RGB-D training sets (especially those with pose), we use an on-the-fly rendering pipeline that generates realistic cluttered room scenes in parallel to training. We then perform transfer learning on the relatively small amount of publicly available annotated RGB-D data, and find that our model is able to successfully annotate even highly challenging real scenes. Importantly, our trained network is able to understand noisy and sparse observations of highly cluttered scenes with a remarkable degree of accuracy, inferring class and pose from a very limited set of cues. Additionally, our neural network is only moderately deep and computes class, pose and position in tandem, so the overall run-time is significantly faster than existing methods, estimating all output parameters simultaneously in parallel on a GPU in seconds.

##### Abstract (translated by Google)
在这项工作中，我们解决了RGB-D图像的室内场景理解问题。具体而言，我们建议寻找普通类别模型的普通家具类别，空间范围和姿态。为了达到这个目的，我们使用一个深度的，宽的，多输出的卷积神经网络（CNN）来同时预测可能物体的类别，姿态和位置。为了克服缺乏大规模注释的RGB-D训练集（尤其是那些有姿势的训练集），我们使用一个即时渲染管线，在训练的同时生成逼真的混乱的房间场景。然后，我们对相对较少数量的公开可用注释的RGB-D数据进行转换学习，并发现我们的模型能够成功注释即使是高度具有挑战性的真实场景。重要的是，我们的训练网络能够以非常精确的程度理解高度混乱的场景的噪声和稀疏观测，从极其有限的线索推断出课堂和姿势。另外，我们的神经网络只有中等深度，并且可以同时计算类，姿态和位置，所以总体运行时间比现有方法快得多，可以在几秒钟内同时在GPU上并行估计所有输出参数。

##### URL
[https://arxiv.org/abs/1508.00835](https://arxiv.org/abs/1508.00835)

##### PDF
[https://arxiv.org/pdf/1508.00835](https://arxiv.org/pdf/1508.00835)

