---
layout: post
title: "Ego-Lane Analysis System : Dataset and Algorithms"
date: 2018-06-15 14:02:44
categories: arXiv_CV
tags: arXiv_CV Tracking Classification Detection
author: Rodrigo F. Berriel, Edilson de Aguiar, Alberto F. de Souza, Thiago Oliveira-Santos
mathjax: true
---

* content
{:toc}

##### Abstract
Decreasing costs of vision sensors and advances in embedded hardware boosted lane related research detection, estimation, and tracking in the past two decades. The interest in this topic has increased even more with the demand for advanced driver assistance systems (ADAS) and self-driving cars. Although extensively studied independently, there is still need for studies that propose a combined solution for the multiple problems related to the ego-lane, such as lane departure warning (LDW), lane change detection, lane marking type (LMT) classification, road markings detection and classification, and detection of adjacent lanes (i.e., immediate left and right lanes) presence. In this paper, we propose a real-time Ego-Lane Analysis System (ELAS) capable of estimating ego-lane position, classifying LMTs and road markings, performing LDW and detecting lane change events. The proposed vision-based system works on a temporal sequence of images. Lane marking features are extracted in perspective and Inverse Perspective Mapping (IPM) images that are combined to increase robustness. The final estimated lane is modeled as a spline using a combination of methods (Hough lines with Kalman filter and spline with particle filter). Based on the estimated lane, all other events are detected. To validate ELAS and cover the lack of lane datasets in the literature, a new dataset with more than 20 different scenes (in more than 15,000 frames) and considering a variety of scenarios (urban road, highways, traffic, shadows, etc.) was created. The dataset was manually annotated and made publicly available to enable evaluation of several events that are of interest for the research community (i.e., lane estimation, change, and centering; road markings; intersections; LMTs; crosswalks and adjacent lanes). ELAS achieved high detection rates in all real-world events and proved to be ready for real-time applications.

##### Abstract (translated by Google)
在过去的二十年里，视觉传感器成本的降低和嵌入式硬件的进步推动了车道相关的研究检测，估计和跟踪。随着对高级驾驶辅助系统（ADAS）和自动驾驶汽车的需求，对这一主题的兴趣更加增加。尽管独立进行了广泛的研究，但仍需要研究提出针对与自我车道有关的多个问题的综合解决方案，例如车道偏离警告（LDW），车道变换检测，车道标记类型（LMT）分类，道路标记检测和分类以及相邻车道（即，即时左右车道）存在的检测。在本文中，我们提出了一个实时Ego-Lane分析系统（ELAS），能够估计自行车道位置，对LMT和道路标记进行分类，执行LDW并检测车道变化事件。所提出的基于视觉的系统对时间序列的图像起作用。车道标记特征是在透视和反向透视映射（IPM）图像中提取的，这些图像被组合以提高鲁棒性。最终估计车道使用方法组合（霍尔线与卡尔曼滤波器和样条线与粒子滤波器）建模为样条。基于估计的车道，检测到所有其他事件。为了验证ELAS并覆盖文献中缺少的车道数据集，一个包含超过20个不同场景（超过15,000帧）并考虑到各种场景（城市道路，高速公路，交通，阴影等）的新数据集为创建。该数据集被手动注释并公开可用，以评估研究社区感兴趣的几个事件（即车道估计，更改和居中;道路标记;交叉路口; LMT;人行横道和相邻车道）。 ELAS在所有现实世界的事件中都实现了高检测率，并被证明可以用于实时应用。

##### URL
[http://arxiv.org/abs/1806.05984](http://arxiv.org/abs/1806.05984)

##### PDF
[http://arxiv.org/pdf/1806.05984](http://arxiv.org/pdf/1806.05984)

