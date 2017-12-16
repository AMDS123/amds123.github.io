---
layout: post
title: "Cascaded Region-based Densely Connected Network for Event Detection: A Seismic Application"
date: 2017-11-29 04:15:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Relation
author: Yue Wu, Youzuo Lin, Zheng Zhou, David Chas Bolton, Ji Liu, Paul Johnson
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic event detection from time series signals has wide applications, such as abnormal event detection in video surveillance and event detection in geophysical data. Traditional detection methods detect events primarily by the use of similarity and correlation in data. Those methods can be inefficient and yield low accuracy. In recent years, because of the significantly increased computational power, machine learning techniques have revolutionized many science and engineering domains. In this study, we apply a deep-learning-based method to the detection of events from time series seismic signals. However, a direct adaptation of the similar ideas from 2D object detection to our problem faces two challenges. The first challenge is that the duration of earthquake event varies significantly; The other is that the proposals generated are temporally correlated. To address these challenges, we propose a novel cascaded region-based convolutional neural network to capture earthquake events in different sizes, while incorporating contextual information to enrich features for each individual proposal. To achieve a better generalization performance, we use densely connected blocks as the backbone of our network. Because of the fact that some positive events are not correctly annotated, we further formulate the detection problem as a learning-from-noise problem. To verify the performance of our detection methods, we employ our methods to seismic data generated from a bi-axial "earthquake machine" located at Rock Mechanics Laboratory, and we acquire labels with the help of experts. Through our numerical tests, we show that our novel detection techniques yield high accuracy. Therefore, our novel deep-learning-based detection methods can potentially be powerful tools for locating events from time series data in various applications.

##### Abstract (translated by Google)
时间序列信号的自动事件检测具有广泛的应用，如视频监控中的异常事件检测和地球物理数据中的事件检测。传统的检测方法主要通过使用数据中的相似性和相关性来检测事件。那些方法可能是低效率的并且产生低精度。近年来，由于计算能力的显着提高，机器学习技术已经彻底颠覆了许多科学和工程领域。在这项研究中，我们采用深度学习的方法来检测时间序列地震信号中的事件。然而，从二维物体检测的类似想法直接适应我们的问题面临两个挑战。第一个挑战是地震事件的持续时间差异很大，另一个是生成的提案是时间相关的。为了应对这些挑战，我们提出了一种新颖的基于区域的卷积神经网络来捕捉不同大小的地震事件，同时结合上下文信息来丰富每个提议的特征。为了获得更好的泛化性能，我们使用密集连接的块作为我们网络的骨干。由于一些正面事件没有被正确的注释，我们进一步将检测问题形成一个学习噪声问题。为了验证我们的检测方法的性能，我们使用我们的方法来处理岩石力学实验室的双轴“地震机器”产生的地震数据，并在专家的帮助下获得标签。通过我们的数值测试，我们发现我们的新型检测技术具有很高的准确性。因此，我们新颖的基于深度学习的检测方法可能成为用于从各种应用中的时间序列数据中定位事件的强大工具。

##### URL
[https://arxiv.org/abs/1709.07943](https://arxiv.org/abs/1709.07943)

##### PDF
[https://arxiv.org/pdf/1709.07943](https://arxiv.org/pdf/1709.07943)

