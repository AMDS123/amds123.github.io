---
layout: post
title: "Framewise approach in multimodal emotion recognition in OMG challenge"
date: 2018-05-03 15:21:44
categories: arXiv_AI
tags: arXiv_AI Face CNN Prediction Recognition
author: Grigoriy Sterling, Andrey Belyaev, Maxim Ryabov
mathjax: true
---

* content
{:toc}

##### Abstract
In this report we described our approach achieves $53\%$ of unweighted accuracy over $7$ emotions and $0.05$ and $0.09$ mean squared errors for arousal and valence in OMG emotion recognition challenge. Our results were obtained with ensemble of single modality models trained on voice and face data from video separately. We consider each stream as a sequence of frames. Next we estimated features from frames and handle it with recurrent neural network. As audio frame we mean short $0.4$ second spectrogram interval. For features estimation for face pictures we used own ResNet neural network pretrained on AffectNet database. Each short spectrogram was considered as a picture and processed by convolutional network too. As a base audio model we used ResNet pretrained in speaker recognition task. Predictions from both modalities were fused on decision level and improve single-channel approaches by a few percent

##### Abstract (translated by Google)
在这份报告中，我们描述了我们的方法在OMG情绪识别挑战中实现了超过$ 7 $情绪的$ 53 \％$的未加权准确性和$ 0.05 $以及$ 0.09 $均方差的唤醒和效价错误。我们的结果是通过分别在视频和面部数据上训练的单一模态模型获得的。我们将每个流视为一系列帧。接下来我们估计帧的特征并用递归神经网络处理它。作为音频帧我们的意思是$ 0.4美元的第二谱图间隔。对于面部图片的特征估计，我们使用在AffectNet数据库上预先训练过的自己的ResNet神经网络。每张短谱图都被认为是一张图片，并且也被卷积网络处理。作为基础音频模型，我们使用ResNet预先训练在说话人识别任务。来自两种模式的预测都在决策层面进行融合，并将单通道方法改进了几个百分点

##### URL
[http://arxiv.org/abs/1805.01369](http://arxiv.org/abs/1805.01369)

##### PDF
[http://arxiv.org/pdf/1805.01369](http://arxiv.org/pdf/1805.01369)

