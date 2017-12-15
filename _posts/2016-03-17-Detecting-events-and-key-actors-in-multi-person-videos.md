---
layout: post
title: "Detecting events and key actors in multi-person videos"
date: 2016-03-17 00:02:03
categories: arXiv_CV
tags: arXiv_CV Attention RNN Classification Detection Recognition
author: Vignesh Ramanathan, Jonathan Huang, Sami Abu-El-Haija, Alexander Gorban, Kevin Murphy, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-person event recognition is a challenging task, often with many people active in the scene but only a small subset contributing to an actual event. In this paper, we propose a model which learns to detect events in such videos while automatically "attending" to the people responsible for the event. Our model does not use explicit annotations regarding who or where those people are during training and testing. In particular, we track people in videos and use a recurrent neural network (RNN) to represent the track features. We learn time-varying attention weights to combine these features at each time-instant. The attended features are then processed using another RNN for event detection/classification. Since most video datasets with multiple people are restricted to a small number of videos, we also collected a new basketball dataset comprising 257 basketball games with 14K event annotations corresponding to 11 event classes. Our model outperforms state-of-the-art methods for both event classification and detection on this new dataset. Additionally, we show that the attention mechanism is able to consistently localize the relevant players.

##### Abstract (translated by Google)
多人事件识别是一个具有挑战性的任务，往往有许多人在场景中活动，但只有一小部分人为实际事件做出贡献。在本文中，我们提出了一个模型，学习如何检测这些视频中的事件，同时自动“参加”负责该事件的人员。我们的模型不会在训练和测试期间使用明确的注释来说明这些人是谁或在哪里。特别是，我们跟踪视频中的人，并使用循环神经网络（RNN）来表示轨道特征。我们学习时变关注权重，以便在每个时刻将这些特征组合起来。然后使用另一个RNN处理出席的功能以进行事件检测/分类。由于大多数多人视频数据集仅限于少量视频，因此我们还收集了一个新的篮球数据集，其中包含257个14K事件注释对应于11个事件类别的篮球比赛。我们的模型在这个新的数据集上胜过了最先进的事件分类和检测方法。此外，我们表明，注意机制是能够一致地本地化有关球员。

##### URL
[https://arxiv.org/abs/1511.02917](https://arxiv.org/abs/1511.02917)

##### PDF
[https://arxiv.org/pdf/1511.02917](https://arxiv.org/pdf/1511.02917)

