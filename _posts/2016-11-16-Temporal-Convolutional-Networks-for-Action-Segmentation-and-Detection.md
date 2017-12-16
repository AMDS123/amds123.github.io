---
layout: post
title: "Temporal Convolutional Networks for Action Segmentation and Detection"
date: 2016-11-16 13:19:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Detection
author: Colin Lea, Michael D. Flynn, Rene Vidal, Austin Reiter, Gregory D. Hager
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to identify and temporally segment fine-grained human actions throughout a video is crucial for robotics, surveillance, education, and beyond. Typical approaches decouple this problem by first extracting local spatiotemporal features from video frames and then feeding them into a temporal classifier that captures high-level temporal patterns. We introduce a new class of temporal models, which we call Temporal Convolutional Networks (TCNs), that use a hierarchy of temporal convolutions to perform fine-grained action segmentation or detection. Our Encoder-Decoder TCN uses pooling and upsampling to efficiently capture long-range temporal patterns whereas our Dilated TCN uses dilated convolutions. We show that TCNs are capable of capturing action compositions, segment durations, and long-range dependencies, and are over a magnitude faster to train than competing LSTM-based Recurrent Neural Networks. We apply these models to three challenging fine-grained datasets and show large improvements over the state of the art.

##### Abstract (translated by Google)
在整个视频中识别和细分人类行为的时间细分能力对于机器人，监视，教育等等至关重要。典型的方法通过首先从视频帧中提取局部时空特征，然后将它们馈送到捕获高级时间模式的时间分类器来解耦这个问题。我们引入了一类新的时态模型，我们称之为时态卷积网络（TCNs），它使用时间卷积的层次来执行细粒度的动作分割或检测。我们的编码器 - 解码器TCN使用汇集和上采样来有效地捕捉远距离时间模式，而我们的扩张TCN使用扩张的卷积。我们表明，TCNs能够捕捉动作组合，分段持续时间和远距离依赖性，比竞争的基于LSTM的递归神经网络训练速度快得多。我们将这些模型应用于三个具有挑战性的细粒度数据集，并显示出对现有技术水平的巨大改进。

##### URL
[https://arxiv.org/abs/1611.05267](https://arxiv.org/abs/1611.05267)

##### PDF
[https://arxiv.org/pdf/1611.05267](https://arxiv.org/pdf/1611.05267)

