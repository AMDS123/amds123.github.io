---
layout: post
title: "LSTM Pose Machines"
date: 2017-12-18 09:56:45
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN RNN Prediction Relation
author: Yue Luo, Jimmy Ren, Zhouxia Wang, Wenxiu Sun, Jinshan Pan, Jianbo Liu, Jiahao Pang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We observed that recent state-of-the-art results on single image human pose estimation were achieved by multi-stage Convolution Neural Networks (CNN). Notwithstanding the superior performance on static images, the application of these models on videos is not only computationally intensive, it also suffers from performance degeneration and flicking. Such suboptimal results are mainly attributed to the inability of imposing sequential geometric consistency, handling severe image quality degradation (e.g. motion blur and occlusion) as well as the inability of capturing the temporal correlation among video frames. In this paper, we proposed a novel recurrent network to tackle these problems. We showed that if we were to impose the weight sharing scheme to the multi-stage CNN, it could be re-written as a Recurrent Neural Network (RNN). This property decouples the relationship among multiple network stages and results in significantly faster speed in invoking the network for videos. It also enables the adoption of Long Short-Term Memory (LSTM) units between video frames. We found such memory augmented RNN is very effective in imposing geometric consistency among frames. It also well handles input quality degradation in videos while successfully stabilizes the sequential outputs. The experiments showed that our approach significantly outperformed current state-of-the-art methods on two large scale video pose estimation benchmarks. We also explored the memory cells inside the LSTM and provided insights on why such mechanism would benefit the prediction for video-based pose estimations.

##### Abstract (translated by Google)
我们观察到最近在单幅图像人体姿态估计方面的最新成果是通过多级卷积神经网络（CNN）实现的。尽管静态图像具有优越的性能，但这些模型在视频上的应用不仅计算量大，而且还受到性能退化和轻拂的影响。这样的次优结果主要归因于不能施加顺序的几何一致性，处理严重的图像质量劣化（例如运动模糊和遮挡）以及不能捕获视频帧之间的时间相关性。在本文中，我们提出了一个新颖的循环网络来解决这些问题。我们表明，如果我们将权重分配方案强加给多级CNN，它可以被重写为递归神经网络（RNN）。该属性将多个网络阶段之间的关系解耦，并且以调用视频网络的速度显着加快。它还能够在视频帧之间采用长时间短期记忆（LSTM）单元。我们发现这种记忆增强的RNN在强化帧间的几何一致性方面非常有效。它也很好地处理了视频输入质量的下降，同时成功稳定了顺序输出。实验表明，我们的方法在两个大型视频姿态估计基准上显着优于当前最先进的方法。我们还探索了LSTM内部的存储单元，并提供了有关为什么这种机制将有利于基于视频的姿态估计预测的见解。

##### URL
[http://arxiv.org/abs/1712.06316](http://arxiv.org/abs/1712.06316)

##### PDF
[http://arxiv.org/pdf/1712.06316](http://arxiv.org/pdf/1712.06316)

