---
layout: post
title: "Learning Long-range Perception using Self-Supervision from Short-Range Sensors and Odometry"
date: 2018-09-19 14:16:03
categories: arXiv_RO
tags: arXiv_RO CNN Prediction Quantitative
author: Mirko Nava, Jerome Guzzi, R. Omar Chavez-Garcia, Luca M. Gambardella, Alessandro Giusti
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a general self-supervised approach to predict the future outputs of a short-range sensor (such as a proximity sensor) given the current outputs of a long-range sensor (such as a camera); we assume that the former is directly related to some piece of information to be perceived (such as the presence of an obstacle in a given position), whereas the latter is information-rich but hard to interpret directly. We instantiate and implement the approach on a small mobile robot to detect obstacles at various distances using the video stream of the robot's forward-pointing camera, by training a convolutional neural network on automatically-acquired datasets. We quantitatively evaluate the quality of the predictions on unseen scenarios, qualitatively evaluate robustness to different operating conditions, and demonstrate usage as the sole input of an obstacle-avoidance controller.

##### Abstract (translated by Google)
我们引入了一种通用的自我监督方法，根据远程传感器（如摄像机）的电流输出，预测短程传感器（如接近传感器）的未来输出;我们假设前者与某些要被感知的信息直接相关（例如在给定位置存在障碍物），而后者信息丰富但难以直接解释。我们通过在自动获取的数据集上训练卷积神经网络，在小型移动机器人上实例化并实施该方法，使用机器人前向摄像机的视频流检测各种距离的障碍物。我们定量评估未见情景预测的质量，定性评估不同运行条件的稳健性，并证明使用是避障控制器的唯一输入。

##### URL
[http://arxiv.org/abs/1809.07207](http://arxiv.org/abs/1809.07207)

##### PDF
[http://arxiv.org/pdf/1809.07207](http://arxiv.org/pdf/1809.07207)

