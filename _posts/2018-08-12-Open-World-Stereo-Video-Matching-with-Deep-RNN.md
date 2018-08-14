---
layout: post
title: "Open-World Stereo Video Matching with Deep RNN"
date: 2018-08-12 15:41:54
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning
author: Yiran Zhong, Hongdong Li, Yuchao Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning based stereo matching methods have shown great successes and achieved top scores across different benchmarks. However, like most data-driven methods, existing deep stereo matching networks suffer from some well-known drawbacks such as requiring large amount of labeled training data, and that their performances are fundamentally limited by the generalization ability. In this paper, we propose a novel Recurrent Neural Network (RNN) that takes a continuous (possibly previously unseen) stereo video as input, and directly predicts a depth-map at each frame without a pre-training process, and without the need of ground-truth depth-maps as supervision. Thanks to the recurrent nature (provided by two convolutional-LSTM blocks), our network is able to memorize and learn from its past experiences, and modify its inner parameters (network weights) to adapt to previously unseen or unfamiliar environments. This suggests a remarkable generalization ability of the net, making it applicable in an {\em open world} setting. Our method works robustly with changes in scene content, image statistics, and lighting and season conditions {\em etc}. By extensive experiments, we demonstrate that the proposed method seamlessly adapts between different scenarios. Equally important, in terms of the stereo matching accuracy, it outperforms state-of-the-art deep stereo approaches on standard benchmark datasets such as KITTI and Middlebury stereo.

##### Abstract (translated by Google)
基于深度学习的立体匹配方法已经取得了巨大的成功，并在不同的基准测试中取得了最高分。然而，与大多数数据驱动方法一样，现有的深立体匹配网络存在一些众所周知的缺点，例如需要大量标记的训练数据，并且它们的性能基本上受到泛化能力的限制。在本文中，我们提出了一种新颖的递归神经网络（RNN），它将连续的（可能是以前看不见的）立体视频作为输入，并直接预测每帧的深度图，无需预训练过程，也无需地面实况深度图作为监督。由于经常性（由两个卷积LSTM块提供），我们的网络能够记忆并学习其过去的经验，并修改其内部参数（网络权重）以适应以前看不见或不熟悉的环境。这表明网络的显着泛化能力，使其适用于{\ em开放世界}设置。我们的方法可以很好地适应场景内容，图像统计，照明和季节条件{\ em等}的变化。通过大量实验，我们证明了所提出的方法在不同场景之间无缝适应。同样重要的是，就立体声匹配精度而言，它在标准基准数据集（如KITTI和Middlebury立体声）上优于最先进的深立体声方法。

##### URL
[http://arxiv.org/abs/1808.03959](http://arxiv.org/abs/1808.03959)

##### PDF
[http://arxiv.org/pdf/1808.03959](http://arxiv.org/pdf/1808.03959)

