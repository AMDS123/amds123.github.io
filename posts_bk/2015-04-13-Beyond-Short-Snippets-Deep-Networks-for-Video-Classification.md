---
layout: post
title: "Beyond Short Snippets: Deep Networks for Video Classification"
date: 2015-04-13 19:44:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Video_Classification RNN Classification Detection Recognition
author: Joe Yue-Hei Ng, Matthew Hausknecht, Sudheendra Vijayanarasimhan, Oriol Vinyals, Rajat Monga, George Toderici
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have been extensively applied for image recognition problems giving state-of-the-art results on recognition, detection, segmentation and retrieval. In this work we propose and evaluate several deep neural network architectures to combine image information across a video over longer time periods than previously attempted. We propose two methods capable of handling full length videos. The first method explores various convolutional temporal feature pooling architectures, examining the various design choices which need to be made when adapting a CNN for this task. The second proposed method explicitly models the video as an ordered sequence of frames. For this purpose we employ a recurrent neural network that uses Long Short-Term Memory (LSTM) cells which are connected to the output of the underlying CNN. Our best networks exhibit significant performance improvements over previously published results on the Sports 1 million dataset (73.1% vs. 60.9%) and the UCF-101 datasets with (88.6% vs. 88.0%) and without additional optical flow information (82.6% vs. 72.8%).

##### Abstract (translated by Google)
卷积神经网络（CNN）已被广泛应用于图像识别问题，在识别，检测，分割和检索方面提供了最先进的结果。在这项工作中，我们提出并评估了几个深度的神经网络架构，以在比以前尝试更长的时间段内跨越视频组合图像信息。我们提出了两种能够处理全长视频的方法。第一种方法探讨了各种卷积时间特征池结构，研究了在为此任务调整CNN时需要做出的各种设计选择。所提出的第二种方法明确地将视频模拟为帧的有序序列。为此，我们使用一个循环的神经网络，使用连接到底层CNN输出的长时间短期记忆（LSTM）单元。我们最好的网络比之前公布的运动100万个数据集（73.1％对60.9％）和UCF-101数据集（88.6％对88.0％）显示出显着的性能改善，没有额外的光学流量信息（82.6％vs 。72.8％）。

##### URL
[https://arxiv.org/abs/1503.08909](https://arxiv.org/abs/1503.08909)

##### PDF
[https://arxiv.org/pdf/1503.08909](https://arxiv.org/pdf/1503.08909)

