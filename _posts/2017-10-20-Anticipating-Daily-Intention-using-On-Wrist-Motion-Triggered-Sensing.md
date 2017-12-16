---
layout: post
title: "Anticipating Daily Intention using On-Wrist Motion Triggered Sensing"
date: 2017-10-20 10:39:58
categories: arXiv_CV
tags: arXiv_CV RNN
author: Tz-Ying Wu, Ting-An Chien, Cheng-Sheng Chan, Chan-Wei Hu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Anticipating human intention by observing one's actions has many applications. For instance, picking up a cellphone, then a charger (actions) implies that one wants to charge the cellphone (intention). By anticipating the intention, an intelligent system can guide the user to the closest power outlet. We propose an on-wrist motion triggered sensing system for anticipating daily intentions, where the on-wrist sensors help us to persistently observe one's actions. The core of the system is a novel Recurrent Neural Network (RNN) and Policy Network (PN), where the RNN encodes visual and motion observation to anticipate intention, and the PN parsimoniously triggers the process of visual observation to reduce computation requirement. We jointly trained the whole network using policy gradient and cross-entropy loss. To evaluate, we collect the first daily "intention" dataset consisting of 2379 videos with 34 intentions and 164 unique action sequences. Our method achieves 92.68%, 90.85%, 97.56% accuracy on three users while processing only 29% of the visual observation on average.

##### Abstract (translated by Google)
通过观察自己的行为预测人的意图有很多应用。例如，拿起手机，然后充电器（动作）意味着要给手机充电（意图）。通过预测意图，智能系统可以引导用户到最近的电源插座。我们提出了一个手腕上的运动触发传感系统来预测日常意图，手腕上的传感器帮助我们持续地观察自己的行为。该系统的核心是一个新颖的递归神经网络（RNN）和策略网络（PN），RNN通过对视觉和运动观察进行编码来预测意图，并且通过简洁地触发视觉过程来降低计算量。我们利用策略梯度和交叉熵损失来联合训练整个网络。为了评估，我们收集了第一个每天“意向”数据集，包括2379个视频，34个意图和164个独特的动作序列。我们的方法对三个用户的准确度达到了92.68％，90.85％，97.56％，平均只处理了29％的视觉效果。

##### URL
[https://arxiv.org/abs/1710.07477](https://arxiv.org/abs/1710.07477)

##### PDF
[https://arxiv.org/pdf/1710.07477](https://arxiv.org/pdf/1710.07477)

