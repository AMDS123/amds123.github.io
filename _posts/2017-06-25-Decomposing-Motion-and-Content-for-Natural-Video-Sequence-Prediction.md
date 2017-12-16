---
layout: post
title: "Decomposing Motion and Content for Natural Video Sequence Prediction"
date: 2017-06-25 04:18:12
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN RNN Prediction
author: Ruben Villegas, Jimei Yang, Seunghoon Hong, Xunyu Lin, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep neural network for the prediction of future frames in natural video sequences. To effectively handle complex evolution of pixels in videos, we propose to decompose the motion and content, two key components generating dynamics in videos. Our model is built upon the Encoder-Decoder Convolutional Neural Network and Convolutional LSTM for pixel-level prediction, which independently capture the spatial layout of an image and the corresponding temporal dynamics. By independently modeling motion and content, predicting the next frame reduces to converting the extracted content features into the next frame content by the identified motion features, which simplifies the task of prediction. Our model is end-to-end trainable over multiple time steps, and naturally learns to decompose motion and content without separate training. We evaluate the proposed network architecture on human activity videos using KTH, Weizmann action, and UCF-101 datasets. We show state-of-the-art performance in comparison to recent approaches. To the best of our knowledge, this is the first end-to-end trainable network architecture with motion and content separation to model the spatiotemporal dynamics for pixel-level future prediction in natural videos.

##### Abstract (translated by Google)
我们提出了一个深度神经网络预测自然视频序列中的未来帧。为了有效处理视频中像素的复杂演化，我们建议分解运动和内容，两个关键组件在视频中产生动态。我们的模型建立在编码器 - 解码器卷积神经网络和卷积LSTM上，用于像素级预测，它独立地捕捉图像的空间布局和相应的时间动态。通过对运动和内容进行独立建模，预测下一帧将通过所识别的运动特征将提取的内容特征转换为下一帧内容，这简化了预测任务。我们的模型可以在多个时间段内进行端到端的训练，并自然学习分解运动和内容，而无需单独训练。我们使用KTH，Weizmann动作和UCF-101数据集来评估所提议的人类活动视频网络架构。与最近的方法相比，我们展现了最先进的性能。据我们所知，这是第一个端到端的可训练网络体系结构，运动和内容分离，为自然视频中的像素级未来预测建立时空动态模型。

##### URL
[https://arxiv.org/abs/1706.08033](https://arxiv.org/abs/1706.08033)

##### PDF
[https://arxiv.org/pdf/1706.08033](https://arxiv.org/pdf/1706.08033)

