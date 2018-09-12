---
layout: post
title: "Long-Term Occupancy Grid Prediction Using Recurrent Neural Networks"
date: 2018-09-11 10:21:39
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Relation
author: Marcel Schreiber, Stefan Hoermann, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the long-term prediction of scene evolution in a complex downtown scenario for automated driving based on Lidar grid fusion and recurrent neural networks (RNNs). A bird's eye view of the scene, including occupancy and velocity, is fed as a sequence to a RNN which is trained to predict future occupancy. The nature of prediction allows generation of multiple hours of training data without the need of manual labeling. Thus, the training strategy and loss function is designed for long sequences of real-world data (unbalanced, continuously changing situations, false labels, etc.). The deep CNN architecture comprises convolutional long short-term memories (ConvLSTMs) to separate static from dynamic regions and to predict dynamic objects in future frames. Novel recurrent skip connections show the ability to predict small occluded objects, i.e. pedestrians, and occluded static regions. Spatio-temporal correlations between grid cells are exploited to predict multimodal future paths and interactions between objects. Experiments also quantify improvements to our previous network, a Monte Carlo approach, and literature.

##### Abstract (translated by Google)
我们在基于激光雷达网格融合和递归神经网络（RNN）的自动驾驶的复杂街市场景中解决了场景演化的长期预测。鸟瞰的场景（包括占用率和速度）作为序列馈送到RNN，RNN经过训练以预测未来的占用情况。预测的性质允许生成多个小时的训练数据，而无需手动标记。因此，训练策略和损失函数是针对长序列的真实数据（不平衡，不断变化的情况，虚假标签等）而设计的。深度CNN架构包括卷积长短期存储器（ConvLSTM），用于将静态区域与动态区域分离，并预测未来帧中的动态对象。新颖的重复跳过连接显示了预测小的被遮挡物体（即行人）和被遮挡的静态区域的能力。利用网格单元之间的时空相关性来预测多模态未来路径和对象之间的相互作用。实验还量化了对我们以前的网络，蒙特卡罗方法和文献的改进。

##### URL
[http://arxiv.org/abs/1809.03782](http://arxiv.org/abs/1809.03782)

##### PDF
[http://arxiv.org/pdf/1809.03782](http://arxiv.org/pdf/1809.03782)

