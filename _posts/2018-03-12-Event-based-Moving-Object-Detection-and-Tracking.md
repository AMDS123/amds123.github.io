---
layout: post
title: "Event-based Moving Object Detection and Tracking"
date: 2018-03-12 20:43:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection
author: Anton Mitrokhin, Cornelia Fermuller, Chethan Parameshwara, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based vision sensors, such as the Dynamic Vision Sensor (DVS), are ideally suited for real-time motion analysis. The unique properties encompassed in the readings of such sensors provide high temporal resolution, superior sensitivity to light and low latency. These properties provide the grounds to estimate motion extremely reliably in the most sophisticated scenarios but they come at a price - modern event-based vision sensors have extremely low resolution and produce a lot of noise. Moreover, the asynchronous nature of the event stream calls for novel algorithms. 
 This paper presents a new, efficient approach to object tracking with asynchronous cameras. We present a novel event stream representation which enables us to utilize information about the dynamic (temporal) component of the event stream, and not only the spatial component, at every moment of time. This is done by approximating the 3D geometry of the event stream with a parametric model; as a result, the algorithm is capable of producing the motion-compensated event stream (effectively approximating egomotion), and without using any form of external sensors in extremely low-light and noisy conditions without any form of feature tracking or explicit optical flow computation. We demonstrate our framework on the task of independent motion detection and tracking, where we use the temporal model inconsistencies to locate differently moving objects in challenging situations of very fast motion.

##### Abstract (translated by Google)
基于事件的视觉传感器，如动态视觉传感器（DVS），非常适合实时运动分析。这些传感器读数所包含的独特属性提供了高时间分辨率，对光线的超高灵敏度和低延迟。这些特性为在最复杂情况下非常可靠地估算运动提供了理由，但它们的价格很高 - 现代的基于事件的视觉传感器具有极低的分辨率并产生大量噪音。而且，事件流的异步特性需要新颖的算法。
 本文提出了一种新的高效的异步相机跟踪对象方法。我们提出了一种新颖的事件流表示形式，它使我们能够利用关于事件流的动态（时态）组件的信息，而不仅仅是在每个时刻的空间组件。这通过用参数模型近似事件流的3D几何来完成;结果，该算法能够产生运动补偿事件流（有效逼近运动），并且在没有任何形式的特征跟踪或明确的光流计算的情况下，在极低光和噪声条件下不使用任何形式的外部传感器。我们在独立运动检测和跟踪任务中展示了我们的框架，我们使用时间模型不一致性来在非常快速的运动的具有挑战性的情况下定位不同的运动对象。

##### URL
[http://arxiv.org/abs/1803.04523](http://arxiv.org/abs/1803.04523)

##### PDF
[http://arxiv.org/pdf/1803.04523](http://arxiv.org/pdf/1803.04523)

