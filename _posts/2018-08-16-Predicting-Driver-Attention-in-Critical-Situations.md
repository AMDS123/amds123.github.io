---
layout: post
title: "Predicting Driver Attention in Critical Situations"
date: 2018-08-16 05:41:26
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Prediction
author: Ye Xia, Danqing Zhang, Jinkyu Kim, Ken Nakayama, Karl Zipser, David Whitney
mathjax: true
---

* content
{:toc}

##### Abstract
Robust driver attention prediction for critical situations is a challenging computer vision problem, yet essential for autonomous driving. Because critical driving moments are so rare, collecting enough data for these situations is difficult with the conventional in-car data collection protocol---tracking eye movements during driving. Here, we first propose a new in-lab driver attention collection protocol and introduce a new driver attention dataset built upon braking event videos selected from a large-scale, crowd-sourced driving video dataset. We further propose Human Weighted Sampling (HWS) method, which uses human gaze behavior to identify crucial frames of a driving dataset and weights them heavily during model training. With our dataset and HWS, we built a driver attention prediction model that outperforms the state-of-the-art and demonstrates sophisticated behaviors, like attending to crossing pedestrians but not giving false alarms to pedestrians safely walking on the sidewalk. Its prediction results are nearly indistinguishable from ground-truth to humans. Although only being trained with our in-lab attention data, the model also predicts in-car driver attention data of routine driving with state-of-the-art accuracy. This result not only demonstrates the performance of our model but also proves the validity and usefulness of our dataset and data collection protocol.

##### Abstract (translated by Google)
针对危急情况的强大的驾驶员注意力预测是一个具有挑战性的计算机视觉问题，但对于自动驾由于关键的驾驶时刻非常罕见，因此采用传统的车内数据采集协议（在驾驶过程中跟踪眼球运动）很难为这些情况收集足够的数据。在这里，我们首先提出一个新的实验室内驾驶员注意力收集协议，并引入一个新的驾驶员注意力数据集，该数据集建立在从大规模，众包驱动视频数据集中选择的制动事件视频的基础上。我们进一步提出人类加权采样（HWS）方法，该方法使用人类凝视行为来识别驾驶数据集的关键帧并在模型训练期间对它们进行大量加权。通过我们的数据集和HWS，我们建立了一个优于现有技术的驾驶员注意力预测模型，并展示了复杂的行为，例如过道行人，但没有给行人在人行道上安全行走提供误报。它的预测结果几乎与地面真相无法区分。虽然只是通过我们的实验室注意力数据进行培训，但该模型还可以通过最先进的精度预测日常驾驶的车内驾驶员注意力数据。该结果不仅证明了我们模型的性能，而且证明了我们的数据集和数据收集协议的有效性和实用性。

##### URL
[http://arxiv.org/abs/1711.06406](http://arxiv.org/abs/1711.06406)

##### PDF
[http://arxiv.org/pdf/1711.06406](http://arxiv.org/pdf/1711.06406)

