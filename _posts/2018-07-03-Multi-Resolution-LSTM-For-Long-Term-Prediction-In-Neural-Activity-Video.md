---
layout: post
title: "Multi Resolution LSTM For Long Term Prediction In Neural Activity Video"
date: 2018-07-03 02:50:09
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
癫痫发作是由大脑中异常，过度同步的电活动引起的。异常的电活动表现为波浪，在大脑中传播。准确预测这些波的传播速度和方向可以实现实时响应性脑刺激，从而完全抑制或预防癫痫发作。然而，这个问题非常具有挑战性，因为该算法必须能够在足够长的时间范围内预测神经信号，以便有足够的时间进行医疗干预。我们考虑如何使用LSTM网络完成长期预测。为了减轻消失梯度问题，我们提出了两种编码器 - 解码器 - 预测器结构，两者都使用多分辨率表示。具有多分辨率层的新型LSTM结构可以明显优于具有相似数量参数的单分辨率基准。为了克服与使用标准均方误差（MSE）损失的像素域中的视频预测相关联的模糊效应，我们使用基于能量的对抗训练来改善长期预测。我们演示并分析了使用3D CNN模型的具有编码器 - 解码器结构的判别模型如何改进长期预测。

##### URL
[http://arxiv.org/abs/1705.02893](http://arxiv.org/abs/1705.02893)

##### PDF
[http://arxiv.org/pdf/1705.02893](http://arxiv.org/pdf/1705.02893)

