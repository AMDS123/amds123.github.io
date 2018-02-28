---
layout: post
title: "i3PosNet: Instrument Pose Estimation from X-Ray"
date: 2018-02-26 20:00:40
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Deep_Learning
author: David Kügler, Andrei Stefanov, Anirban Mukhopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
Performing delicate Minimally Invasive Surgeries (MIS) forces surgeons to accurately assess the position and orientation (pose) of surgical instruments. In current practice, this pose information is provided by conventional tracking systems (optical and electro-magnetic). Two challenges render these systems inadequate for minimally invasive bone surgery: the need for instrument positioning with high precision and occluding tissue blocking the line of sight. Fluoroscopic tracking is limited by the radiation exposure to patient and surgeon. A possible solution is constraining the acquisition of x-ray images. The distinct acquisitions at irregular intervals require a pose estimation solution instead of a tracking technique. We develop i3PosNet (Iterative Image Instrument Pose estimation Network), a patch-based modular Deep Learning method enhanced by geometric considerations, which estimates the pose of surgical instruments from single x-rays. For the evaluation of i3PosNet, we consider the scenario of drilling in the otobasis. i3PosNet generalizes well to different instruments, which we show by applying it to a screw, a drill and a robot. i3PosNet consistently estimates the pose of surgical instruments better than conventional image registration techniques by a factor of 5 and more achieving in-plane position errors of 0.031 mm +- 0.025 mm and angle errors of 0.031 +- 1.126. Additional factors, such as depth are evaluated to 0.361 mm +- 8.98 mm from single radiographs.

##### Abstract (translated by Google)
执行微妙的微创手术（MIS）迫使外科医生准确评估手术器械的位置和方向（姿势）。在目前的实践中，这种姿态信息由传统的跟踪系统（光学和电磁）提供。两个挑战使得这些系统对于微创骨手术而言不足：需要高精度的仪器定位和闭塞组织阻挡视线。荧光透视跟踪受限于患者和外科医生的辐射照射。一种可能的解决方案是限制X射线图像的采集。不规则间隔的不同采集需要一个姿态估计解决方案，而不是跟踪技术。我们开发了i3PosNet（迭代图像仪器姿态估计网络），这是一种基于贴片的模块化深度学习方法，它通过几何考虑得以增强，从单个x射线估计手术器械的姿态。对于i3PosNet的评估，我们考虑在otobasis钻孔的情况。 i3PosNet很好地适用于不同的仪器，我们将其应用于螺丝，钻头和机器人。 i3PosNet可以比传统的图像配准技术更好地估计手术器械的姿态5倍，并且可以实现0.031 mm±0.025 mm的面内位置误差和0.031±1.126的角度误差。其他因素，如深度评估为0.361毫米±8.98毫米从单幅X光片。

##### URL
[https://arxiv.org/abs/1802.09575](https://arxiv.org/abs/1802.09575)

##### PDF
[https://arxiv.org/pdf/1802.09575](https://arxiv.org/pdf/1802.09575)

