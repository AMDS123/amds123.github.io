---
layout: post
title: "Mono-Camera 3D Multi-Object Tracking Using Deep Learning Detections and PMBM Filtering"
date: 2018-02-27 15:46:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Deep_Learning Detection
author: Samuel Scheidegger, Joachim Benjaminsson, Emil Rosenberg, Amrit Krishnan, Karl Granstrom
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular cameras are one of the most commonly used sensors in the automotive industry for autonomous vehicles. One major drawback using a monocular camera is that it only makes observations in the two dimensional image plane and can not directly measure the distance to objects. In this paper, we aim at filling this gap by developing a multi-object tracking algorithm that takes an image as input and produces trajectories of detected objects in a world coordinate system. We solve this by using a deep neural network trained to detect and estimate the distance to objects from a single input image. The detections from a sequence of images are fed in to a state-of-the art Poisson multi-Bernoulli mixture tracking filter. The combination of the learned detector and the PMBM filter results in an algorithm that achieves 3D tracking using only mono-camera images as input. The performance of the algorithm is evaluated both in 3D world coordinates, and 2D image coordinates, using the publicly available KITTI object tracking dataset. The algorithm shows the ability to accurately track objects, correctly handle data associations, even when there is a big overlap of the objects in the image, and is one of the top performing algorithms on the KITTI object tracking benchmark. Furthermore, the algorithm is efficient, running on average close to 20 frames per second.

##### Abstract (translated by Google)
单目照相机是汽车行业中用于自动驾驶车辆的最常用的传感器之一。使用单眼相机的一个主要缺点是它仅在二维图像平面进行观察，并且不能直接测量到物体的距离。在本文中，我们旨在通过开发一个多对象跟踪算法来填补这一空白，该算法将图像作为输入并在世界坐标系中产生检测对象的轨迹。我们通过使用训练的深度神经网络来解决这个问题，以检测和估计从单个输入图像到物体的距离。来自一系列图像的检测被输入到现有技术的泊松多伯努利混合跟踪滤波器中。学习探测器和PMBM滤波器的结合产生了一种算法，该算法仅使用单相机图像作为输入来实现3D跟踪。使用公开可用的KITTI对象跟踪数据集，在3D世界坐标和2D图像坐标中评估算法的性能。该算法显示了准确跟踪对象，正确处理数据关联的能力，即使图像中的对象存在大量重叠，也是KITTI对象跟踪基准测试中性能最佳的算法之一。此外，算法效率很高，平均每秒钟运行速度接近20帧。

##### URL
[https://arxiv.org/abs/1802.09975](https://arxiv.org/abs/1802.09975)

##### PDF
[https://arxiv.org/pdf/1802.09975](https://arxiv.org/pdf/1802.09975)

