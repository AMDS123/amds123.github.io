---
layout: post
title: "DeLS-3D: Deep Localization and Segmentation with a 3D Semantic Map"
date: 2018-05-13 21:18:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation RNN
author: Peng Wang, Ruigang Yang, Binbin Cao, Wei Xu, Yuanqing Lin
mathjax: true
---

* content
{:toc}

##### Abstract
For applications such as autonomous driving, self-localization/camera pose estimation and scene parsing are crucial technologies. In this paper, we propose a unified framework to tackle these two problems simultaneously. The uniqueness of our design is a sensor fusion scheme which integrates camera videos, motion sensors (GPS/IMU), and a 3D semantic map in order to achieve robustness and efficiency of the system. Specifically, we first have an initial coarse camera pose obtained from consumer-grade GPS/IMU, based on which a label map can be rendered from the 3D semantic map. Then, the rendered label map and the RGB image are jointly fed into a pose CNN, yielding a corrected camera pose. In addition, to incorporate temporal information, a multi-layer recurrent neural network (RNN) is further deployed improve the pose accuracy. Finally, based on the pose from RNN, we render a new label map, which is fed together with the RGB image into a segment CNN which produces per-pixel semantic label. In order to validate our approach, we build a dataset with registered 3D point clouds and video camera images. Both the point clouds and the images are semantically-labeled. Each video frame has ground truth pose from highly accurate motion sensors. We show that practically, pose estimation solely relying on images like PoseNet may fail due to street view confusion, and it is important to fuse multiple sensors. Finally, various ablation studies are performed, which demonstrate the effectiveness of the proposed system. In particular, we show that scene parsing and pose estimation are mutually beneficial to achieve a more robust and accurate system.

##### Abstract (translated by Google)
对于诸如自动驾驶的应用，自定位/相机姿态估计和场景解析是关键技术。在本文中，我们提出了一个统一的框架来同时解决这两个问题。我们设计的独特之处在于融合了摄像机视频，运动传感器（GPS / IMU）和3D语义映射的传感器融合方案，以实现系统的稳健性和效率。具体来说，我们首先有一个从消费级GPS / IMU获得的初始粗略摄像机姿态，根据这个姿势可以从3D语义地图渲染标签地图。然后，渲染的标签贴图和RGB图像被共同馈送到姿态CNN中，产生校正的相机姿态。另外，为了结合时间信息，进一步部署多层递归神经网络（RNN）来提高姿态精度。最后，基于来自RNN的姿态，我们呈现新的标签映射，其与RGB图像一起被馈送到产生每像素语义标签的片段CNN中。为了验证我们的方法，我们建立了一个带有注册3D点云和摄像机图像的数据集。点云和图像都是语义标记的。每个视频帧都具有高度精确的运动传感器的地面实况。我们表明，实际上，单纯依靠PoseNet等图像进行姿态估计可能会因街道视图混淆而失败，并且融合多个传感器非常重要。最后，进行各种消融研究，证明所提出的系统的有效性。特别是，我们表明，场景分析和姿态估计是互利的，以实现更强大和更精确的系统。

##### URL
[https://arxiv.org/abs/1805.04949](https://arxiv.org/abs/1805.04949)

##### PDF
[https://arxiv.org/pdf/1805.04949](https://arxiv.org/pdf/1805.04949)

