---
layout: post
title: "DeepBreath: Deep Learning of Breathing Patterns for Automatic Stress Recognition using Low-Cost Thermal Imaging in Unconstrained Settings"
date: 2017-08-20 21:36:30
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Recognition
author: Youngjun Cho, Nadia Bianchi-Berthouze, Simon J. Julier
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DeepBreath, a deep learning model which automatically recognises people's psychological stress level (mental overload) from their breathing patterns. Using a low cost thermal camera, we track a person's breathing patterns as temperature changes around his/her nostril. The paper's technical contribution is threefold. First of all, instead of creating hand-crafted features to capture aspects of the breathing patterns, we transform the uni-dimensional breathing signals into two dimensional respiration variability spectrogram (RVS) sequences. The spectrograms easily capture the complexity of the breathing dynamics. Second, a spatial pattern analysis based on a deep Convolutional Neural Network (CNN) is directly applied to the spectrogram sequences without the need of hand-crafting features. Finally, a data augmentation technique, inspired from solutions for over-fitting problems in deep learning, is applied to allow the CNN to learn with a small-scale dataset from short-term measurements (e.g., up to a few hours). The model is trained and tested with data collected from people exposed to two types of cognitive tasks (Stroop Colour Word Test, Mental Computation test) with sessions of different difficulty levels. Using normalised self-report as ground truth, the CNN reaches 84.59% accuracy in discriminating between two levels of stress and 56.52% in discriminating between three levels. In addition, the CNN outperformed powerful shallow learning methods based on a single layer neural network. Finally, the dataset of labelled thermal images will be open to the community.

##### Abstract (translated by Google)
我们提出DeepBreath，这是一种深度学习模式，能够从呼吸模式中自动识别人们的心理压力水平（精神负担）。使用低成本的热像仪，我们追踪一个人的呼吸模式，因为他/她的鼻孔周围的温度变化。本文的技术贡献有三个方面。首先，我们不是创建手工特征来捕捉呼吸模式，而是将单维呼吸信号转换成二维呼吸变异谱图（RVS）序列。频谱图很容易捕捉到呼吸动态的复杂性。其次，基于深度卷积神经网络（CNN）的空间模式分析直接应用于谱图序列，而不需要手工特征。最后，从深度学习中的过度拟合问题的解决方案中启发的数据增强技术被应用于允许CNN利用短期测量（例如长达几个小时）的小规模数据集进行学习。该模型是训练和测试从暴露于两种类型的认知任务（Stroop色彩词测试，心理计算测试）的人收集的数据与不同难度级别的会议。以归一化自报作为基础事实，CNN在区分两个层次的压力方面达到了84.59％的准确率，在三个层面上区分了CNN达到了56.52％。此外，CNN的表现优于基于单层神经网络的强大的浅层学习方法。最后，标记的热图像数据集将向社区开放。

##### URL
[https://arxiv.org/abs/1708.06026](https://arxiv.org/abs/1708.06026)

##### PDF
[https://arxiv.org/pdf/1708.06026](https://arxiv.org/pdf/1708.06026)

