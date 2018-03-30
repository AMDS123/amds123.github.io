---
layout: post
title: "Generating Talking Face Landmarks from Speech"
date: 2018-03-26 19:25:02
categories: arXiv_CV
tags: arXiv_CV Face RNN
author: Sefik Emre Eskimez, Ross K Maddox, Chenliang Xu, Zhiyao Duan
mathjax: true
---

* content
{:toc}

##### Abstract
The presence of a corresponding talking face has been shown to significantly improve speech intelligibility in noisy conditions and for hearing impaired population. In this paper, we present a system that can generate landmark points of a talking face from an acoustic speech in real time. The system uses a long short-term memory (LSTM) network and is trained on frontal videos of 27 different speakers with automatically extracted face landmarks. After training, it can produce talking face landmarks from the acoustic speech of unseen speakers and utterances. The training phase contains three key steps. We first transform landmarks of the first video frame to pin the two eye points into two predefined locations and apply the same transformation on all of the following video frames. We then remove the identity information by transforming the landmarks into a mean face shape across the entire training dataset. Finally, we train an LSTM network that takes the first- and second-order temporal differences of the log-mel spectrogram as input to predict face landmarks in each frame. We evaluate our system using the mean-squared error (MSE) loss of landmarks of lips between predicted and ground-truth landmarks as well as their first- and second-order temporal differences. We further evaluate our system by conducting subjective tests, where the subjects try to distinguish the real and fake videos of talking face landmarks. Both tests show promising results.

##### Abstract (translated by Google)
已经表明存在相应的说话人脸可以显着改善噪声条件下的语音清晰度和听力受损人群的语音清晰度。在本文中，我们提出一个系统，可以从一个声音语音实时生成一个说话人脸的界标点。该系统使用长期短期记忆（LSTM）网络，并通过自动提取的人脸地标对27个不同扬声器的正面视频进行训练。训练之后，它可以从看不见的说话者和话语的声音讲话中产生说话人脸标志。训练阶段包含三个关键步骤。我们首先转换第一个视频帧的地标，将两个视点固定到两个预定义的位置，并对所有后续视频帧应用相同的转换。然后，我们通过在整个训练数据集中将地标变换为平均面部形状来移除身份信息。最后，我们训练一个LSTM网络，该网络将log-mel谱图的一阶和二阶时间差作为输入来预测每帧中的人脸地标。我们评估我们的系统使用预测和地面真实标志之间的嘴唇地标的均方误差（MSE）损失以及它们的一阶和二阶时间差异。我们通过进行主观测试来进一步评估我们的系统，其中主题试图区分说话人脸标志的真实和虚假视频。这两项测试都显示出可喜的成果

##### URL
[https://arxiv.org/abs/1803.09803](https://arxiv.org/abs/1803.09803)

##### PDF
[https://arxiv.org/pdf/1803.09803](https://arxiv.org/pdf/1803.09803)

