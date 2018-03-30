---
layout: post
title: "Learning Driving Models with a Surround-View Camera System and a Route Planner"
date: 2018-03-27 16:07:45
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Simon Hecker, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
For people, having a rear-view mirror and side-view mirrors is vital for safe driving. They deliver a better view of what happens around the car. Human drivers also heavily exploit their mental map for navigation. Nonetheless, several methods have been published that learn driving models with only a front-facing camera and without a route planner. This lack of information renders the self-driving task quite intractable. Hence, we investigate the problem with a more realistic setting, which consists of a surround-view camera system with eight cameras, a route planner, and a CAN bus reader. In particular, we develop a sensor setup that provides data for a 360-degree view of the area surrounding the vehicle, the driving route to the destination, and the low-level driving maneuvers (e.g. steering angle and speed) by human drivers. With such sensor setup we collect a new driving dataset, covering diverse driving scenarios and varying weather/illumination conditions. Finally, we learn a novel driving model by integrating information from the surround-view cameras and the route planner. Two route planners are exploited: one based on OpenStreetMap and the other on TomTom Maps. The route planners are exploited in two ways: 1) by representing the planned routes as a stack of GPS coordinates, and 2) by rendering the planned routes on a map and recording the progression into a video. Our experiments show that: 1) 360-degree surround-view cameras help avoid failures made with a single front-view camera for the driving task; and 2) a route planner helps the driving task significantly. We acknowledge that our method is not the best-ever driving model, but that is not our focus. Rather, it provides a strong basis for further academic research, especially on driving relevant tasks by integrating information from street-view images and the planned driving routes. Code and data will be made available.

##### Abstract (translated by Google)
对于人来说，拥有后视镜和侧视镜对于安全驾驶至关重要。他们可以更好地了解车辆周围发生的情况。人类驾驶员也大量利用他们的导航心智图。尽管如此，已经发布了几种方法，只使用前置摄像头和没有路线规划器的情况下学习驾驶模型。信息的缺乏使得自我驾驶任务变得相当棘手。因此，我们通过更实际的设置来调查问题，该设置由带有8个摄像头的环视摄像系统，路线规划器和CAN总线读取器组成。特别是，我们开发了一种传感器装置，可为驾驶员提供360度全方位视野的数据，驾驶路线以及目的地的驾驶路线，以及驾驶人员的低级驾驶操作（例如转向角度和速度）。通过这种传感器设置，我们收集了一个新的驾驶数据集，涵盖了不同的驾驶场景和不同的天气/照明条件。最后，我们通过整合来自环视摄像头和路线规划者的信息来学习一种新颖的驾驶模式。两个路由规划者被利用：一个基于OpenStreetMap，另一个基于TomTom Maps。路线规划者有两种利用方式：1）通过将计划路线表示为一堆GPS坐标; 2）通过在地图上呈现规划路线并将进展记录到视频中。我们的实验表明：1）360度环视摄像头有助于避免使用单个前视摄像头进行驾驶任务时发生的故障;和2）路线规划者显着帮助驾驶任务。我们承认我们的方法并不是最好的驾驶模式，但这不是我们的重点。相反，它为进一步的学术研究提供了坚实的基础，特别是通过整合来自街景图像和计划的驾驶路线的信息来驾驶相关任务。代码和数据将可用。

##### URL
[https://arxiv.org/abs/1803.10158](https://arxiv.org/abs/1803.10158)

##### PDF
[https://arxiv.org/pdf/1803.10158](https://arxiv.org/pdf/1803.10158)

