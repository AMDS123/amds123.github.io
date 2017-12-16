---
layout: post
title: "DDD17: End-To-End DAVIS Driving Dataset"
date: 2017-11-04 16:19:56
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Jonathan Binas, Daniel Neil, Shih-Chii Liu, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Event cameras, such as dynamic vision sensors (DVS), and dynamic and active-pixel vision sensors (DAVIS) can supplement other autonomous driving sensors by providing a concurrent stream of standard active pixel sensor (APS) images and DVS temporal contrast events. The APS stream is a sequence of standard grayscale global-shutter image sensor frames. The DVS events represent brightness changes occurring at a particular moment, with a jitter of about a millisecond under most lighting conditions. They have a dynamic range of >120 dB and effective frame rates >1 kHz at data rates comparable to 30 fps (frames/second) image sensors. To overcome some of the limitations of current image acquisition technology, we investigate in this work the use of the combined DVS and APS streams in end-to-end driving applications. The dataset DDD17 accompanying this paper is the first open dataset of annotated DAVIS driving recordings. DDD17 has over 12 h of a 346x260 pixel DAVIS sensor recording highway and city driving in daytime, evening, night, dry and wet weather conditions, along with vehicle speed, GPS position, driver steering, throttle, and brake captured from the car's on-board diagnostics interface. As an example application, we performed a preliminary end-to-end learning study of using a convolutional neural network that is trained to predict the instantaneous steering angle from DVS and APS visual data.

##### Abstract (translated by Google)
诸如动​​态视觉传感器（DVS）以及动态和有源像素视觉传感器（DAVIS）的事件相机可以通过提供标准有源像素传感器（APS）图像和DVS时间对比度事件的并发流来补充其他自主驾驶传感器。 APS流是一系列标准灰度全局快门图像传感器帧。 DVS事件表示在特定时刻发生的亮度变化，在大多数照明条件下具有约1毫秒的抖动。它们的动态范围> 120 dB，有效帧速率> 1 kHz，数据速率可与30 fps（帧/秒）的图像传感器相媲美。为了克服当前图像采集技术的一些局限性，我们研究了在端到端驱动应用中使用组合的DVS和APS流。伴随本文的数据集DDD17是第一个注释DAVIS驾驶记录的开放数据集。 DDD17拥有超过12小时的346x260像素DAVIS传感器，记录白天，傍晚，夜晚，干燥和潮湿的天气条件下的高速公路和城市驾驶情况，以及车辆在车上的车速，GPS位置，驾驶员转向，油门和刹车，板卡诊断接口。作为一个应用实例，我们进行了一个初步的端到端的学习研究，使用卷积神经网络来训练预测DVS和APS视觉数据的瞬时转向角度。

##### URL
[https://arxiv.org/abs/1711.01458](https://arxiv.org/abs/1711.01458)

##### PDF
[https://arxiv.org/pdf/1711.01458](https://arxiv.org/pdf/1711.01458)

