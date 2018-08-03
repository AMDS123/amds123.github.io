---
layout: post
title: "A Learning-Based Framework for Two-Dimensional Vehicle Maneuver Prediction over V2V Networks"
date: 2018-08-01 19:12:22
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Hossein Nourkhiz Mahjoub, Amin Tahmasbi-Sarvestani, Hadi Kazemi, Yaser P. Fallah
mathjax: true
---

* content
{:toc}

##### Abstract
Situational awareness in vehicular networks could be substantially improved utilizing reliable trajectory prediction methods. More precise situational awareness, in turn, results in notably better performance of critical safety applications, such as Forward Collision Warning (FCW), as well as comfort applications like Cooperative Adaptive Cruise Control (CACC). Therefore, vehicle trajectory prediction problem needs to be deeply investigated in order to come up with an end to end framework with enough precision required by the safety applications' controllers. This problem has been tackled in the literature using different methods. However, machine learning, which is a promising and emerging field with remarkable potential for time series prediction, has not been explored enough for this purpose. In this paper, a two-layer neural network-based system is developed which predicts the future values of vehicle parameters, such as velocity, acceleration, and yaw rate, in the first layer and then predicts the two-dimensional, i.e. longitudinal and lateral, trajectory points based on the first layer's outputs. The performance of the proposed framework has been evaluated in realistic cut-in scenarios from Safety Pilot Model Deployment (SPMD) dataset and the results show a noticeable improvement in the prediction accuracy in comparison with the kinematics model which is the dominant employed model by the automotive industry. Both ideal and nonideal communication circumstances have been investigated for our system evaluation. For non-ideal case, an estimation step is included in the framework before the parameter prediction block to handle the drawbacks of packet drops or sensor failures and reconstruct the time series of vehicle parameters at a desirable frequency.

##### Abstract (translated by Google)
利用可靠的轨迹预测方法可以显着改善车辆网络中的情境感知。反过来，更精确的态势感知可以显着提高关键安全应用的性能，例如前方碰撞警告（FCW），以及协同自适应巡航控制（CACC）等舒适应用。因此，需要深入研究车辆轨迹预测问题，以便提出具有安全应用程序控制器所需的足够精度的端到端框架。在文献中使用不同的方法解决了这个问题。然而，机器学习是一个有前途的新兴领域，具有显着的时间序列预测潜力，但尚未被充分研究用于此目的。在本文中，开发了一个基于双层神经网络的系统，该系统预测第一层中车辆参数的未来值，例如速度，加速度和偏航率，然后预测二维，即纵向和横向，轨迹点基于第一层的输出。所提出的框架的性能已经在安全飞行员模型部署（SPMD）数据集的现实切入情景中进行了评估，结果表明，与运动学模型相比，预测精度有显着提高，而运动学模型是汽车的主要应用模型。行业。我们的系统评估已经研究了理想和非理想的通信环境。对于非理想情况，在参数预测块之前的框架中包括估计步骤，以处理分组丢失或传感器故障的缺点，并以期望的频率重构车辆参数的时间序列。

##### URL
[http://arxiv.org/abs/1808.00516](http://arxiv.org/abs/1808.00516)

##### PDF
[http://arxiv.org/pdf/1808.00516](http://arxiv.org/pdf/1808.00516)

