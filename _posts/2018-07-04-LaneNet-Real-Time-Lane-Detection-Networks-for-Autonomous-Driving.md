---
layout: post
title: "LaneNet: Real-Time Lane Detection Networks for Autonomous Driving"
date: 2018-07-04 18:05:04
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Ze Wang, Weiqiang Ren, Qiang Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
Lane detection is to detect lanes on the road and provide the accurate location and shape of each lane. It severs as one of the key techniques to enable modern assisted and autonomous driving systems. However, several unique properties of lanes challenge the detection methods. The lack of distinctive features makes lane detection algorithms tend to be confused by other objects with similar local appearance. Moreover, the inconsistent number of lanes on a road as well as diverse lane line patterns, e.g. solid, broken, single, double, merging, and splitting lines further hamper the performance. In this paper, we propose a deep neural network based method, named LaneNet, to break down the lane detection into two stages: lane edge proposal and lane line localization. Stage one uses a lane edge proposal network for pixel-wise lane edge classification, and the lane line localization network in stage two then detects lane lines based on lane edge proposals. Please note that the goal of our LaneNet is built to detect lane line only, which introduces more difficulties on suppressing the false detections on the similar lane marks on the road like arrows and characters. Despite all the difficulties, our lane detection is shown to be robust to both highway and urban road scenarios method without relying on any assumptions on the lane number or the lane line patterns. The high running speed and low computational cost endow our LaneNet the capability of being deployed on vehicle-based systems. Experiments validate that our LaneNet consistently delivers outstanding performances on real world traffic scenarios.

##### Abstract (translated by Google)
车道检测是检测道路上的车道并提供每个车道的准确位置和形状。它作为实现现代辅助和自动驾驶系统的关键技术之一。然而，泳道的几个独特属性挑战了检测方法。缺乏显着特征使得车道检测算法倾向于被具有类似局部外观的其他物体所混淆。此外，道路上不一致的车道数量以及不同的车道线路图案，例如，实心，破损，单一，双重，合并和分割线进一步妨碍了性能。在本文中，我们提出了一种基于深度神经网络的方法，名为LaneNet，将车道检测分为两个阶段：车道边缘提议和车道线定位。第一阶段使用车道边缘提议网络进行逐像素车道边缘分类，第二阶段的车道线路定位网络然后根据车道边缘提议检测车道线路。请注意，我们的LaneNet的目标仅用于检测车道线，这在抑制道路上类似车道标记（如箭头和字符）上的错误检测方面存在更多困难。尽管存在各种困难，但我们的车道检测对于公路和城市道路情景方法都显示出稳健性，而不依赖于车道编号或车道线模式的任何假设。高运行速度和低计算成本使我们的LaneNet能够部署在基于车辆的系统上。实验验证我们的LaneNet始终如一地在真实世界的交通场景中提供出色的表现。

##### URL
[http://arxiv.org/abs/1807.01726](http://arxiv.org/abs/1807.01726)

##### PDF
[http://arxiv.org/pdf/1807.01726](http://arxiv.org/pdf/1807.01726)

