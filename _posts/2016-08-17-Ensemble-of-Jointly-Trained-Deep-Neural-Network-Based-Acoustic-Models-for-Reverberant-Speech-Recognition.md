---
layout: post
title: "Ensemble of Jointly Trained Deep Neural Network-Based Acoustic Models for Reverberant Speech Recognition"
date: 2016-08-17 14:43:17
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Jeehye Lee, Myungin Lee, Joon-Hyuk Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Distant speech recognition is a challenge, particularly due to the corruption of speech signals by reverberation caused by large distances between the speaker and microphone. In order to cope with a wide range of reverberations in real-world situations, we present novel approaches for acoustic modeling including an ensemble of deep neural networks (DNNs) and an ensemble of jointly trained DNNs. First, multiple DNNs are established, each of which corresponds to a different reverberation time 60 (RT60) in a setup step. Also, each model in the ensemble of DNN acoustic models is further jointly trained, including both feature mapping and acoustic modeling, where the feature mapping is designed for the dereverberation as a front-end. In a testing phase, the two most likely DNNs are chosen from the DNN ensemble using maximum a posteriori (MAP) probabilities, computed in an online fashion by using maximum likelihood (ML)-based blind RT60 estimation and then the posterior probability outputs from two DNNs are combined using the ML-based weights as a simple average. Extensive experiments demonstrate that the proposed approach leads to substantial improvements in speech recognition accuracy over the conventional DNN baseline systems under diverse reverberant conditions.

##### Abstract (translated by Google)
遥远的语音识别是一个挑战，特别是由于扬声器和麦克风之间的距离很远而引起的混响使语音信号受损。为了应对现实世界中广泛的混响，我们提出了一种新的声学建模方法，包括深度神经网络（DNNs）的集合和联合训练的DNN的集合。首先，建立多个DNN，每个DNN在设置步骤中对应于不同的混响时间60（RT60）。此外，DNN声学模型的集合中的每个模型被进一步联合训练，包括特征映射和声学建模，其中特征映射被设计为用于去混响作为前端。在测试阶段，使用最大后验概率（MAP）从DNN集合中选择两个最可能的DNN，以最大似然（ML）为基础的盲RT60估计以在线方式计算，然后从两个后验概率输出使用基于ML的权重将DNN组合为简单的平均值。大量的实验表明，在不同的混响条件下，所提出的方法相对于传统的DNN基线系统导致语音识别精度的实质性改进。

##### URL
[https://arxiv.org/abs/1608.04983](https://arxiv.org/abs/1608.04983)

##### PDF
[https://arxiv.org/pdf/1608.04983](https://arxiv.org/pdf/1608.04983)

