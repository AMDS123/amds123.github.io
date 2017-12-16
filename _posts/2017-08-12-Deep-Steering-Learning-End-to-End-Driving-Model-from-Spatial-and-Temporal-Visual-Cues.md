---
layout: post
title: "Deep Steering: Learning End-to-End Driving Model from Spatial and Temporal Visual Cues"
date: 2017-08-12 17:18:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection RNN Prediction Quantitative Detection
author: Lu Chi, Yadong Mu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, autonomous driving algorithms using low-cost vehicle-mounted cameras have attracted increasing endeavors from both academia and industry. There are multiple fronts to these endeavors, including object detection on roads, 3-D reconstruction etc., but in this work we focus on a vision-based model that directly maps raw input images to steering angles using deep networks. This represents a nascent research topic in computer vision. The technical contributions of this work are three-fold. First, the model is learned and evaluated on real human driving videos that are time-synchronized with other vehicle sensors. This differs from many prior models trained from synthetic data in racing games. Second, state-of-the-art models, such as PilotNet, mostly predict the wheel angles independently on each video frame, which contradicts common understanding of driving as a stateful process. Instead, our proposed model strikes a combination of spatial and temporal cues, jointly investigating instantaneous monocular camera observations and vehicle's historical states. This is in practice accomplished by inserting carefully-designed recurrent units (e.g., LSTM and Conv-LSTM) at proper network layers. Third, to facilitate the interpretability of the learned model, we utilize a visual back-propagation scheme for discovering and visualizing image regions crucially influencing the final steering prediction. Our experimental study is based on about 6 hours of human driving data provided by Udacity. Comprehensive quantitative evaluations demonstrate the effectiveness and robustness of our model, even under scenarios like drastic lighting changes and abrupt turning. The comparison with other state-of-the-art models clearly reveals its superior performance in predicting the due wheel angle for a self-driving car.

##### Abstract (translated by Google)
近年来，使用低成本车载摄像头的自主驾驶算法已经引起了学术界和工业界的越来越多的努力。这些工作有多个方面，包括道路上的物体​​检测，三维重建等，但是在这项工作中，我们关注的是基于视觉的模型，它使用深度网络将原始输入图像直接映射到转向角。这代表了计算机视觉领域一个新兴的研究课题。这项工作的技术贡献是三重的。首先，在与其他车辆传感器时间同步的真人驾驶视频上学习和评估模型。这与许多赛车游戏合成数据训练的模型不同。其次，最先进的模型，比如PilotNet，主要是在每个视频帧上独立预测车轮角度，这与驾驶作为一个有状态过程的共同理解相矛盾。相反，我们提出的模型将空间和时间线索结合起来，共同研究瞬时单目相机观测和车辆的历史状态。这实际上是通过在适当的网络层插入精心设计的循环单元（例如，LSTM和Conv-LSTM）来实现的。第三，为了促进学习模型的可解释性，我们利用视觉反向传播方案来发现和可视化影响最终转向预测的图像区域。我们的实验研究基于Udacity提供的大约6小时的人类驾驶数据。全面的定量评估证明了我们的模型的有效性和鲁棒性，即使在剧烈的光照变化和突然转向的情况下。与其他最先进的车型的比较清楚地表明，它在预测自行驾驶车辆的正确的车轮角度方面具有优越的性能。

##### URL
[https://arxiv.org/abs/1708.03798](https://arxiv.org/abs/1708.03798)

##### PDF
[https://arxiv.org/pdf/1708.03798](https://arxiv.org/pdf/1708.03798)

