---
layout: post
title: "Patch-based Fake Fingerprint Detection Using a Fully Convolutional Neural Network with a Small Number of Parameters and an Optimal Threshold"
date: 2018-03-21 09:50:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Detection
author: Eunsoo Park, Xuenan Cui, Weonjin Kim, Jinsong Liu, Hakil Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Fingerprint authentication is widely used in biometrics due to its simple process, but it is vulnerable to fake fingerprints. This study proposes a patch-based fake fingerprint detection method using a fully convolutional neural network with a small number of parameters and an optimal threshold to solve the above-mentioned problem. Unlike the existing methods that classify a fingerprint as live or fake, the proposed method classifies fingerprints as fake, live, or background, so preprocessing methods such as segmentation are not needed. The proposed convolutional neural network (CNN) structure applies the Fire module of SqueezeNet, and the fewer parameters used require only 2.0 MB of memory. The network that has completed training is applied to the training data in a fully convolutional way, and the optimal threshold to distinguish fake fingerprints is determined, which is used in the final test. As a result of this study experiment, the proposed method showed an average classification error of 1.35%, demonstrating a fake fingerprint detection method using a high-performance CNN with a small number of parameters.

##### Abstract (translated by Google)
指纹认证由于其简单的过程而被广泛用于生物特征识别，但它容易受到假指纹的影响。本研究提出了一种基于斑块的伪指纹检测方法，该方法使用具有少量参数和最佳阈值的全卷积神经网络来解决上述问题。与现有的将指纹分类为活或假的方法不同，所提出的方法将指纹分类为假，活或背景，因此不需要诸如分割的预处理方法。提出的卷积神经网络（CNN）结构应用SqueezeNet的Fire模块，使用的参数较少仅需要2.0 MB的内存。已完成训练的网络以完全卷积方式应用于训练数据，并且确定用于区分假指纹的最佳阈值，其在最终测试中被使用。作为这项研究实验的结果，所提出的方法显示出1.35％的平均分类错误，证明使用具有少量参数的高性能CNN的假指纹检测方法。

##### URL
[http://arxiv.org/abs/1803.07817](http://arxiv.org/abs/1803.07817)

##### PDF
[http://arxiv.org/pdf/1803.07817](http://arxiv.org/pdf/1803.07817)

