---
layout: post
title: "Adversarial Training for Adverse Conditions: Robust Metric Localisation using Appearance Transfer"
date: 2018-03-09 00:45:08
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Sparse Detection Recognition
author: Horia Porav, Will Maddern, Paul Newman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method of improving visual place recognition and metric localisation under very strong appear- ance change. We learn an invertable generator that can trans- form the conditions of images, e.g. from day to night, summer to winter etc. This image transforming filter is explicitly designed to aid and abet feature-matching using a new loss based on SURF detector and dense descriptor maps. A network is trained to output synthetic images optimised for feature matching given only an input RGB image, and these generated images are used to localize the robot against a previously built map using traditional sparse matching approaches. We benchmark our results using multiple traversals of the Oxford RobotCar Dataset over a year-long period, using one traversal as a map and the other to localise. We show that this method significantly improves place recognition and localisation under changing and adverse conditions, while reducing the number of mapping runs needed to successfully achieve reliable localisation.

##### Abstract (translated by Google)
我们提出了一种在非常强烈的外观变化下改善视觉位置识别和度量定位的方法。我们学习了一个可以转换图像条件的可逆转发生器，例如从白天到晚上，从夏天到冬天等。这种图像变换滤波器明确地设计为使用基于SURF检测器和稠密描述符图的新损失来辅助和怂恿特征匹配。一个网络被训练输出为特征匹配而优化的合成图像，只给出一个输入的RGB图像，并且这些生成的图像被用于使用传统的稀疏匹配方法针对先前构建的地图定位机器人。我们使用牛津RobotCar数据集多年遍历一年的时间来对我们的结果进行基准测试，使用一次遍历作为地图，另一次本地化。我们证明，这种方法在改变和不利条件下显着改善了地点识别和本地化，同时减少了成功实现可靠本地化所需的映射运行次数。

##### URL
[http://arxiv.org/abs/1803.03341](http://arxiv.org/abs/1803.03341)

##### PDF
[http://arxiv.org/pdf/1803.03341](http://arxiv.org/pdf/1803.03341)

