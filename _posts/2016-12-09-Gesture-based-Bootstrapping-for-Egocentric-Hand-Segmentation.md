---
layout: post
title: "Gesture-based Bootstrapping for Egocentric Hand Segmentation"
date: 2016-12-09 01:49:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Face CNN Detection
author: Yubo Zhang, Vishnu Naresh Boddeti, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately identifying hands in images is a key sub-task for human activity understanding with wearable first-person point-of-view cameras. Traditional hand segmentation approaches rely on a large corpus of manually labeled data to generate robust hand detectors. However, these approaches still face challenges as the appearance of the hand varies greatly across users, tasks, environments or illumination conditions. A key observation in the case of many wearable applications and interfaces is that, it is only necessary to accurately detect the user's hands in a specific situational context. Based on this observation, we introduce an interactive approach to learn a person-specific hand segmentation model that does not require any manually labeled training data. Our approach proceeds in two steps, an interactive bootstrapping step for identifying moving hand regions, followed by learning a personalized user specific hand appearance model. Concretely, our approach uses two convolutional neural networks: (1) a gesture network that uses pre-defined motion information to detect the hand region; and (2) an appearance network that learns a person specific model of the hand region based on the output of the gesture network. During training, to make the appearance network robust to errors in the gesture network, the loss function of the former network incorporates the confidence of the gesture network while learning. Experiments demonstrate the robustness of our approach with an F1 score over 0.8 on all challenging datasets across a wide range of illumination and hand appearance variations, improving over a baseline approach by over 10%.

##### Abstract (translated by Google)
准确地识别图像中的手是用可穿戴的第一人称视角相机理解人类活动的关键子任务。传统的手分割方法依赖于大量的人工标记数据来生成鲁棒的手部检测器。然而，由于手的外观在用户，任务，环境或照明条件下变化很大，所以这些方法仍然面临挑战。在许多可穿戴应用和接口的情况下的关键观察是，仅在特定的情境中才能准确地检测用户的手。基于这一观察，我们介绍了一种交互式方法来学习不需要任何手动标记的训练数据的特定于人的手分割模型。我们的方法分两步进行：交互式引导步骤，用于识别移动的手区域，然后学习个性化的用户特定的手形模型。具体而言，我们的方法使用两个卷积神经网络：（1）使用预定义的运动信息来检测手区域的手势网络; （2）基于手势网络的输出来学习手区域的个人特定模型的外观网络。在训练过程中，为了使得外观网络对于手势网络中的错误具有鲁棒性，前一网络的丢失功能包含了学习时手势网络的置信度。实验证明，我们的方法在各种照明和手部外观变化的所有具有挑战性的数据集上的F1分数超过0.8的稳健性，比基线方法提高了超过10％。

##### URL
[https://arxiv.org/abs/1612.02889](https://arxiv.org/abs/1612.02889)

##### PDF
[https://arxiv.org/pdf/1612.02889](https://arxiv.org/pdf/1612.02889)

