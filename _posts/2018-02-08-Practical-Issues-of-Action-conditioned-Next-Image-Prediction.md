---
layout: post
title: "Practical Issues of Action-conditioned Next Image Prediction"
date: 2018-02-08 17:38:26
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Donglai Zhu, Hao Chen, Hengshuai Yao, Masoud Nosrati, Peyman Yadmellat, Yunfei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of action-conditioned image prediction is to predict the expected next frame given the current camera frame the robot observes and an action selected by the robot. We provide the first comparison of two recent popular models, especially for image prediction on cars. Our major finding is that action tiling encoding is the most important factor leading to the remarkable performance of the CDNA model. We present a light-weight model by action tiling encoding which has a single-decoder feedforward architecture same as [action_video_prediction_honglak]. On a real driving dataset, the CDNA model achieves ${0.3986} \times 10^{-3}$ MSE and ${0.9846}$ Structure SIMilarity (SSIM) with a network size of about {\bfseries ${12.6}$ million} parameters. With a small network of fewer than {\bfseries ${1}$ million} parameters, our new model achieves a comparable performance to CDNA at ${0.3613} \times 10^{-3}$ MSE and ${0.9633}$ SSIM. Our model requires less memory, is more computationally efficient and is advantageous to be used inside self-driving vehicles.

##### Abstract (translated by Google)
动作条件图像预测的问题是预测给定机器人观察的当前相机帧和机器人选择的动作的预期下一帧。我们提供了两个最近流行的模型的第一个比较，特别是对汽车的图像预测。我们的主要发现是行动拼贴编码是导致CDNA模型显着表现的最重要的因素。我们通过具有与[action_video_prediction_honglak]相同的单解码器前馈结构的动作平铺编码来呈现轻量级模型。在一个真正的驾驶数据集中，CDNA模型的网络规模达到了$ {0.3986} \ times 10 ^ { -  3} $ MSE和$ {0.9846} $结构相似性（SSIM），大约为{\ bfseries $ {12.6} }参数。通过一个少于{\ bfseries $ {1} $ million}个参数的小型网络，我们的新模型可以达到与CDNA相当的性能，即$ {0.3613} \ times 10 ^ { -  3} $ MSE和$ {0.9633} $ SSIM 。我们的模型需要更少的内存，计算效率更高，有利于在自驾车内使用。

##### URL
[http://arxiv.org/abs/1802.02975](http://arxiv.org/abs/1802.02975)

##### PDF
[http://arxiv.org/pdf/1802.02975](http://arxiv.org/pdf/1802.02975)

