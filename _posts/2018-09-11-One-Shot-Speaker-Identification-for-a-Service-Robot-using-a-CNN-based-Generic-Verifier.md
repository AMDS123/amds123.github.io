---
layout: post
title: "One-Shot Speaker Identification for a Service Robot using a CNN-based Generic Verifier"
date: 2018-09-11 19:16:07
categories: arXiv_SD
tags: arXiv_SD CNN
author: Ivette V&#xe9;lez (1), Caleb Rascon (1), Gibr&#xe1;n Fuentes-Pineda (1) ((1) Instituto de Investigaciones en Matem&#xe1;ticas Aplicadas y en Sistemas (IIMAS), Universidad Nacional Aut&#xf3;noma de M&#xe9;xico (UNAM), Mexico.)
mathjax: true
---

* content
{:toc}

##### Abstract
In service robotics, there is an interest to identify the user by voice alone. However, in application scenarios where a service robot acts as a waiter or a store clerk, new users are expected to enter the environment frequently. Typically, speaker identification models need to be retrained when this occurs, which can take an impractical amount of time. In this paper, a new approach for speaker identification through verification has been developed using a Siamese Convolutional Neural Network architecture (SCNN), where it learns to generically verify if two audio signals are from the same speaker. By having an external database of recorded audio of the users, identification is carried out by verifying the speech input with each of its entries. If new users are encountered, it is only required to add their recorded audio to the external database to be able to be identified, without retraining. The system was evaluated in four different aspects: the performance of the verifier, the performance of the system as a classifier using clean audio, its speed, and its accuracy in real-life settings. Its performance in conjunction with its one-shot-learning capabilities, makes the proposed system a viable alternative for speaker identification for service robots.

##### Abstract (translated by Google)
在服务机器人中，有兴趣仅通过语音识别用户。然而，在服务机器人充当服务员或店员的应用场景中，期望新用户经常进入环境。通常，当发生这种情况时，需要重新训练说话者识别模型，这可能花费不切实际的时间量。在本文中，使用暹罗卷积神经网络架构（SCNN）开发了一种通过验证进行说话人识别的新方法，在该方法中，它学习一般性地验证两个音频信号是否来自同一个扬声器。通过具有用户的记录音频的外部数据库，通过用其每个条目验证语音输入来执行识别。如果遇到新用户，则只需要将他们录制的音频添加到外部数据库即可进行识别，而无需重新训练。系统在四个不同方面进行了评估：验证器的性能，系统作为使用干净音频的分类器的性能，速度以及在现实环境中的准确性。其性能与其一次性学习功能相结合，使得所提出的系统成为服务机器人的说话人识别的可行替代方案。

##### URL
[http://arxiv.org/abs/1809.04115](http://arxiv.org/abs/1809.04115)

##### PDF
[http://arxiv.org/pdf/1809.04115](http://arxiv.org/pdf/1809.04115)

