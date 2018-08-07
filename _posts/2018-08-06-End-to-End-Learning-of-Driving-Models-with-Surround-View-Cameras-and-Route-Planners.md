---
layout: post
title: "End-to-End Learning of Driving Models with Surround-View Cameras and Route Planners"
date: 2018-08-06 14:54:01
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Simon Hecker, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
For human drivers, having rear and side-view mirrors is vital for safe driving. They deliver a more complete view of what is happening around the car. Human drivers also heavily exploit their mental map for navigation. Nonetheless, several methods have been published that learn driving models with only a front-facing camera and without a route planner. This lack of information renders the self-driving task quite intractable. We investigate the problem in a more realistic setting, which consists of a surround-view camera system with eight cameras, a route planner, and a CAN bus reader. In particular, we develop a sensor setup that provides data for a 360-degree view of the area surrounding the vehicle, the driving route to the destination, and low-level driving maneuvers (e.g. steering angle and speed) by human drivers. With such a sensor setup we collect a new driving dataset, covering diverse driving scenarios and varying weather/illumination conditions. Finally, we learn a novel driving model by integrating information from the surround-view cameras and the route planner. Two route planners are exploited: 1) by representing the planned routes on OpenStreetMap as a stack of GPS coordinates, and 2) by rendering the planned routes on TomTom Go Mobile and recording the progression into a video. Our experiments show that: 1) 360-degree surround-view cameras help avoid failures made with a single front-view camera, in particular for city driving and intersection scenarios; and 2) route planners help the driving task significantly, especially for steering angle prediction.

##### Abstract (translated by Google)
对于人类驾驶员而言，后视镜和侧视镜对于安全驾驶至关重要。它们可以更全面地了解汽车周围发生的事情。人类驾驶员也大量利用他们的心理地图进行导航。尽管如此，已经发布了几种方法，这些方法仅使用前置摄像头和没有路线规划器来学习驾驶模型。缺乏信息使得自动驾驶任务变得非常棘手。我们在一个更现实的环境中研究这个问题，它包括一个带有八个摄像头的环视摄像系统，一个路线规划器和一个CAN总线阅读器。特别地，我们开发了一种传感器设置，其提供用于车辆周围区域的360度视图，到目的地的行驶路线以及人类驾驶员的低水平驾驶操纵（例如转向角和速度）的数据。通过这种传感器设置，我们收集了一个新的驾驶数据集，涵盖了各种驾驶场景和不同的天气/照明条件。最后，我们通过整合环视摄像机和路线规划器的信息，学习了一种新颖的驾驶模型。利用两个路线规划器：1）通过将OpenStreetMap上的计划路线表示为GPS坐标堆栈，以及2）通过在TomTom Go Mobile上渲染计划路线并将进展记录到视频中。我们的实验表明：1）360度环视摄像机有助于避免使用单个前视摄像头进行故障，特别是对于城市驾驶和交叉场景; 2）路线规划人员显着地帮助驾驶任务，特别是对于转向角预测。

##### URL
[http://arxiv.org/abs/1803.10158](http://arxiv.org/abs/1803.10158)

##### PDF
[http://arxiv.org/pdf/1803.10158](http://arxiv.org/pdf/1803.10158)

