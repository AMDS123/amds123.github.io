---
layout: post
title: "Automatic Discovery and Geotagging of Objects from Street View Imagery"
date: 2017-12-01 17:05:02
categories: arXiv_CV
tags: arXiv_CV CNN
author: Vladimir A. Krylov, Eamonn Kenny, Rozenn Dahyot
mathjax: true
---

* content
{:toc}

##### Abstract
Many applications such as autonomous navigation, urban planning and asset monitoring, rely on the availability of accurate information about objects and their geolocations. In this paper we propose to automatically detect and compute the GPS coordinates of recurring stationary objects of interest using street view imagery. Our processing pipeline relies on two fully convolutional neural networks: the first segments objects in the images while the second estimates their distance from the camera. To geolocate all the detected objects coherently we propose a novel custom Markov Random Field model to perform objects triangulation. The novelty of the resulting pipeline is the combined use of monocular depth estimation and triangulation to enable automatic mapping of complex scenes with multiple visually similar objects of interest. We validate experimentally the effectiveness of our approach on two object classes: traffic lights and telegraph poles. The experiments report high object recall rates and GPS accuracy within 2 meters, which is comparable with the precision of single-frequency GPS receivers.

##### Abstract (translated by Google)
诸如自主导航，城市规划和资产监控等许多应用依赖于有关物体及其地理位置的准确信息的可用性。在本文中，我们建议使用街景图像自动检测和计算感兴趣的静止物体的GPS坐标。我们的处理流程依赖于两个完全卷积神经网络：第一个分段对象在图像中，而第二个估计它们与相机的距离。为了对所有检测到的物体进行相干地理定位，我们提出了一种新颖的定制马尔可夫随机场模型来执行物体三角测量。所得到的流水线的新颖性是单目深度估计和三角测量的组合使得能够将复杂场景与多个视觉上相似的感兴趣对象进行自动映射。我们通过实验验证了我们的方法在两个对象类别（交通灯和电线杆）上的有效性。实验报告的目标回忆率高，GPS精度在2米以内，与单频GPS接收机精度相当。

##### URL
[https://arxiv.org/abs/1708.08417](https://arxiv.org/abs/1708.08417)

##### PDF
[https://arxiv.org/pdf/1708.08417](https://arxiv.org/pdf/1708.08417)

