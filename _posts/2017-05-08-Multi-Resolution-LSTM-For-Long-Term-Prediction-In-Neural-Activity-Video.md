---
layout: post
title: "Multi Resolution LSTM For Long Term Prediction In Neural Activity Video"
date: 2017-05-08 14:32:22
categories: arXiv_CV
tags: arXiv_CV Adversarial RNN Prediction
author: Yilin Song, Jonathan Viventi, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Epileptic seizures are caused by abnormal, overly syn- chronized, electrical activity in the brain. The abnor- mal electrical activity manifests as waves, propagating across the brain. Accurate prediction of the propagation velocity and direction of these waves could enable real- time responsive brain stimulation to suppress or prevent the seizures entirely. However, this problem is very chal- lenging because the algorithm must be able to predict the neural signals in a sufficiently long time horizon to allow enough time for medical intervention. We consider how to accomplish long term prediction using a LSTM network. To alleviate the vanishing gradient problem, we propose two encoder-decoder-predictor structures, both using multi-resolution representation. The novel LSTM structure with multi-resolution layers could significantly outperform the single-resolution benchmark with similar number of parameters. To overcome the blurring effect associated with video prediction in the pixel domain using standard mean square error (MSE) loss, we use energy- based adversarial training to improve the long-term pre- diction. We demonstrate and analyze how a discriminative model with an encoder-decoder structure using 3D CNN model improves long term prediction.

##### Abstract (translated by Google)
癫痫发作是由异常，过度同步，大脑中的电活动引起的。异常的电活动表现为波浪，在大脑中传播。准确预测这些波的传播速度和方向可以使实时响应性脑刺激完全抑制或防止癫痫发作。然而，这个问题是非常有挑战性的，因为该算法必须能够在足够长的时间范围内预测神经信号，从而有足够的时间进行医学干预。我们考虑如何使用LSTM网络来实现长期预测。为了缓解消失梯度问题，我们提出了两种编解码器 - 预测器结构，都使用多分辨率表示。具有多分辨率层的新型LSTM结构可以显着地胜过具有相似参数的单分辨率基准。为了克服使用标准均方误差（MSE）丢失的像素域中的视频预测相关的模糊效应，我们使用基于能量的对抗训练来改善长期预测。我们展示和分析了如何使用3D CNN模型的编码器 - 解码器结构的判别模型改善长期预测。

##### URL
[https://arxiv.org/abs/1705.02893](https://arxiv.org/abs/1705.02893)

##### PDF
[https://arxiv.org/pdf/1705.02893](https://arxiv.org/pdf/1705.02893)

