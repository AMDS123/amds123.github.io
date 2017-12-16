---
layout: post
title: "Real-time Hand Tracking under Occlusion from an Egocentric RGB-D Sensor"
date: 2017-10-05 14:05:06
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking CNN Quantitative
author: Franziska Mueller, Dushyant Mehta, Oleksandr Sotnychenko, Srinath Sridhar, Dan Casas, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for real-time, robust and accurate hand pose estimation from moving egocentric RGB-D cameras in cluttered real environments. Existing methods typically fail for hand-object interactions in cluttered scenes imaged from egocentric viewpoints, common for virtual or augmented reality applications. Our approach uses two subsequently applied Convolutional Neural Networks (CNNs) to localize the hand and regress 3D joint locations. Hand localization is achieved by using a CNN to estimate the 2D position of the hand center in the input, even in the presence of clutter and occlusions. The localized hand position, together with the corresponding input depth value, is used to generate a normalized cropped image that is fed into a second CNN to regress relative 3D hand joint locations in real time. For added accuracy, robustness and temporal stability, we refine the pose estimates using a kinematic pose tracking energy. To train the CNNs, we introduce a new photorealistic dataset that uses a merged reality approach to capture and synthesize large amounts of annotated data of natural hand interaction in cluttered scenes. Through quantitative and qualitative evaluation, we show that our method is robust to self-occlusion and occlusions by objects, particularly in moving egocentric perspectives.

##### Abstract (translated by Google)
我们提出了一种在杂乱的真实环境中通过移动以自我为中心的RGB-D摄像机实时，稳健和准确的手势估计的方法。现有的方法通常对于以自我中心视点成像的杂乱场景中的手对象交互失败，对于虚拟或增强现实应用而言是常见的。我们的方法使用两个随后应用的卷积神经网络（CNN）来定位手并回归3D关节位置。手部定位是通过使用CNN来估计输入中手部中心的二维位置，即使存在杂波和遮挡。局部手位置与相应的输入深度值一起用于生成归一化的裁剪图像，该归一化的裁剪图像被馈送到第二CNN中以实时回归相对3D手关节位置。为了增加准确性，鲁棒性和时间稳定性，我们使用运动学姿态跟踪能量来改进姿态估计。为了训练CNN，我们引入了一个新的真实感数据集，它使用合并的现实方法来捕捉和合成大量的混杂场景中自然人手交互的注释数据。通过定量和定性的评估，我们发现我们的方法对于自我遮挡和物体遮挡是强健的，特别是在移动自我中心的视角下。

##### URL
[https://arxiv.org/abs/1704.02201](https://arxiv.org/abs/1704.02201)

##### PDF
[https://arxiv.org/pdf/1704.02201](https://arxiv.org/pdf/1704.02201)

