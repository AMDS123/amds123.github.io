---
layout: post
title: "Self-Supervised Learning for Stereo Matching with Self-Improving Ability"
date: 2017-09-04 12:56:18
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yiran Zhong, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Exiting deep-learning based dense stereo matching methods often rely on ground-truth disparity maps as the training signals, which are however not always available in many situations. In this paper, we design a simple convolutional neural network architecture that is able to learn to compute dense disparity maps directly from the stereo inputs. Training is performed in an end-to-end fashion without the need of ground-truth disparity maps. The idea is to use image warping error (instead of disparity-map residuals) as the loss function to drive the learning process, aiming to find a depth-map that minimizes the warping error. While this is a simple concept well-known in stereo matching, to make it work in a deep-learning framework, many non-trivial challenges must be overcome, and in this work we provide effective solutions. Our network is self-adaptive to different unseen imageries as well as to different camera settings. Experiments on KITTI and Middlebury stereo benchmark datasets show that our method outperforms many state-of-the-art stereo matching methods with a margin, and at the same time significantly faster.

##### Abstract (translated by Google)
基于深度学习的密集立体匹配方法往往依赖于地面真实视差图作为训练信号，然而这在很多情况下并不总是可用的。在本文中，我们设计了一个简单的卷积神经网络结构，能够学习直接从立体声输入计算密集视差图。训练是以端对端的方式进行的，不需要地面真实视差图。这个想法是使用图像扭曲误差（而不是视差图残差）作为驱动学习过程的损失函数，目的是找到使翘曲误差最小化的深度图。虽然这是一个在立体匹配方面众所周知的简单概念，但要使其在深度学习框架下工作，必须克服许多不平凡的挑战，并在此工作中提供有效的解决方案。我们的网络能够自适应不同的不可见的图像以及不同的相机设置。在KITTI和Middlebury立体声基准数据集上进行的实验表明，我们的方法胜过了许多具有余量的最先进的立体匹配方法，同时速度更快。

##### URL
[https://arxiv.org/abs/1709.00930](https://arxiv.org/abs/1709.00930)

##### PDF
[https://arxiv.org/pdf/1709.00930](https://arxiv.org/pdf/1709.00930)

