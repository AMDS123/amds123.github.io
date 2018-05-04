---
layout: post
title: "Deep Speech Denoising with Vector Space Projections"
date: 2018-04-27 20:08:38
categories: arXiv_AI
tags: arXiv_AI Sparse Embedding Inference
author: Jeff Hetherly, Paul Gamble, Maria Barrios, Cory Stephenson, Karl Ni
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an algorithm to denoise speakers from a single microphone in the presence of non-stationary and dynamic noise. Our approach is inspired by the recent success of neural network models separating speakers from other speakers and singers from instrumental accompaniment. Unlike prior art, we leverage embedding spaces produced with source-contrastive estimation, a technique derived from negative sampling techniques in natural language processing, while simultaneously obtaining a continuous inference mask. Our embedding space directly optimizes for the discrimination of speaker and noise by jointly modeling their characteristics. This space is generalizable in that it is not speaker or noise specific and is capable of denoising speech even if the model has not seen the speaker in the training set. Parameters are trained with dual objectives: one that promotes a selective bandpass filter that eliminates noise at time-frequency positions that exceed signal power, and another that proportionally splits time-frequency content between signal and noise. We compare to state of the art algorithms as well as traditional sparse non-negative matrix factorization solutions. The resulting algorithm avoids severe computational burden by providing a more intuitive and easily optimized approach, while achieving competitive accuracy.

##### Abstract (translated by Google)
我们提出了一种算法来消除来自单个麦克风的扬声器在存在非平稳和动态噪声的情况下。我们的方法受到最近成功的神经网络模型的启发，这些模型将扬声器与其他演讲者和歌手从器乐伴奏中分离出来。与现有技术不同，我们利用源自对比估计产生的嵌入空间，这是一种从自然语言处理中的负抽样技术中获得的技术，同时获得连续的推理掩码。我们的嵌入空间通过联合建模它们的特性来直接优化扬声器和噪声的区分。这个空间是可普遍的，因为它不是说话者或噪声特定的，并且即使模型没有看到训练集中的说话者也能够去噪语音。参数采用双重目标进行训练：一种方法是推广一种选择性带通滤波器，消除时频位置处的噪声超过信号功率，另一种按比例分配信号与噪声之间的时频内容。我们比较最先进的算法以及传统的稀疏非负矩阵分解解决方案。由此产生的算法通过提供更直观，更容易优化的方法避免了严重的计算负担，同时实现了竞争的准确性。

##### URL
[https://arxiv.org/abs/1804.10669](https://arxiv.org/abs/1804.10669)

##### PDF
[https://arxiv.org/pdf/1804.10669](https://arxiv.org/pdf/1804.10669)

