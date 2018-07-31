---
layout: post
title: "Joint Representation and Truncated Inference Learning for Correlation Filter based Tracking"
date: 2018-07-29 15:24:51
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Inference Deep_Learning Relation
author: Yingjie Yao, Xiaohe Wu, Lei Zhang, Shiguang Shan, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filter (CF) based trackers generally include two modules, i.e., feature representation and on-line model adaptation. In existing off-line deep learning models for CF trackers, the model adaptation usually is either abandoned or has closed-form solution to make it feasible to learn deep representation in an end-to-end manner. However, such solutions fail to exploit the advances in CF models, and cannot achieve competitive accuracy in comparison with the state-of-the-art CF trackers. In this paper, we investigate the joint learning of deep representation and model adaptation, where an updater network is introduced for better tracking on future frame by taking current frame representation, tracking result, and last CF tracker as input. By modeling the representor as convolutional neural network (CNN), we truncate the alternating direction method of multipliers (ADMM) and interpret it as a deep network of updater, resulting in our model for learning representation and truncated inference (RTINet). Experiments demonstrate that our RTINet tracker achieves favorable tracking accuracy against the state-of-the-art trackers and its rapid version can run at a real-time speed of 24 fps. The code and pre-trained models will be publicly available at https://github.com/tourmaline612/RTINet.

##### Abstract (translated by Google)
基于相关滤波器（CF）的跟踪器通常包括两个模块，即特征表示和在线模型适配。在用于CF跟踪器的现有离线深度学习模型中，模型适配通常要么被放弃，要么具有封闭形式的解决方案，以使得以端到端方式学习深度表示是可行的。然而，这些解决方案未能利用CF模型的进步，并且与最先进的CF跟踪器相比无法实现竞争准确性。在本文中，我们研究深度表示和模型自适应的联合学习，其中引入更新器网络以通过将当前帧表示，跟踪结果和最后CF跟踪器作为输入来更好地跟踪未来帧。通过将表示器建模为卷积神经网络（CNN），我们截断乘法器的交替方向方法（ADMM）并将其解释为更新器的深层网络，从而得到我们的学习表示和截断推理（RTINet）模型。实验表明，我们的RTINet跟踪器可以对最先进的跟踪器实现良好的跟踪精度，其快速版本可以24 fps的实时速度运行。代码和预先训练的模型将在https://github.com/tourmaline612/RTINet上公开。

##### URL
[http://arxiv.org/abs/1807.11071](http://arxiv.org/abs/1807.11071)

##### PDF
[http://arxiv.org/pdf/1807.11071](http://arxiv.org/pdf/1807.11071)

