---
layout: post
title: "Visual-Inertial-Semantic Scene Representation for 3-D Object Detection"
date: 2017-04-17 20:25:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Drone CNN Detection
author: Jingming Dong, Xiaohan Fei, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a system to detect objects in three-dimensional space using video and inertial sensors (accelerometer and gyrometer), ubiquitous in modern mobile platforms from phones to drones. Inertials afford the ability to impose class-specific scale priors for objects, and provide a global orientation reference. A minimal sufficient representation, the posterior of semantic (identity) and syntactic (pose) attributes of objects in space, can be decomposed into a geometric term, which can be maintained by a localization-and-mapping filter, and a likelihood function, which can be approximated by a discriminatively-trained convolutional neural network. The resulting system can process the video stream causally in real time, and provides a representation of objects in the scene that is persistent: Confidence in the presence of objects grows with evidence, and objects previously seen are kept in memory even when temporarily occluded, with their return into view automatically predicted to prime re-detection.

##### Abstract (translated by Google)
我们描述了一个使用视频和惯性传感器（加速度计和陀螺仪）在三维空间中检测物体的系统，无论在从手机到无人机的现代移动平台中都是如此。惯性提供了为对象强加特定类别比例的能力，并提供了一个全球性的方向参考。一个最小的充分表示，空间中对象的语义（身份）和语法（姿态）属性的后验可以被分解成一个几何术语，可以通过一个定位和映射过滤器和一个似然函数来维护可以通过有区别地训练的卷积神经网络来近似。由此产生的系统可以实时处理视频流，并提供场景中持久对象的表示：存在对象的可信度随着证据增长而增加，并且即使临时遮挡，以前看到的对象也会保留在内存中他们返回到视图自动预测重新检测。

##### URL
[https://arxiv.org/abs/1606.03968](https://arxiv.org/abs/1606.03968)

