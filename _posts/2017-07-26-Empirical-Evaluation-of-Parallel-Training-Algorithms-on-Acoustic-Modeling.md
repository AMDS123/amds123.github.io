---
layout: post
title: "Empirical Evaluation of Parallel Training Algorithms on Acoustic Modeling"
date: 2017-07-26 06:29:54
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition CNN Deep_Learning Gradient_Descent Recognition
author: Wenpeng Li, BinBin Zhang, Lei Xie, Dong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models (DLMs) are state-of-the-art techniques in speech recognition. However, training good DLMs can be time consuming especially for production-size models and corpora. Although several parallel training algorithms have been proposed to improve training efficiency, there is no clear guidance on which one to choose for the task in hand due to lack of systematic and fair comparison among them. In this paper we aim at filling this gap by comparing four popular parallel training algorithms in speech recognition, namely asynchronous stochastic gradient descent (ASGD), blockwise model-update filtering (BMUF), bulk synchronous parallel (BSP) and elastic averaging stochastic gradient descent (EASGD), on 1000-hour LibriSpeech corpora using feed-forward deep neural networks (DNNs) and convolutional, long short-term memory, DNNs (CLDNNs). Based on our experiments, we recommend using BMUF as the top choice to train acoustic models since it is most stable, scales well with number of GPUs, can achieve reproducible results, and in many cases even outperforms single-GPU SGD. ASGD can be used as a substitute in some cases.

##### Abstract (translated by Google)
深度学习模型（DLM）是语音识别中的最新技术。但是，训练良好的DLM可能会耗费大量时间，特别是对于生产规模的模型和语料库。尽管已经提出了几种并行训练算法来提高训练效率，但是由于缺乏系统和公正的比较，对于手头的任务选择哪一种没有明确的指导。在本文中，我们旨在通过比较语音识别中的四种流行的并行训练算法，即异步随机梯度下降（ASGD），块状模型更新滤波（BMUF），批量同步并行（BSP）和弹性平均随机梯度下降（EASGD），使用前馈深层神经网络（DNNs）和卷积，长期短期记忆，DNNs（CLDNNs），1000小时的LibriSpeech语料库。基于我们的实验，我们推荐使用BMUF作为训练声学模型的首选，因为它最稳定，可以与GPU数量成正比，可以获得可重现的结果，甚至在许多情况下甚至胜过单GPU SGD。 ASGD可以在某些情况下用作替代品。

##### URL
[https://arxiv.org/abs/1703.05880](https://arxiv.org/abs/1703.05880)

##### PDF
[https://arxiv.org/pdf/1703.05880](https://arxiv.org/pdf/1703.05880)

