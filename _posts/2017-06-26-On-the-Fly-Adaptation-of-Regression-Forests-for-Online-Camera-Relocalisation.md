---
layout: post
title: "On-the-Fly Adaptation of Regression Forests for Online Camera Relocalisation"
date: 2017-06-26 10:11:30
categories: arXiv_CV
tags: arXiv_CV
author: Tommaso Cavallari, Stuart Golodetz, Nicholas A. Lord, Julien Valentin, Luigi Di Stefano, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Camera relocalisation is an important problem in computer vision, with applications in simultaneous localisation and mapping, virtual/augmented reality and navigation. Common techniques either match the current image against keyframes with known poses coming from a tracker, or establish 2D-to-3D correspondences between keypoints in the current image and points in the scene in order to estimate the camera pose. Recently, regression forests have become a popular alternative to establish such correspondences. They achieve accurate results, but must be trained offline on the target scene, preventing relocalisation in new environments. In this paper, we show how to circumvent this limitation by adapting a pre-trained forest to a new scene on the fly. Our adapted forests achieve relocalisation performance that is on par with that of offline forests, and our approach runs in under 150ms, making it desirable for real-time systems that require online relocalisation.

##### Abstract (translated by Google)
相机重新定位是计算机视觉中的一个重要问题，应用于同时定位和绘图，虚拟/增强现实和导航。常见的技术或者将当前图像与来自跟踪器的已知姿态的关键帧进行匹配，或者在当前图像中的关键点之间建立二维到三维的对应关系，并且指示场景中的点以估计相机姿态。最近，退化森林已经成为建立这种通信的流行替代方案。他们获得准确的结果，但必须在目标现场进行离线培训，防止在新环境中重新定位。在这篇论文中，我们展示了如何通过使一个预先训练好的森林适应一个新的场景在飞行中绕过这个限制。我们经过改造的森林实现了与离线森林相当的重新定位性能，我们的方法运行时间低于150ms，使得需要在线重新定位的实时系统成为可能。

##### URL
[https://arxiv.org/abs/1702.02779](https://arxiv.org/abs/1702.02779)

##### PDF
[https://arxiv.org/pdf/1702.02779](https://arxiv.org/pdf/1702.02779)

