---
layout: post
title: "RGB Video Based Tennis Action Recognition Using a Deep Weighted Long Short-Term Memory"
date: 2018-08-02 14:58:51
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition Embedding CNN RNN Deep_Learning Recognition
author: Jiaxin Cai, Xin Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Action recognition has attracted increasing attention from RGB input in computer vision partially due to potential applications on somatic simulation and statistics of sport such as virtual tennis game and tennis techniques and tactics analysis by video. Recently, deep learning based methods have achieved promising performance for action recognition. In this paper, we propose weighted Long Short-Term Memory adopted with convolutional neural network representations for three dimensional tennis shots recognition. First, the local two-dimensional convolutional neural network spatial representations are extracted from each video frame individually using a pre-trained Inception network. Then, a weighted Long Short-Term Memory decoder is introduced to take the output state at time t and the historical embedding feature at time t-1 to generate feature vector using a score weighting scheme. Finally, we use the adopted CNN and weighted LSTM to map the original visual features into a vector space to generate the spatial-temporal semantical description of visual sequences and classify the action video content. Experiments on the benchmark demonstrate that our method using only simple raw RGB video can achieve better performance than the state-of-the-art baselines for tennis shot recognition.

##### Abstract (translated by Google)
动作识别引起了计算机视觉中RGB输入的越来越多的关注，部分原因在于体育模拟和运动统计的潜在应用，如虚拟网球比赛和网球技术以及视频战术分析。最近，基于深度学习的方法已经取得了有希望的动作识别性能。在本文中，我们提出加权长短期记忆采用卷积神经网络表示三维网球拍摄识别。首先，使用预先训练的初始网络从每个视频帧单独提取局部二维卷积神经网络空间表示。然后，引入加权长短期存储器解码器以获取时间t处的输出状态和时间t-1处的历史嵌入特征以使用得分加权方案生成特征向量。最后，我们使用所采用的CNN和加权LSTM将原始视觉特征映射到矢量空间，以生成视觉序列的时空语义描述并对动作视频内容进行分类。基准测试的实验表明，我们使用简单原始RGB视频的方法可以获得比网球拍摄识别最先进的基线更好的性能。

##### URL
[http://arxiv.org/abs/1808.00845](http://arxiv.org/abs/1808.00845)

##### PDF
[http://arxiv.org/pdf/1808.00845](http://arxiv.org/pdf/1808.00845)

