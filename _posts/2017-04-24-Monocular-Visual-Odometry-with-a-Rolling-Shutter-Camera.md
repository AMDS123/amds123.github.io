---
layout: post
title: "Monocular Visual Odometry with a Rolling Shutter Camera"
date: 2017-04-24 12:02:53
categories: arXiv_CV
tags: arXiv_CV Prediction Quantitative
author: Chang-Ryeol Lee, Kuk-Jin Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Rolling Shutter (RS) cameras have become popularized because of low-cost imaging capability. However, the RS cameras suffer from undesirable artifacts when the camera or the subject is moving, or illumination condition changes. For that reason, Monocular Visual Odometry (MVO) with RS cameras produces inaccurate ego-motion estimates. Previous works solve this RS distortion problem with motion prediction from images and/or inertial sensors. However, the MVO still has trouble in handling the RS distortion when the camera motion changes abruptly (e.g. vibration of mobile cameras causes extremely fast motion instantaneously). To address the problem, we propose the novel MVO algorithm in consideration of the geometric characteristics of RS cameras. The key idea of the proposed algorithm is the new RS essential matrix which incorporates the instantaneous angular and linear velocities at each frame. Our algorithm produces accurate and robust ego-motion estimates in an online manner, and is applicable to various mobile applications with RS cameras. The superiority of the proposed algorithm is validated through quantitative and qualitative comparison on both synthetic and real dataset.

##### Abstract (translated by Google)
由于低成本的成像能力，卷帘快门（RS）相机已经普及。然而，当相机或被摄体移动或照明条件改变时，RS相机遭受不希望的伪影。出于这个原因，带有RS摄像机的单目视觉内测（MVO）产生不准确的自我运动估计。以前的工作通过图像和/或惯性传感器的运动预测来解决这个RS失真问题。然而，当摄像机运动突然变化（例如移动摄像机的振动瞬间引起极快的运动）时，MVO在处理RS失真方面仍然存在麻烦。为了解决这个问题，我们提出了考虑到RS摄像机的几何特性的新型MVO算法。该算法的关键思想是在每一帧中结合瞬时角速度和线速度的新的RS基本矩阵。我们的算法以在线方式产生准确和强大的自我运动估计，并且适用于具有RS相机的各种移动应用。通过定量和定性比较合成和实际数据集，验证了所提算法的优越性。

##### URL
[https://arxiv.org/abs/1704.07163](https://arxiv.org/abs/1704.07163)

##### PDF
[https://arxiv.org/pdf/1704.07163](https://arxiv.org/pdf/1704.07163)

