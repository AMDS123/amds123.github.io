---
layout: post
title: "Autonomous navigation for low-altitude UAVs in urban areas"
date: 2016-02-25 22:43:14
categories: arXiv_CV
tags: arXiv_CV Drone
author: Thomas Castelli, Aidean Sharghi, Don Harper, Alain Tremeau, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, consumer Unmanned Aerial Vehicles have become very popular, everyone can buy and fly a drone without previous experience, which raises concern in regards to regulations and public safety. In this paper, we present a novel approach towards enabling safe operation of such vehicles in urban areas. Our method uses geodetically accurate dataset images with Geographical Information System (GIS) data of road networks and buildings provided by Google Maps, to compute a weighted A* shortest path from start to end locations of a mission. Weights represent the potential risk of injuries for individuals in all categories of land-use, i.e. flying over buildings is considered safer than above roads. We enable safe UAV operation in regards to 1- land-use by computing a static global path dependent on environmental structures, and 2- avoiding flying over moving objects such as cars and pedestrians by dynamically optimizing the path locally during the flight. As all input sources are first geo-registered, pixels and GPS coordinates are equivalent, it therefore allows us to generate an automated and user-friendly mission with GPS waypoints readable by consumer drones' autopilots. We simulated 54 missions and show significant improvement in maximizing UAV's standoff distance to moving objects with a quantified safety parameter over 40 times better than the naive straight line navigation.

##### Abstract (translated by Google)
近年来，消费类无人驾驶飞机已经非常流行，没有以往的经验，每个人都可以购买和驾驶无人机，这就引起了人们对法规和公共安全的关注。在本文中，我们提出了一种新的方法来实现这种车辆在城市地区的安全运行。我们的方法使用具有Google Maps提供的道路网络和建筑物的地理信息系统（GIS）数据的大地测量准确的数据集图像来计算从任务的开始到结束位置的加权A *最短路径。重量代表所有类别土地使用者个人受伤的潜在风险，即飞越建筑物被认为比道路安全。通过计算一个依赖于环境结构的静态全局路径，实现安全无人机在1号土地利用方面的运行，并且通过在飞行过程中本地动态优化路径，避免飞越诸如汽车和行人等移动物体。由于所有的输入源都是首先进行地理配准的，所以像素和GPS坐标是相同的，因此可以让我们生成一个自动化的，用户友好的任务，可以通过消费者无人机的自动驾驶仪读取GPS航点。我们模拟了54个任务，并显示出最大化无人机与移动物体的距离的显着改善，其量化的安全参数比天真的直线导航好40倍以上。

##### URL
[https://arxiv.org/abs/1602.08141](https://arxiv.org/abs/1602.08141)

##### PDF
[https://arxiv.org/pdf/1602.08141](https://arxiv.org/pdf/1602.08141)

