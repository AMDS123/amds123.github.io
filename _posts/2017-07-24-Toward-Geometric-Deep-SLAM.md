---
layout: post
title: "Toward Geometric Deep SLAM"
date: 2017-07-24 05:41:35
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Tracking CNN Detection SLAM
author: Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
We present a point tracking system powered by two deep convolutional neural networks. The first network, MagicPoint, operates on single images and extracts salient 2D points. The extracted points are "SLAM-ready" because they are by design isolated and well-distributed throughout the image. We compare this network against classical point detectors and discover a significant performance gap in the presence of image noise. As transformation estimation is more simple when the detected points are geometrically stable, we designed a second network, MagicWarp, which operates on pairs of point images (outputs of MagicPoint), and estimates the homography that relates the inputs. This transformation engine differs from traditional approaches because it does not use local point descriptors, only point locations. Both networks are trained with simple synthetic data, alleviating the requirement of expensive external camera ground truthing and advanced graphics rendering pipelines. The system is fast and lean, easily running 30+ FPS on a single CPU.

##### Abstract (translated by Google)
我们提出了一个由两个深度卷积神经网络驱动的点跟踪系统。第一个网络，MagicPoint，对单个图像进行操作，并提取显着的2D点。提取的点是“SLAM就绪”，因为它们在设计上是分离的并且在整个图像中分布均匀。我们将这个网络与经典的点检测器进行比较，发现图像噪声存在显着的性能差距。因为当检测点几何稳定时，变换估计更简单，我们设计了第二个网络MagicWarp，该网络对一对点图像（MagicPoint的输出）进行操作，并估计与输入有关的单应性。这个转换引擎不同于传统的方法，因为它不使用本地点描述符，只使用点位置。两个网络都使用简单的合成数据进行训练，从而减轻了昂贵的外部摄像头地面测量和高级图形渲染管线的需求。该系统速度快，精简，可以在单个CPU上轻松运行30+ FPS。

##### URL
[https://arxiv.org/abs/1707.07410](https://arxiv.org/abs/1707.07410)

##### PDF
[https://arxiv.org/pdf/1707.07410](https://arxiv.org/pdf/1707.07410)

