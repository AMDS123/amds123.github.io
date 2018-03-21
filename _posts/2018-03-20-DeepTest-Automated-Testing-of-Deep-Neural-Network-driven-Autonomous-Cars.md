---
layout: post
title: "DeepTest: Automated Testing of Deep-Neural-Network-driven Autonomous Cars"
date: 2018-03-20 06:10:24
categories: arXiv_AI
tags: arXiv_AI
author: Yuchi Tian, Kexin Pei, Suman Jana, Baishakhi Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Deep Neural Networks (DNNs) have led to the development of DNN-driven autonomous cars that, using sensors like camera, LiDAR, etc., can drive without any human intervention. Most major manufacturers including Tesla, GM, Ford, BMW, and Waymo/Google are working on building and testing different types of autonomous vehicles. The lawmakers of several US states including California, Texas, and New York have passed new legislation to fast-track the process of testing and deployment of autonomous vehicles on their roads. 
 However, despite their spectacular progress, DNNs, just like traditional software, often demonstrate incorrect or unexpected corner case behaviors that can lead to potentially fatal collisions. Several such real-world accidents involving autonomous cars have already happened including one which resulted in a fatality. Most existing testing techniques for DNN-driven vehicles are heavily dependent on the manual collection of test data under different driving conditions which become prohibitively expensive as the number of test conditions increases. 
 In this paper, we design, implement and evaluate DeepTest, a systematic testing tool for automatically detecting erroneous behaviors of DNN-driven vehicles that can potentially lead to fatal crashes. First, our tool is designed to automatically generated test cases leveraging real-world changes in driving conditions like rain, fog, lighting conditions, etc. DeepTest systematically explores different parts of the DNN logic by generating test inputs that maximize the numbers of activated neurons. DeepTest found thousands of erroneous behaviors under different realistic driving conditions (e.g., blurring, rain, fog, etc.) many of which lead to potentially fatal crashes in three top performing DNNs in the Udacity self-driving car challenge.

##### Abstract (translated by Google)
深度神经网络（DNNs）的最新进展促成了DNN驱动的自动驾驶汽车的发展，使用摄像头，LiDAR等传感器可以在没有任何人为干预的情况下驾驶。包括特斯拉，通用，福特，宝马和Waymo /谷歌在内的大多数主要制造商正致力于构建和测试不同类型的自动驾驶汽车。包括加利福尼亚州，德克萨斯州和纽约州在内的多个美国州的立法者已经通过了新的立法，以快速追踪道路上自动驾驶车辆的测试和部署过程。
 然而，尽管DNN取得了令人瞩目的进展，但就像传统软件一样，DNN经常表现出错误或意外的角落案例行为，这些行为可能导致潜在的致命冲突。涉及自动驾驶汽车的几起此类现实世界事故已经发生，其中包括导致死亡的事故。 DNN驱动车辆的大多数现有测试技术在很大程度上取决于在不同驾驶条件下手动收集测试数据，随着测试条件数量的增加，这些测试数据过于昂贵。
 在本文中，我们设计，实施和评估DeepTest，这是一种系统测试工具，可自动检测可能导致致命碰撞的DNN驾驶车辆的错误行为。首先，我们的工具旨在自动生成测试案例，以利用雨，雾，照明条件等驾驶条件的实际变化。DeepTest通过生成最大化激活的神经元数量的测试输入系统地探索DNN逻辑的不同部分。 DeepTest在不同的逼真驾驶条件下（例如，模糊，下雨，雾等等）发现了成千上万的错误行为，其中许多导致Udacity自驾车挑战中的三个顶级DNN中可能致命的车祸。

##### URL
[http://arxiv.org/abs/1708.08559](http://arxiv.org/abs/1708.08559)

##### PDF
[http://arxiv.org/pdf/1708.08559](http://arxiv.org/pdf/1708.08559)

