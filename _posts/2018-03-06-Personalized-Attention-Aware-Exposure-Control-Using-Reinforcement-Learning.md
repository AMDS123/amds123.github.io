---
layout: post
title: "Personalized Attention-Aware Exposure Control Using Reinforcement Learning"
date: 2018-03-06 16:00:54
categories: arXiv_CV
tags: arXiv_CV Review Attention Reinforcement_Learning CNN Prediction
author: Huan Yang, Baoyuan Wang, Noranart Vesdapunt, Minyi Guo, Sing Bing Kang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a reinforcement learning approach for real-time exposure control of a mobile camera that is personalizable. Our approach is based on Markov Decision Process (MDP). In the camera viewfinder or live preview mode, given the current frame, our system predicts the change in exposure so as to optimize the trade-off among image quality, fast convergence, and minimal temporal oscillation. We model the exposure prediction function as a fully convolutional neural network that can be trained through Gaussian policy gradient in an end-to-end fashion. As a result, our system can associate scene semantics with exposure values; it can also be extended to personalize the exposure adjustments for a user and device. We improve the learning performance by incorporating an attention module that links semantics with exposure. This attention module generalizes the conventional spot or matrix metering techniques. We validate our system using the MIT FiveK and our own datasets captured using iPhone 7 and Google Pixel. Experimental results show that our system exhibits stable real-time behavior while improving visual quality compared to what is achieved through native camera control.

##### Abstract (translated by Google)
我们提出了一种强化学习方法，用于实时曝光控制个性化的移动相机。我们的方法基于马尔可夫决策过程（MDP）。在相机取景器或实时预览模式下，在给定当前帧的情况下，我们的系统会预测曝光的变化，从而优化图像质量，快速收敛和最小时间振荡之间的折衷。我们将暴露预测函数建模为完全卷积神经网络，该网络可以通过高斯策略梯度以端到端方式进行训练。因此，我们的系统可以将场景语义与曝光值相关联;它还可以扩展为个性化用户和设备的曝光调整。我们通过引入将语义与暴露联系起来的注意模块来提高学习效果。这个注意模块概括了传统的点测量或矩阵测量技术。我们使用MIT FiveK和使用iPhone 7和Google Pixel捕获的我们自己的数据集来验证我们的系统。实验结果表明，与通过本机相机控制实现的相比，我们的系统具有稳定的实时行为，同时提高了视觉质量。

##### URL
[http://arxiv.org/abs/1803.02269](http://arxiv.org/abs/1803.02269)

##### PDF
[http://arxiv.org/pdf/1803.02269](http://arxiv.org/pdf/1803.02269)

