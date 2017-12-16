---
layout: post
title: "Video Classification With CNNs: Using The Codec As A Spatio-Temporal Activity Sensor"
date: 2017-10-14 00:43:18
categories: arXiv_CV
tags: arXiv_CV CNN Video_Classification Inference Classification
author: Aaron Chadha, Alhabib Abbas, Yiannis Andreopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate video classification via a two-stream convolutional neural network (CNN) design that directly ingests information extracted from compressed video bitstreams. Our approach begins with the observation that all modern video codecs divide the input frames into macroblocks (MBs). We demonstrate that selective access to MB motion vector (MV) information within compressed video bitstreams can also provide for selective, motion-adaptive, MB pixel decoding (a.k.a., MB texture decoding). This in turn allows for the derivation of spatio-temporal video activity regions at extremely high speed in comparison to conventional full-frame decoding followed by optical flow estimation. In order to evaluate the accuracy of a video classification framework based on such activity data, we independently train two CNN architectures on MB texture and MV correspondences and then fuse their scores to derive the final classification of each test video. Evaluation on two standard datasets shows that the proposed approach is competitive to the best two-stream video classification approaches found in the literature. At the same time: (i) a CPU-based realization of our MV extraction is over 977 times faster than GPU-based optical flow methods; (ii) selective decoding is up to 12 times faster than full-frame decoding; (iii) our proposed spatial and temporal CNNs perform inference at 5 to 49 times lower cloud computing cost than the fastest methods from the literature.

##### Abstract (translated by Google)
我们通过双流卷积神经网络（CNN）设计来调查视频分类，直接从压缩的视频比特流中提取信息。我们的方法始于所有现代视频编解码器将输入帧划分为宏块（MB）的观察。我们证明，对压缩视频比特流内的MB运动向量（MV）信息的选择性访问也可以提供选择性的，运动自适应的MB像素解码（也称为MB纹理解码）。与传统的全帧解码和光流估计相比，这又允许以极高的速度推导时空视频活动区域。为了评估基于这样的活动数据的视频分类框架的准确性，我们独立地训练两个CNN架构的MB纹理和MV对应关系，然后融合他们的分数得出每个测试视频的最终分类。对两个标准数据集的评估表明，所提出的方法与文献中找到的最佳双流视频分类方法相比具有竞争性。同时：（i）基于CPU的实现我们的MV提取速度比基于GPU的光流方法快977倍; （ii）选择性解码比全帧解码快达12倍; （iii）我们提出的空间和时间CNN比云端运算成本低5到49倍的文献进行推理。

##### URL
[https://arxiv.org/abs/1710.05112](https://arxiv.org/abs/1710.05112)

##### PDF
[https://arxiv.org/pdf/1710.05112](https://arxiv.org/pdf/1710.05112)

