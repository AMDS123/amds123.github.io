---
layout: post
title: "Am I a Baller? Basketball Performance Assessment from First-Person Videos"
date: 2017-08-02 15:10:27
categories: arXiv_CV
tags: arXiv_CV Salient CNN RNN
author: Gedas Bertasius, Hyun Soo Park, Stella X. Yu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to assess a basketball player's performance from his/her first-person video. A key challenge lies in the fact that the evaluation metric is highly subjective and specific to a particular evaluator. We leverage the first-person camera to address this challenge. The spatiotemporal visual semantics provided by a first-person view allows us to reason about the camera wearer's actions while he/she is participating in an unscripted basketball game. Our method takes a player's first-person video and provides a player's performance measure that is specific to an evaluator's preference. To achieve this goal, we first use a convolutional LSTM network to detect atomic basketball events from first-person videos. Our network's ability to zoom-in to the salient regions addresses the issue of a severe camera wearer's head movement in first-person videos. The detected atomic events are then passed through the Gaussian mixtures to construct a highly non-linear visual spatiotemporal basketball assessment feature. Finally, we use this feature to learn a basketball assessment model from pairs of labeled first-person basketball videos, for which a basketball expert indicates, which of the two players is better. We demonstrate that despite not knowing the basketball evaluator's criterion, our model learns to accurately assess the players in real-world games. Furthermore, our model can also discover basketball events that contribute positively and negatively to a player's performance.

##### Abstract (translated by Google)
本文介绍了一种从他/她的第一人称视频中评估篮球运动员表现的方法。一个关键的挑战在于评估指标对于特定的评估者来说是非常主观和具体的。我们利用第一人称相机来应对这一挑战。由第一人称视角提供的时空视觉语义允许我们在他/她参加无脚本的篮球游戏时推断相机佩戴者的行为。我们的方法需要玩家的第一人称视频，并提供玩家的评估者偏好特定的表现度量。为了实现这个目标，我们首先使用卷积LSTM网络来检测来自第一人称视频的原子篮球事件。我们的网络能够放大显示区域，解决了第一人称视频中严重摄像头佩戴者头部移动的问题。然后检测到的原子事件通过高斯混合，构建高度非线性的视觉时空篮球评估特征。最后，我们使用这个特征来从一对篮球专家指出的标记的第一人称篮球视频中学习一个篮球评估模型，这两个球员哪一个更好。我们证明，尽管不知道篮球评估者的标准，我们的模型学习准确地评估真实世界的比赛中的球员。此外，我们的模型还可以发现对玩家表现有积极和消极影响的篮球事件。

##### URL
[https://arxiv.org/abs/1611.05365](https://arxiv.org/abs/1611.05365)

##### PDF
[https://arxiv.org/pdf/1611.05365](https://arxiv.org/pdf/1611.05365)

