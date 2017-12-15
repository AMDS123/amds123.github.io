---
layout: post
title: "Action Recognition with Joint Attention on Multi-Level Deep Features"
date: 2016-07-09 01:25:24
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Tracking Action_Recognition CNN RNN Recognition
author: Jialin Wu, Gu Wang, Wukui Yang, Xiangyang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep supervised neural network for the task of action recognition in videos, which implicitly takes advantage of visual tracking and shares the robustness of both deep Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN). In our method, a multi-branch model is proposed to suppress noise from background jitters. Specifically, we firstly extract multi-level deep features from deep CNNs and feed them into 3d-convolutional network. After that we feed those feature cubes into our novel joint LSTM module to predict labels and to generate attention regularization. We evaluate our model on two challenging datasets: UCF101 and HMDB51. The results show that our model achieves the state-of-art by only using convolutional features.

##### Abstract (translated by Google)
针对视频中的动作识别任务，提出了一种新的深度监督神经网络，隐式地利用了视觉追踪，并分享了深度卷积神经网络（CNN）和递归神经网络（RNN）的鲁棒性。在我们的方法中，提出了多分支模型来抑制背景抖动的噪声。具体来说，我们首先从深度CNN中提取多层次的深度特征，并将其提供给三维卷积网络。之后，我们将这些特征立方体送入我们的新型联合LSTM模块中，以预测标签并产生注意力正则化。我们在两个具有挑战性的数据集上评估我们的模型：UCF101和HMDB51。结果表明，我们的模型通过仅使用卷积特征来实现最先进的技术。

##### URL
[https://arxiv.org/abs/1607.02556](https://arxiv.org/abs/1607.02556)

##### PDF
[https://arxiv.org/pdf/1607.02556](https://arxiv.org/pdf/1607.02556)

