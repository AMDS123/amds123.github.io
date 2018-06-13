---
layout: post
title: "Learning to Decompose and Disentangle Representations for Video Prediction"
date: 2018-06-11 18:12:59
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Jun-Ting Hsieh, Bingbin Liu, De-An Huang, Li Fei-Fei, Juan Carlos Niebles
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to predict future video frames given a sequence of input frames. Despite large amounts of video data, this remains a challenging task because of the high-dimensionality of video frames. We address this challenge by proposing the Decompositional Disentangled Predictive Auto-Encoder (DDPAE), a framework that combines structured probabilistic models and deep networks to automatically (i) decompose the high-dimensional video that we aim to predict into components, and (ii) disentangle each component to have low-dimensional temporal dynamics that are easier to predict. Crucially, with an appropriately specified generative model of video frames, our DDPAE is able to learn both the latent decomposition and disentanglement without explicit supervision. For the Moving MNIST dataset, we show that DDPAE is able to recover the underlying components (individual digits) and disentanglement (appearance and location) as we would intuitively do. We further demonstrate that DDPAE can be applied to the Bouncing Balls dataset involving complex interactions between multiple objects to predict the video frame directly from the pixels and recover physical states without explicit supervision.

##### Abstract (translated by Google)
我们的目标是在给定一系列输入帧的情况下预测未来的视频帧。尽管有大量的视频数据，但由于视频帧的高维度，这仍然是一项具有挑战性的任务。我们通过提出分解无失真预测自动编码器（DDPAE）来解决这一难题，该解决方案结合了结构化概率模型和深度网络，以自动（i）将我们旨在预测的高维视频分解成分量，以及（ii）分解每个组件以具有更容易预测的低维时间动态。至关重要的是，通过适当指定的视频帧生成模型，我们的DDPAE能够在没有明确监督的情况下学习潜在分解和解缠。对于Moving MNIST数据集，我们显示DDPAE能够像我们直觉那样恢复基本组件（单个数字）和解开（外观和位置）。我们进一步证明DDPAE可以应用于涉及多个物体之间复杂相互作用的Bouncing Balls数据集，以直接从像素预测视频帧，并在没有明确监督的情况下恢复物理状态。

##### URL
[http://arxiv.org/abs/1806.04166](http://arxiv.org/abs/1806.04166)

##### PDF
[http://arxiv.org/pdf/1806.04166](http://arxiv.org/pdf/1806.04166)

