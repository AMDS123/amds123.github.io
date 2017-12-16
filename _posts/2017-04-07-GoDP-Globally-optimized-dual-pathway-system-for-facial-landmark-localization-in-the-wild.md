---
layout: post
title: "GoDP: Globally optimized dual pathway system for facial landmark localization in-the-wild"
date: 2017-04-07 23:39:29
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Inference Detection Recognition Face_Recognition
author: Yuhang Wu, Shishir K. Shah, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
Facial landmark localization is a fundamental module for face recognition. Current common approach for facial landmark detection is cascaded regression, which is composed by two steps: feature extraction and facial shape regression. Recent methods employ deep convolutional networks to extract robust features in each step and the whole system could be regarded as a deep cascaded regression architecture. Unfortunately, this architecture is problematic. First, parameters in the networks are optimized from a greedy stage-wise perspective. Second, the network cannot efficiently merge landmark coordinate vectors with 2D convolutional layers. Third, the facial shape regression relies on a feature vector generated from the bottom layer of the convolutional neural network, which has recently been criticized for lacking spatial resolution to accomplish pixel-wise localization tasks. We propose a globally optimized dual-pathway system (GoDP) to handle the optimization and precision weaknesses of deep cascaded regression without resorting to high-level inference models or complex stacked architecture. This end-to-end system relies on distance-aware softmax functions and dual-pathway proposal-refinement architecture. The proposed system outperforms the state-of-the-art cascaded regression-based methods on multiple in-the-wild face alignment databases. Experiments on face identification demonstrate that GoDP significantly improves the quality of face frontalization in face recognition.

##### Abstract (translated by Google)
面部标志本地化是人脸识别的基本模块。目前常用的面部标志检测方法是级联回归，它由两个步骤组成：特征提取和面部形状回归。最近的方法采用深度卷积网络来提取每个步骤中的鲁棒特征，整个系统可以被看作是深度级联的回归架构。不幸的是，这个架构是有问题的。首先，网络中的参数从贪婪阶段的角度进行优化。其次，网络不能有效地将地标坐标向量与二维卷积层合并。第三，面部形状回归依赖于从卷积神经网络底层产生的特征向量，最近因为缺乏空间分辨率而被批评为完成像素定位任务。我们提出了一个全局优化的双路径系统（GoDP）来处理深级联回归的优化和精度弱点，而不是采用高层次的推理模型或复杂的堆栈结构。该端到端系统依靠感知距离的softmax功能和双路径建议 - 改进架构。所提出的系统胜过了在多个在野人脸对齐数据库中的最先进的基于级联回归的方法。人脸识别实验表明，GoDP能够显着提高人脸识别的人脸质量。

##### URL
[https://arxiv.org/abs/1704.02402](https://arxiv.org/abs/1704.02402)

##### PDF
[https://arxiv.org/pdf/1704.02402](https://arxiv.org/pdf/1704.02402)

