---
layout: post
title: "Hallucinating robots: Inferring obstacle distances from partial laser measurements"
date: 2018-05-31 06:38:07
categories: arXiv_RO
tags: arXiv_RO Quantitative
author: Jens Lundell, Francesco Verdoja, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
Many mobile robots rely on 2D laser scanners for localization, mapping, and navigation. However, those sensors are unable to correctly provide distance to obstacles such as glass panels and tables whose actual occupancy is invisible at the height the sensor is measuring. In this work, instead of estimating the distance to obstacles from richer sensor readings such as 3D lasers or RGBD sensors, we present a method to estimate the distance directly from raw 2D laser data. To learn a mapping from raw 2D laser distances to obstacle distances we frame the problem as a learning task and train a neural network formed as an autoencoder. A novel configuration of network hyperparameters is proposed for the task at hand and is quantitatively validated on a test set. Finally, we qualitatively demonstrate in real time on a Care-O-bot 4 that the trained network can successfully infer obstacle distances from partial 2D laser readings.

##### Abstract (translated by Google)
许多移动机器人依靠二维激光扫描仪进行定位，绘图和导航。但是，这些传感器无法正确地提供与障碍物的距离，例如玻璃面板和桌子，这些障碍物在传感器测量的高度处实际占用不可见。在这项工作中，我们提出了一种直接从原始2D激光数据中估算距离的方法，而不是估算更加丰富的传感器读数（如3D激光或RGBD传感器）的障碍距离。为了学习从原始2D激光距离到障碍距离的映射，我们将该问题作为学习任务来构建，并训练形成为自编码器的神经网络。针对手头的任务提出了一种新的网络超参数配置，并在测试集上进行了定量验证。最后，我们定性地在Care-O-bot 4上展示了训练好的网络可以成功地从部分2D激光读数中推断障碍物距离。

##### URL
[http://arxiv.org/abs/1805.12338](http://arxiv.org/abs/1805.12338)

##### PDF
[http://arxiv.org/pdf/1805.12338](http://arxiv.org/pdf/1805.12338)

