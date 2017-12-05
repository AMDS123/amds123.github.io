---
layout: post
title: 'Learning Human Motion Models for Long-term Predictions'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: [arXiv_CV]
author: Partha Ghosh, Jie Song, Emre Aksan, Otmar Hilliges
---

* content
{:toc}

##### Abstract
We propose a new architecture for the learning of predictive spatio-temporal motion models from data alone. Our approach, dubbed the Dropout Autoencoder LSTM, is capable of synthesizing natural looking motion sequences over long time horizons without catastrophic drift or motion degradation. The model consists of two components, a 3-layer recurrent neural network to model temporal aspects and a novel auto-encoder that is trained to implicitly recover the spatial structure of the human skeleton via randomly removing information about joints during training time. This Dropout Autoencoder (D-AE) is then used to filter each predicted pose of the LSTM, reducing accumulation of error and hence drift over time. Furthermore, we propose new evaluation protocols to assess the quality of synthetic motion sequences even for which no ground truth data exists. The proposed protocols can be used to assess generated sequences of arbitrary length. Finally, we evaluate our proposed method on two of the largest motion-capture datasets available to date and show that our model outperforms the state-of-the-art on a variety of actions, including cyclic and acyclic motion, and that it can produce natural looking sequences over longer time horizons than previous methods.

##### Abstract (translated by Google)
我们提出了一个新的体系结构，用于仅从数据中学习预测时空运动模型。我们的方法被称为Dropout Autoencoder LSTM，能够在长时间范围内合成自然的运动序列，而不会产生灾难性的漂移或运动退化。该模型由两部分组成：一个三层递归神经网络，用于对时间方面进行建模;一个新型自动编码器，通过在训练时间内随机删除关节信息，训练隐式恢复人体骨架的空间结构。然后使用该丢弃自动编码器（D-AE）来过滤LSTM的每个预测姿态，减少误差的累积并因此随时间推移漂移。此外，我们提出新的评估协议来评估合成运动序列的质量，即使没有地面实况数据存在。建议的协议可以用来评估任意长度的生成序列。最后，我们评估我们提出的方法在两个迄今为止最大的运动捕捉数据集上，并显示我们的模型在各种行动上的表现都优于现有技术，包括循环和非循环运动，并且可以产生比以前的方法在更长的时间范围内看起来自然的序列。

##### URL
[http://arxiv.org/abs/1704.02827](http://arxiv.org/abs/1704.02827)

