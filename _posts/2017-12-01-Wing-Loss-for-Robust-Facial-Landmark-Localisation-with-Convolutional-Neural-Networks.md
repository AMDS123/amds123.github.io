---
layout: post
title: "Wing Loss for Robust Facial Landmark Localisation with Convolutional Neural Networks"
date: 2017-12-01 21:40:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhen-Hua Feng, Josef Kittler, Muhammad Awais, Patrik Huber, Xiao-Jun Wu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new loss function, namely Wing loss, for robust facial landmark localisation with Convolutional Neural Networks (CNNs). We first compare and analyse different objective functions and show that the L1 and smooth L1 loss functions perform much better than the widely used L2 loss function in facial landmark localisation. The analysis of these loss functions suggests that, for the training of a CNN-based localisation model, more attention should be paid to small and medium range errors. To this end, we design a piece-wise loss function. The new loss function amplifies the impact of errors from the interval (-w,w) by switching from L1 loss to a modified logarithm function. </p> <p>To address the problem of under-representation of samples with large out-of-plane head rotations in the training set, we propose a simple but effective boosting strategy, referred to as Hard Sample Mining (HSM). In particular, we deal with the data imbalance problem by duplicating the minority training samples and perturbing them by injecting random image rotation, bounding box translation and other data augmentation approaches. Last, the proposed approach is extended to create a two-stage localisation framework for robust facial landmark localisation in the wild. The experimental results obtained on the AFLW and 300W datasets demonstrate the merits of the Wing loss function, and prove the superiority of the proposed method over the state-of-the-art approaches.

##### Abstract (translated by Google)
我们提出了一个新的损失函数，即永久损失，用于卷积神经网络（CNN）的鲁棒性面部标志定位。首先对不同的目标函数进行比较和分析，结果表明L1和平滑L1损失函数在面部地标定位中比广泛使用的L2损失函数表现得更好。对这些损失函数的分析表明，对于基于CNN的本地化模型的培训，应该更加关注中小范围的错误。为此，我们设计了一个分段式损失函数。新的损失函数通过从L1损失切换到修改的对数函数来放大来自间隔（-w，w）的错误的影响。为了解决训练集中具有较大的平面外头部旋转的样本的低代表性问题，我们提出了一种简单而有效的提升策略，称为硬采样（HSM）。特别是通过复制少数训练样本，通过注入随机图像旋转，边界框平移和其他数据增强方法来扰动数据不平衡问题。最后，所提出的方法被扩展为创建两阶段本地化框架，用于在野外强健的面部标志物定位。在AFLW和300W数据集上获得的实验结果证明了Wing损失函数的优点，并且证明了所提出的方法优于最先进的方法的优越性。

##### URL
[http://arxiv.org/abs/1711.06753](http://arxiv.org/abs/1711.06753)

