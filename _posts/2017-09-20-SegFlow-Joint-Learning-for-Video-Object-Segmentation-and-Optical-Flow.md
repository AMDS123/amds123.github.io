---
layout: post
title: "SegFlow: Joint Learning for Video Object Segmentation and Optical Flow"
date: 2017-09-20 07:38:20
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Jingchun Cheng, Yi-Hsuan Tsai, Shengjin Wang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an end-to-end trainable network, SegFlow, for simultaneously predicting pixel-wise object segmentation and optical flow in videos. The proposed SegFlow has two branches where useful information of object segmentation and optical flow is propagated bidirectionally in a unified framework. The segmentation branch is based on a fully convolutional network, which has been proved effective in image segmentation task, and the optical flow branch takes advantage of the FlowNet model. The unified framework is trained iteratively offline to learn a generic notion, and fine-tuned online for specific objects. Extensive experiments on both the video object segmentation and optical flow datasets demonstrate that introducing optical flow improves the performance of segmentation and vice versa, against the state-of-the-art algorithms.

##### Abstract (translated by Google)
本文提出了一个端到端的可训练网络SegFlow，用于同时预测视频中像素级的对象分割和光流。所提出的SegFlow有两个分支，其中对象分割和光流的有用信息在一个统一的框架中双向传播。分割分支基于完全卷积网络，在图像分割任务中被证明是有效的，光流分支利用FlowNet模型。统一的框架被反复训练离线学习一个通用的概念，并针对特定对象进行在线微调。对视频对象分割和光流数据集的大量实验表明，引入光流可以改善分割的性能，反之亦然，而不是最先进的算法。

##### URL
[https://arxiv.org/abs/1709.06750](https://arxiv.org/abs/1709.06750)

##### PDF
[https://arxiv.org/pdf/1709.06750](https://arxiv.org/pdf/1709.06750)

