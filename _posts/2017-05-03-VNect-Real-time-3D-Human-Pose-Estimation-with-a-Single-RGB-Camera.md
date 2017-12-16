---
layout: post
title: "VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera"
date: 2017-05-03 19:13:23
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Quantitative
author: Dushyant Mehta, Srinath Sridhar, Oleksandr Sotnychenko, Helge Rhodin, Mohammad Shafiei, Hans-Peter Seidel, Weipeng Xu, Dan Casas, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first real-time method to capture the full global 3D skeletal pose of a human in a stable, temporally consistent manner using a single RGB camera. Our method combines a new convolutional neural network (CNN) based pose regressor with kinematic skeleton fitting. Our novel fully-convolutional pose formulation regresses 2D and 3D joint positions jointly in real time and does not require tightly cropped input frames. A real-time kinematic skeleton fitting method uses the CNN output to yield temporally stable 3D global pose reconstructions on the basis of a coherent kinematic skeleton. This makes our approach the first monocular RGB method usable in real-time applications such as 3D character control---thus far, the only monocular methods for such applications employed specialized RGB-D cameras. Our method's accuracy is quantitatively on par with the best offline 3D monocular RGB pose estimation methods. Our results are qualitatively comparable to, and sometimes better than, results from monocular RGB-D approaches, such as the Kinect. However, we show that our approach is more broadly applicable than RGB-D solutions, i.e. it works for outdoor scenes, community videos, and low quality commodity RGB cameras.

##### Abstract (translated by Google)
我们提出了第一个实时方法来捕捉人类的全局三维骨骼姿态，使用一个单一的RGB相机以稳定，时间一致的方式捕捉人体。我们的方法将基于卷积神经网络（CNN）的姿态回归器与运动学骨架拟合相结合。我们的新型全卷积姿态公式实时地联合地回归2D和3D联合位置，并且不需要紧凑裁剪的输入帧。实时运动学骨架拟合方法使用CNN输出在相干运动学骨架的基础上产生时间稳定的3D全局姿态重建。这使得我们的方法成为第一个可用于实时应用的单眼RGB方法，例如3D角色控制。迄今为止，这种应用的唯一单眼方法是采用了专用的RGB-D相机。我们的方法的准确性在数量上与最好的离线3D单目RGB姿态估计方法相当。我们的结果在性能上与单眼RGB-D方法（如Kinect）的结果相当，甚至更好。然而，我们表明，我们的方法比RGB-D解决方案更广泛适用，即它适用于室外场景，社区视频和低质量商品RGB摄像机。

##### URL
[https://arxiv.org/abs/1705.01583](https://arxiv.org/abs/1705.01583)

##### PDF
[https://arxiv.org/pdf/1705.01583](https://arxiv.org/pdf/1705.01583)

