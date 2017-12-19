---
layout: post
title: "Recurrent Network Models for Human Dynamics"
date: 2015-09-29 01:28:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Represenation_Learning RNN Prediction Detection Recognition
author: Katerina Fragkiadaki, Sergey Levine, Panna Felsen, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the Encoder-Recurrent-Decoder (ERD) model for recognition and prediction of human body pose in videos and motion capture. The ERD model is a recurrent neural network that incorporates nonlinear encoder and decoder networks before and after recurrent layers. We test instantiations of ERD architectures in the tasks of motion capture (mocap) generation, body pose labeling and body pose forecasting in videos. Our model handles mocap training data across multiple subjects and activity domains, and synthesizes novel motions while avoid drifting for long periods of time. For human pose labeling, ERD outperforms a per frame body part detector by resolving left-right body part confusions. For video pose forecasting, ERD predicts body joint displacements across a temporal horizon of 400ms and outperforms a first order motion model based on optical flow. ERDs extend previous Long Short Term Memory (LSTM) models in the literature to jointly learn representations and their dynamics. Our experiments show such representation learning is crucial for both labeling and prediction in space-time. We find this is a distinguishing feature between the spatio-temporal visual domain in comparison to 1D text, speech or handwriting, where straightforward hard coded representations have shown excellent results when directly combined with recurrent units.

##### Abstract (translated by Google)
我们提出编码器 - 回复 - 解码器（ERD）模型，用于识别和预测视频和动作捕捉中的人体姿态。 ERD模型是一种递归神经网络，在复现层之前和之后包含非线性编码器和解码器网络。我们在运动捕捉（mocap）生成，身体姿势标记和视频中的身体姿势预测任务中测试ERD体系结构的实例。我们的模型处理跨多个主题和活动领域的mocap训练数据，并合成新颖的运动，同时避免长时间漂移。对于人体姿势标记，通过解决左右身体部位混乱，ERD优于每帧身体部位检测器。对于视频姿态预​​测，ERD预测400ms时间范围内的身体关节位移，并且优于基于光流的一阶运动模型。 ERD延伸了文献中的以前的长时短期记忆（LSTM）模型，以共同学习表示及其动态。我们的实验表明这样的表示学习对于时空中的标记和预测是至关重要的。我们发现这是时空视觉领域与一维文本，语音或手写相比的一个显着特征，其中直接的硬编码表示直接与经常性单位结合显示出优异的结果。

##### URL
[https://arxiv.org/abs/1508.00271](https://arxiv.org/abs/1508.00271)

##### PDF
[https://arxiv.org/pdf/1508.00271](https://arxiv.org/pdf/1508.00271)

