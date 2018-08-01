---
layout: post
title: "Multi-Speaker DOA Estimation Using Deep Convolutional Networks Trained with Noise Signals"
date: 2018-07-31 09:40:39
categories: arXiv_SD
tags: arXiv_SD CNN Classification
author: Soumitro Chakrabarty, Emanu&#xeb;l A. P. Habets
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning based methods for source localization, being data driven, can be adapted to different acoustic conditions via training and have been shown to be robust to adverse acoustic environments. In this paper, a convolutional neural network (CNN) based supervised learning method for estimating the direction-of-arrival (DOA) of multiple speakers is proposed. Multi-speaker DOA estimation is formulated as a multi-class multi-label classification problem, where the assignment of each DOA label to the input feature is treated as a separate binary classification problem. The phase component of the short-time Fourier transform (STFT) coefficients of the received microphone signals are directly fed into the CNN, and the features for DOA estimation are learnt during training. Utilizing the assumption of disjoint speaker activity in the STFT domain, a novel method is proposed to train the CNN with synthesized noise signals. Through experimental evaluation with both simulated and measured acoustic impulse responses, the ability of the proposed DOA estimation approach to adapt to unseen acoustic conditions and its robustness to unseen noise type is demonstrated. Through additional empirical investigation, it is also shown that with an array of M microphones our proposed framework yields the best localization performance with M-1 convolution layers. The ability of the proposed method to accurately localize speakers in a dynamic acoustic scenario with varying number of sources is also shown.

##### Abstract (translated by Google)
用于源定位（数据驱动）的基于监督学习的方法可以通过训练适应于不同的声学条件，并且已经被证明对于不利的声学环境是稳健的。本文提出了一种基于卷积神经网络（CNN）的监测学习方法，用于估计多个扬声器的到达方向（DOA）。多扬声器DOA估计被公式化为多类多标签分类问题，其中将每个DOA标签分配给输入特征被视为单独的二元分类问题。接收的麦克风信号的短时傅立叶变换（STFT）系数的相位分量被直接馈送到CNN，并且在训练期间学习用于DOA估计的特征。利用STFT域中不相交说话者活动的假设，提出了一种利用合成噪声信号训练CNN的新方法。通过模拟和测量的声脉冲响应的实验评估，证明了所提出的DOA估计方法适应于看不见的声学条件及其对看不见的噪声类型的鲁棒性的能力。通过额外的实证研究，还表明，使用M个麦克风阵列，我们提出的框架可以产生M-1卷积层的最佳定位性能。还示出了所提出的方法在具有不同数量的源的动态声学场景中精确定位扬声器的能力。

##### URL
[http://arxiv.org/abs/1807.11722](http://arxiv.org/abs/1807.11722)

##### PDF
[http://arxiv.org/pdf/1807.11722](http://arxiv.org/pdf/1807.11722)

