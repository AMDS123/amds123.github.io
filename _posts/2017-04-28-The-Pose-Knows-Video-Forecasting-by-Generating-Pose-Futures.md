---
layout: post
title: "The Pose Knows: Video Forecasting by Generating Pose Futures"
date: 2017-04-28 19:46:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Prediction Quantitative Detection
author: Jacob Walker, Kenneth Marino, Abhinav Gupta, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
Current approaches in video forecasting attempt to generate videos directly in pixel space using Generative Adversarial Networks (GANs) or Variational Autoencoders (VAEs). However, since these approaches try to model all the structure and scene dynamics at once, in unconstrained settings they often generate uninterpretable results. Our insight is to model the forecasting problem at a higher level of abstraction. Specifically, we exploit human pose detectors as a free source of supervision and break the video forecasting problem into two discrete steps. First we explicitly model the high level structure of active objects in the scene---humans---and use a VAE to model the possible future movements of humans in the pose space. We then use the future poses generated as conditional information to a GAN to predict the future frames of the video in pixel space. By using the structured space of pose as an intermediate representation, we sidestep the problems that GANs have in generating video pixels directly. We show through quantitative and qualitative evaluation that our method outperforms state-of-the-art methods for video prediction.

##### Abstract (translated by Google)
视频预测中的当前方法尝试使用生成对抗网络（GAN）或变分自动编码器（VAE）直接在像素空间中生成视频。然而，由于这些方法试图模拟所有的结构和场景的动态一次，在不受限制的设置，他们往往产生不可解释的结果。我们的洞察力是在更高的抽象层次上对预测问题进行建模。具体而言，我们利用人体姿态检测器作为自由的监督来源，将视频预测问题分解为两个不连续的步骤。首先，我们明确地建模场景中活动对象的高层结构 - 人类 - 并使用VAE来模拟人类在姿势空间中可能的未来运动。然后，我们使用未来姿态作为条件信息生成GAN来预测未来的像素空间中的视频帧。通过使用姿态的结构空间作为中间表示，我们避开了GAN直接生成视频像素的问题。我们通过定性和定量评估显示，我们的方法胜过了最先进的视频预测方法。

##### URL
[https://arxiv.org/abs/1705.00053](https://arxiv.org/abs/1705.00053)

##### PDF
[https://arxiv.org/pdf/1705.00053](https://arxiv.org/pdf/1705.00053)

