---
layout: post
title: "Simulating LIDAR Point Cloud for Autonomous Driving using Real-world Scenes and Traffic Flows"
date: 2018-11-17 07:09:13
categories: arXiv_CV
tags: arXiv_CV
author: Jin Fang, Feilong Yan, Tongtong Zhao, Feihu Zhang, Dingfu Zhou, Ruigang Yang, Yu Ma, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a LIDAR simulation framework that can automatically generate 3D point cloud based on LIDAR type and placement. The point cloud, annotated with ground truth semantic labels, is to be used as training data to improve environmental perception capabilities for autonomous driving vehicles. Different from previous simulators, we generate the point cloud based on real environment and real traffic flow. More specifically we employ a mobile LIDAR scanner with cameras to capture real world scenes. The input to our simulation framework includes dense 3D point cloud and registered color images. Moving objects (such as cars, pedestrians, bicyclists) are automatically identified and recorded. These objects are then removed from the input point cloud to restore a static background (e.g., environment without movable objects). With that we can insert synthetic models of various obstacles, such as vehicles and pedestrians in the static background to create various traffic scenes. A novel LIDAR renderer takes the composite scene to generate new realistic LIDAR points that are already annotated at point level for synthetic objects. Experimental results show that our system is able to close the performance gap between simulation and real data to be 1 ~ 6% in different applications, and for model fine tuning, only 10% ~ 20% extra real data could help to outperform the original model trained with full real dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07112](http://arxiv.org/abs/1811.07112)

##### PDF
[http://arxiv.org/pdf/1811.07112](http://arxiv.org/pdf/1811.07112)

