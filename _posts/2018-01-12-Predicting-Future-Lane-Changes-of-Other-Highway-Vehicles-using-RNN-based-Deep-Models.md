---
layout: post
title: "Predicting Future Lane Changes of Other Highway Vehicles using RNN-based Deep Models"
date: 2018-01-12 22:16:05
categories: arXiv_RO
tags: arXiv_RO RNN Prediction
author: Sajan Patel, Brent Griffin, Kristofer Kusano, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
In the event of sensor failure, it is necessary for autonomous vehicles to safely execute emergency maneuvers while avoiding other vehicles on the road. In order to accomplish this, the sensor-failed vehicle must predict the future semantic behaviors of other drivers, such as lane changes, as well as their future trajectories given a small window of past sensor observations. We address the first issue of semantic behavior prediction in this paper, by introducing a prediction framework that leverages the power of recurrent neural networks (RNNs) and graphical models. Our prediction goal is to predict the future categorical driving intent, for lane changes, of neighboring vehicles up to three seconds into the future given as little as a one-second window of past LIDAR, GPS, inertial, and map data. 
 We collect real-world data containing over 500,000 samples of highway driving using an autonomous Toyota vehicle. We propose a pair of models that leverage RNNs: first, a monolithic RNN model that tries to directly map inputs to future behavior through a long-short-term-memory network. Second, we propose a composite RNN model by adopting the methodology of Structural Recurrent Neural Networks (RNNs) to learn factor functions and take advantage of both the high-level structure of graphical models and the sequence modeling power of RNNs, which we expect to afford more transparent modeling and activity than the monolithic RNN. To demonstrate our approach, we validate our models using authentic interstate highway driving to predict the future lane change maneuvers of other vehicles neighboring our autonomous vehicle. We find that both RNN models outperform baselines, and they outperform each other in certain conditions.

##### Abstract (translated by Google)
在发生传感器故障的情况下，自主车辆必须安全地执行紧急操作，同时避开路上的其他车辆。为了做到这一点，传感器故障的车辆必须预测其他驾驶员未来的语义行为，例如车道变化，以及在过去的传感器观察的小窗口中的未来轨迹。本文通过引入一个利用递归神经网络（RNN）和图形模型的预测框架来解决语义行为预测的第一个问题。我们的预测目标是预测将来三秒钟的相邻车辆的未来分类驾驶意图，车道变化，只要过去的激光雷达，GPS，惯性和地图数据的一秒窗口。
 我们采用自动丰田车辆收集包含超过500,000个高速公路样本的实际数据。我们提出了一对利用RNNs的模型：首先是一个单一的RNN模型，试图通过一个长期的短期记忆网络直接将输入映射到未来的行为。其次，本文提出了一种复合RNN模型，采用结构递归神经网络（RNN）的方法学习因子函数，并利用图形模型的高层结构和RNN的序列建模能力，比单片RNN更透明的建模和活动。为了证明我们的方法，我们使用真实的州际公路驾驶来验证我们的模型，以预测邻近我们的自主车辆的其他车辆的未来车道变换机动。我们发现两个RNN模型都比基线要好，在一定的条件下，它们的表现都超越对方。

##### URL
[http://arxiv.org/abs/1801.04340](http://arxiv.org/abs/1801.04340)

##### PDF
[http://arxiv.org/pdf/1801.04340](http://arxiv.org/pdf/1801.04340)

