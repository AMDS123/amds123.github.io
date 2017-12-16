---
layout: post
title: "Fully Context-Aware Video Prediction"
date: 2017-10-23 21:55:12
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN RNN Prediction
author: Wonmin Byeon, Qin Wang, Rupesh Kumar Srivastava, Petros Koumoutsakos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new neural network design for unsupervised learning through video prediction. Current video prediction models based on convolutional networks, recurrent networks, and their combinations often result in blurry predictions. Recent work has attempted to address this issue with techniques like separation of background and foreground modeling, motion flow learning, or adversarial training. We highlight that a contributing factor for this problem is the failure of current architectures to fully capture relevant past information for accurately predicting the future. To address this shortcoming we introduce a fully context-aware architecture, which captures the entire available past context for each pixel using Parallel Multi-Dimensional LSTM units and aggregates it using context blending blocks. Our model is simple, efficient and directly applicable to high resolution video frames. It yields state-of-the-art performance for next step prediction on three challenging real-world video datasets: Human 3.6M, Caltech Pedestrian, and UCF-101 and produces sharp predictions of high visual quality.

##### Abstract (translated by Google)
本文提出了一种通过视频预测进行无监督学习的神经网络设计方法。基于卷积网络，递归网络及其组合的当前视频预测模型经常导致模糊的预测。最近的工作试图用背景和前景建模，运动流学习或对抗训练等技术来解决这个问题。我们强调，这个问题的一个促成因素是当前体系结构未能充分捕获相关的过去信息以准确地预测未来。为了解决这个缺点，我们引入了完全上下文感知的架构，该架构使用并行多维LSTM单元捕获每个像素的全部可用过去上下文，并使用上下文混合块对其进行聚合。我们的模型简单，高效并直接适用于高分辨率视频帧。它为三个具有挑战性的真实世界视频数据集（人类3.6M，加州理工行人和UCF-101）提供了最先进的下一步预测性能，并对高视觉质量产生了尖锐的预测。

##### URL
[https://arxiv.org/abs/1710.08518](https://arxiv.org/abs/1710.08518)

##### PDF
[https://arxiv.org/pdf/1710.08518](https://arxiv.org/pdf/1710.08518)

