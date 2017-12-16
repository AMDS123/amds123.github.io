---
layout: post
title: "Predicting Video Saliency with Object-to-Motion CNN and Two-layer Convolutional LSTM"
date: 2017-09-25 04:16:54
categories: arXiv_CV
tags: arXiv_CV Salient Attention Tracking CNN RNN Prediction Relation
author: Lai Jiang, Mai Xu, Zulin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past few years, deep neural networks (DNNs) have exhibited great success in predicting the saliency of images. However, there are few works that apply DNNs to predict the saliency of generic videos. In this paper, we propose a novel DNN-based video saliency prediction method. Specifically, we establish a large-scale eye-tracking database of videos (LEDOV), which provides sufficient data to train the DNN models for predicting video saliency. Through the statistical analysis of our LEDOV database, we find that human attention is normally attracted by objects, particularly moving objects or the moving parts of objects. Accordingly, we propose an object-to-motion convolutional neural network (OM-CNN) to learn spatio-temporal features for predicting the intra-frame saliency via exploring the information of both objectness and object motion. We further find from our database that there exists a temporal correlation of human attention with a smooth saliency transition across video frames. Therefore, we develop a two-layer convolutional long short-term memory (2C-LSTM) network in our DNN-based method, using the extracted features of OM-CNN as the input. Consequently, the inter-frame saliency maps of videos can be generated, which consider the transition of attention across video frames. Finally, the experimental results show that our method advances the state-of-the-art in video saliency prediction.

##### Abstract (translated by Google)
在过去的几年里，深度神经网络（DNNs）在预测图像的显着性方面取得了巨大的成功。但是，很少有作品使用DNN来预测通用视频的显着性。本文提出了一种新的基于DNN的视频显着性预测方法。具体来说，我们建立了一个大规模的视频视频数据库（LEDOV），它提供了足够的数据来训练用于预测视频显着性的DNN模型。通过对我们的LEDOV数据库进行统计分析，发现人类的注意力通常被物体所吸引，特别是移动物体或物体的运动部分。因此，本文提出了一种运动对象卷积神经网络（OM-CNN），通过探索对象运动信息和物体运动信息来学习时空特征，从而预测帧内显着性。我们从我们的数据库中进一步发现，在视频帧之间存在人类注意力与平滑显着性转换的时间相关性。因此，我们在基于DNN的方法中，利用OM-CNN的提取特征作为输入，开发了一个双层卷积长短期记忆（2C-LSTM）网络。因此，可以生成视频的帧间显着性图，其考虑跨视频帧的注意力的转变。最后，实验结果表明，我们的方法推进了视频显着性预测的最新技术。

##### URL
[https://arxiv.org/abs/1709.06316](https://arxiv.org/abs/1709.06316)

##### PDF
[https://arxiv.org/pdf/1709.06316](https://arxiv.org/pdf/1709.06316)

