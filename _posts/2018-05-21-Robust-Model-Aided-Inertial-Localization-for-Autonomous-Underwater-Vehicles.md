---
layout: post
title: "Robust Model-Aided Inertial Localization for Autonomous Underwater Vehicles"
date: 2018-05-21 12:17:15
categories: arXiv_RO
tags: arXiv_RO
author: Sascha Arnold, Lashika Medagoda
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a manifold based Unscented Kalman Filter that applies a novel strategy for inertial, model-aiding and Acoustic Doppler Current Profiler (ADCP) measurement incorporation. The filter is capable of observing and utilizing the Earth rotation for heading estimation with a tactical grade IMU, and utilizes information from the vehicle model during DVL drop outs. The drag and thrust model-aiding accounts for the correlated nature of vehicle model parameter error by applying them as states in the filter. ADCP-aiding provides further information for the model-aiding in the case of DVL bottom-lock loss. Additionally this work was implemented using the MTK and ROCK framework in C++, and is capable of running in real-time on computing available on the FlatFish AUV. The IMU biases are estimated in a fully coupled approach in the navigation filter. Heading convergence is shown on a real-world data set. Further experiments show that the filter is capable of consistent positioning, and data denial validates the method for DVL dropouts due to very low or high altitude scenarios.

##### Abstract (translated by Google)
本文提出了一种基于流形的Unscented卡尔曼滤波器，该滤波器应用了惯性，模型辅助和Acoustic Doppler Current Profiler（ADCP）测量并入的新策略。该过滤器能够观测和利用地球自转以用于战术等级IMU的航向估算，并在DVL丢失期间利用来自车辆模型的信息。阻力和推力模型帮助将车​​辆模型参数误差的相关性质应用于滤波器中作为状态。 ADCP辅助为DVL底部锁定损失情况下的模型提供了进一步的信息。此外，这项工作是使用C ++中的MTK和ROCK框架实现的，并且能够实时运行在FlatFish AUV上的计算机上。 IMU偏差在导航滤波器中以完全耦合的方式进行估计。标题融合显示在真实世界的数据集上。进一步的实验表明，滤波器能够一致定位，并且数据拒绝验证了由于非常低或高海拔情况导致的DVL丢失的方法。

##### URL
[http://arxiv.org/abs/1805.08011](http://arxiv.org/abs/1805.08011)

##### PDF
[http://arxiv.org/pdf/1805.08011](http://arxiv.org/pdf/1805.08011)

