---
layout: post
title: "Learning a Bias Correction for Lidar-only Motion Estimation"
date: 2018-01-15 07:05:32
categories: arXiv_RO
tags: arXiv_RO
author: Tim Y. Tang, David J. Yoon, Fran&#xe7;ois Pomerleau, Timothy D. Barfoot
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel technique to correct for bias in a classical estimator using a learning approach. We apply a learned bias correction to a lidar-only motion estimation pipeline. Our technique trains a Gaussian process (GP) regression model using data with ground truth. The inputs to the model are high-level features derived from the geometry of the point-clouds, and the outputs are the predicted biases between poses computed by the estimator and the ground truth. The predicted biases are applied as a correction to the poses computed by the estimator. 
 Our technique is evaluated on over 50km of lidar data, which includes the KITTI odometry benchmark and lidar datasets collected around the University of Toronto campus. After applying the learned bias correction, we obtained significant improvements to lidar odometry in all datasets tested. We achieved around 10% reduction in errors on all datasets from an already accurate lidar odometry algorithm, at the expense of only less than 1% increase in computational cost at run-time.

##### Abstract (translated by Google)
本文提出了一种新颖的技术来纠正经典估计中的偏见使用学习的方法。我们将学习的偏差校正应用于仅有激光雷达的运动估计管线。我们的技术使用具有基本事实的数据训练高斯过程（GP）回归模型。模型的输入是从点云的几何结构导出的高级特征，而输出是由估计器计算出的姿态和地面事实之间的预测偏差。预测的偏差被用作对由估计器计算的姿势的校正。
 我们的技术在超过50公里的激光雷达数据上进行了评估，其中包括多伦多大学校园周围收集的KITTI测距基准和激光雷达数据集。在应用学习偏差校正之后，我们在所有测试的数据集中获得了激光雷达测距的显着改进。从已经精确的激光雷达测距法算法中，我们实现了所有数据集误差约10％的降低，但运行时计算成本仅增加不到1％。

##### URL
[http://arxiv.org/abs/1801.04678](http://arxiv.org/abs/1801.04678)

##### PDF
[http://arxiv.org/pdf/1801.04678](http://arxiv.org/pdf/1801.04678)

