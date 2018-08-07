---
layout: post
title: "Personalized Exposure Control Using Adaptive Metering and Reinforcement Learning"
date: 2018-08-05 08:05:27
categories: arXiv_CV
tags: arXiv_CV Review Reinforcement_Learning CNN Prediction
author: Huan Yang, Baoyuan Wang, Noranart Vesdapunt, Minyi Guo, Sing Bing Kang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a reinforcement learning approach for real-time exposure control of a mobile camera that is personalizable. Our approach is based on Markov Decision Process (MDP). In the camera viewfinder or live preview mode, given the current frame, our system predicts the change in exposure so as to optimize the trade-off among image quality, fast convergence, and minimal temporal oscillation. We model the exposure prediction function as a fully convolutional neural network that can be trained through Gaussian policy gradient in an end-to-end fashion. As a result, our system can associate scene semantics with exposure values; it can also be extended to personalize the exposure adjustments for a user and device. We improve the learning performance by incorporating an adaptive metering module that links semantics with exposure. This adaptive metering module generalizes the conventional spot or matrix metering techniques. We validate our system using the MIT FiveK and our own datasets captured using iPhone 7 and Google Pixel. Experimental results show that our system exhibits stable real-time behavior while improving visual quality compared to what is achieved through native camera control.

##### Abstract (translated by Google)
我们提出了一种强化学习方法，用于可个性化的移动相机的实时曝光控制。我们的方法基于马尔可夫决策过程（MDP）。在相机取景器或实时预览模式中，给定当前帧，我们的系统预测曝光的变化，以优化图像质量，快速收敛和最小时间振荡之间的权衡。我们将曝光预测函数建模为完全卷积神经网络，可以通过端对端方式通过高斯策略梯度进行训练。因此，我们的系统可以将场景语义与曝光值相关联;它还可以扩展到个性化用户和设备的曝光调整。我们通过结合将语义与曝光相关联的自适应计量模块来提高学习成绩。该自适应计量模块概括了传统的点或矩阵计量技术。我们使用MIT FiveK和我们自己使用iPhone 7和Google Pixel捕获的数据集来验证我们的系统。实验结果表明，与通过本机摄像机控制实现的系统相比，我们的系统具有稳定的实时行为，同时提高了视觉质量。

##### URL
[http://arxiv.org/abs/1803.02269](http://arxiv.org/abs/1803.02269)

##### PDF
[http://arxiv.org/pdf/1803.02269](http://arxiv.org/pdf/1803.02269)

