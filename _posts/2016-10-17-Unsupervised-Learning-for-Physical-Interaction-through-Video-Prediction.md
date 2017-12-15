---
layout: post
title: "Unsupervised Learning for Physical Interaction through Video Prediction"
date: 2016-10-17 20:09:56
categories: arXiv_CV
tags: arXiv_CV Prediction Quantitative
author: Chelsea Finn, Ian Goodfellow, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
A core challenge for an agent learning to interact with the world is to predict how its actions affect objects in its environment. Many existing methods for learning the dynamics of physical interactions require labeled object information. However, to scale real-world interaction learning to a variety of scenes and objects, acquiring labeled data becomes increasingly impractical. To learn about physical object motion without labels, we develop an action-conditioned video prediction model that explicitly models pixel motion, by predicting a distribution over pixel motion from previous frames. Because our model explicitly predicts motion, it is partially invariant to object appearance, enabling it to generalize to previously unseen objects. To explore video prediction for real-world interactive agents, we also introduce a dataset of 59,000 robot interactions involving pushing motions, including a test set with novel objects. In this dataset, accurate prediction of videos conditioned on the robot's future actions amounts to learning a "visual imagination" of different futures based on different courses of action. Our experiments show that our proposed method produces more accurate video predictions both quantitatively and qualitatively, when compared to prior methods.

##### Abstract (translated by Google)
学习与世界交互的代理人面临的核心挑战是预测其行为如何影响其环境中的对象。许多现有的学习物理交互动态的方法需要标记的对象信息。然而，为了将真实世界的交互学习扩展到各种场景和对象，获取标记数据变得越来越不切实际。为了了解没有标签的物体运动，我们开发了一个动作条件视频预测模型，通过预测前一帧像素运动的分布，明确地模拟像素运动。因为我们的模型明确地预测了运动，所以对象外观是部分不变的，使它能够推广到以前看不见的对象。为了探索真实世界交互代理的视频预测，我们还介绍了包含推动运动的59,000个机器人交互的数据集，其中包括具有新颖对象的测试集。在这个数据集中，准确预测机器人未来行动的视频，就等于根据不同的行动路线学习不同期货的“视觉想象力”。我们的实验表明，与先前的方法相比，我们所提出的方法在数量上和质量上产生更准确的视频预测。

##### URL
[https://arxiv.org/abs/1605.07157](https://arxiv.org/abs/1605.07157)

##### PDF
[https://arxiv.org/pdf/1605.07157](https://arxiv.org/pdf/1605.07157)

