---
layout: post
title: "Deep Learning of Appearance Models for Online Object Tracking"
date: 2016-07-09 06:15:20
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Deep_Learning
author: Mengyao Zhai, Mehrsan Javan Roshtkhari, Greg Mori
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel deep learning based approach for vision based single target tracking. We address this problem by proposing a network architecture which takes the input video frames and directly computes the tracking score for any candidate target location by estimating the probability distributions of the positive and negative examples. This is achieved by combining a deep convolutional neural network with a Bayesian loss layer in a unified framework. In order to deal with the limited number of positive training examples, the network is pre-trained offline for a generic image feature representation and then is fine-tuned in multiple steps. An online fine-tuning step is carried out at every frame to learn the appearance of the target. We adopt a two-stage iterative algorithm to adaptively update the network parameters and maintain a probability density for target/non-target regions. The tracker has been tested on the standard tracking benchmark and the results indicate that the proposed solution achieves state-of-the-art tracking results.

##### Abstract (translated by Google)
本文介绍了一种基于视觉的单目标跟踪的新型深度学习方法。我们通过提出一种网络结构来解决这个问题，该网络结构采用输入视频帧，并通过估计正例和负例的概率分布直接计算任何候选目标位置的跟踪分数。这是通过将深度卷积神经网络与贝叶斯损失层结合在一个统一的框架中来实现的。为了处理有限数量的正面训练示例，网络被预先离线训练以用于通用图像特征表示，然后在多个步骤中被微调。在每一帧进行在线微调步骤以了解目标的外观。我们采用两阶段迭代算法来自适应地更新网络参数，并保持目标/非目标区域的概率密度。跟踪器已经在标准跟踪基准上进行了测试，结果表明所提出的解决方案实现了最先进的跟踪结果。

##### URL
[https://arxiv.org/abs/1607.02568](https://arxiv.org/abs/1607.02568)

##### PDF
[https://arxiv.org/pdf/1607.02568](https://arxiv.org/pdf/1607.02568)

