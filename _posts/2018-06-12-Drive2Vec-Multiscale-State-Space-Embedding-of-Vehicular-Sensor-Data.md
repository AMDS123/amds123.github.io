---
layout: post
title: "Drive2Vec: Multiscale State-Space Embedding of Vehicular Sensor Data"
date: 2018-06-12 23:19:54
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Deep_Learning
author: David Hallac, Suvrat Bhooshan, Michael Chen, Kacem Abida, Rok Sosic, Jure Leskovec
mathjax: true
---

* content
{:toc}

##### Abstract
With automobiles becoming increasingly reliant on sensors to perform various driving tasks, it is important to encode the relevant CAN bus sensor data in a way that captures the general state of the vehicle in a compact form. In this paper, we develop a deep learning-based method, called Drive2Vec, for embedding such sensor data in a low-dimensional yet actionable form. Our method is based on stacked gated recurrent units (GRUs). It accepts a short interval of automobile sensor data as input and computes a low-dimensional representation of that data, which can then be used to accurately solve a range of tasks. With this representation, we (1) predict the exact values of the sensors in the short term (up to three seconds in the future), (2) forecast the long-term average values of these same sensors, (3) infer additional contextual information that is not encoded in the data, including the identity of the driver behind the wheel, and (4) build a knowledge base that can be used to auto-label data and identify risky states. We evaluate our approach on a dataset collected by Audi, which equipped a fleet of test vehicles with data loggers to store all sensor readings on 2,098 hours of driving on real roads. We show in several experiments that our method outperforms other baselines by up to 90%, and we further demonstrate how these embeddings of sensor data can be used to solve a variety of real-world automotive applications.

##### Abstract (translated by Google)
随着汽车越来越依赖于传感器来执行各种驾驶任务，重要的是以紧凑的形式捕捉车辆的一般状态来编码相关的CAN总线传感器数据。在本文中，我们开发了一种名为Drive2Vec的基于深度学习的方法，用于以低维且可操作的形式嵌入这些传感器数据。我们的方法基于堆叠门控循环单元（GRU）。它接受汽车传感器数据的短时间间隔作为输入并计算该数据的低维表示，然后可以用它来精确地解决一系列任务。 （2）预测这些相同传感器的长期平均值，（3）推断附加的上下文关系信息中没有编码的数据，包括车轮后面驱动程序的身份，以及（4）建立可用于自动标记数据和识别风险状态的知识库。我们评估了奥迪收集的数据集的方法，该数据集配备了一组测试车辆和数据记录器，以存储在真实道路上驾驶2098小时的所有传感器读数。我们在几个实验中展示了我们的方法比其他基线高出90％，并且我们进一步演示了如何使用这些传感器数据嵌入来解决各种现实世界的汽车应用。

##### URL
[http://arxiv.org/abs/1806.04795](http://arxiv.org/abs/1806.04795)

##### PDF
[http://arxiv.org/pdf/1806.04795](http://arxiv.org/pdf/1806.04795)

