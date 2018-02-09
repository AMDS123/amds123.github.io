---
layout: post
title: "Effective Quantization Approaches for Recurrent Neural Networks"
date: 2018-02-07 19:43:01
categories: arXiv_CV
tags: arXiv_CV Sentiment CNN RNN Deep_Learning Prediction
author: Md Zahangir Alom, Adam T Moody, Naoya Maruyama, Brian C Van Essen, Tarek M. Taha
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning, and in particular Recurrent Neural Networks (RNN) have shown superior accuracy in a large variety of tasks including machine translation, language understanding, and movie frame generation. However, these deep learning approaches are very expensive in terms of computation. In most cases, Graphic Processing Units (GPUs) are in used for large scale implementations. Meanwhile, energy efficient RNN approaches are proposed for deploying solutions on special purpose hardware including Field Programming Gate Arrays (FPGAs) and mobile platforms. In this paper, we propose an effective quantization approach for Recurrent Neural Networks (RNN) techniques including Long Short Term Memory (LSTM), Gated Recurrent Units (GRU), and Convolutional Long Short Term Memory (ConvLSTM). We have implemented different quantization methods including Binary Connect {-1, 1}, Ternary Connect {-1, 0, 1}, and Quaternary Connect {-1, -0.5, 0.5, 1}. These proposed approaches are evaluated on different datasets for sentiment analysis on IMDB and video frame predictions on the moving MNIST dataset. The experimental results are compared against the full precision versions of the LSTM, GRU, and ConvLSTM. They show promising results for both sentiment analysis and video frame prediction.

##### Abstract (translated by Google)
深度学习，尤其是递归神经网络（RNN）在包括机器翻译，语言理解和电影帧生成在内的各种任务中已经表现出优异的准确性。然而，这些深度学习方法在计算方面是非常昂贵的。在大多数情况下，图形处理单元（GPU）用于大规模实施。同时，针对包括现场编程门阵列（FPGAs）和移动平台在内的专用硬件部署解决方案，提出了节能RNN方法。在本文中，我们提出了递归神经网络（RNN）技术的一种有效的量化方法，包括长期短期记忆（LSTM），门控循环单元（GRU）和卷积长期短期记忆（ConvLSTM）。我们实现了不同的量化方法，包括二元连接{-1,1}，三元连接{-1,0,1}和四元连接{-1，-0.5,0.5,1}。这些建议的方法在不同的数据集上评估IMDB的情感分析和移动的MNIST数据集上的视频帧预测。将实验结果与LSTM，GRU和ConvLSTM的全精密版本进行比较。它们对于情感分析和视频帧预测都显示出有希望的结果。

##### URL
[http://arxiv.org/abs/1802.02615](http://arxiv.org/abs/1802.02615)

##### PDF
[http://arxiv.org/pdf/1802.02615](http://arxiv.org/pdf/1802.02615)

