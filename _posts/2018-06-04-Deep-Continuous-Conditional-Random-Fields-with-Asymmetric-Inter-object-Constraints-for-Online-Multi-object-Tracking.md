---
layout: post
title: "Deep Continuous Conditional Random Fields with Asymmetric Inter-object Constraints for Online Multi-object Tracking"
date: 2018-06-04 16:27:03
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Detection Relation
author: Hui Zhou, Wanli Ouyang, Jian Cheng, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Online Multi-Object Tracking (MOT) is a challenging problem and has many important applications including intelligence surveillance, robot navigation and autonomous driving. In existing MOT methods, individual object's movements and inter-object relations are mostly modeled separately and relations between them are still manually tuned. In addition, inter-object relations are mostly modeled in a symmetric way, which we argue is not an optimal setting. To tackle those difficulties, in this paper, we propose a Deep Continuous Conditional Random Field (DCCRF) for solving the online MOT problem in a track-by-detection framework. The DCCRF consists of unary and pairwise terms. The unary terms estimate tracked objects' displacements across time based on visual appearance information. They are modeled as deep Convolution Neural Networks, which are able to learn discriminative visual features for tracklet association. The asymmetric pairwise terms model inter-object relations in an asymmetric way, which encourages high-confidence tracklets to help correct errors of low-confidence tracklets and not to be affected by low-confidence ones much. The DCCRF is trained in an end-to-end manner for better adapting the influences of visual information as well as inter-object relations. Extensive experimental comparisons with state-of-the-arts as well as detailed component analysis of our proposed DCCRF on two public benchmarks demonstrate the effectiveness of our proposed MOT framework.

##### Abstract (translated by Google)
在线多目标跟踪（MOT）是一个具有挑战性的问题，并且具有许多重要的应用，包括智能监视，机器人导航和自动驾驶。在现有的MOT方法中，单个对象的运动和对象间关系大多是单独建模的，它们之间的关系仍然是手动调整的。另外，对象间的关系大多是以对称的方式建模的，我们认为这不是一个最佳的设置。为了解决这些困难，在本文中，我们提出了一种深度连续条件随机场（DCCRF），用于在逐行检测框架中解决在线MOT问题。 DCCRF由一元和两两组成。一元项根据视觉外观信息估计跟踪对象随时间的位移。他们被模拟为深度卷积神经网络，能够学习跟踪关联的区分视觉特征。非对称成对条款以不对称的方式模拟对象间的关系，鼓励高信心的tracklets帮助纠正低置信度tracklets的错误，而不会被低置信度的错误所影响。 DCCRF是以端对端的方式进行训练，以更好地适应视觉信息以及对象间关系的影响。与先进技术进行广泛的实验比较以及我们在两个公共基准上提出的DCCRF的详细成分分析证明了我们提出的MOT框架的有效性。

##### URL
[http://arxiv.org/abs/1806.01183](http://arxiv.org/abs/1806.01183)

##### PDF
[http://arxiv.org/pdf/1806.01183](http://arxiv.org/pdf/1806.01183)

