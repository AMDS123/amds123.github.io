---
layout: post
title: "Joint 3D Reconstruction of a Static Scene and Moving Objects"
date: 2018-02-13 17:05:55
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking
author: Sergio Caccamo, Esra Ataer-Cansizoglu, Yuichi Taguchi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a technique for simultaneous 3D reconstruction of static regions and rigidly moving objects in a scene. An RGB-D frame is represented as a collection of features, which are points and planes. We classify the features into static and dynamic regions and grow separate maps, static and object maps, for each of them. To robustly classify the features in each frame, we fuse multiple RANSAC-based registration results obtained by registering different groups of the features to different maps, including (1) all the features to the static map, (2) all the features to each object map, and (3) subsets of the features, each forming a segment, to each object map. This multi-group registration approach is designed to overcome the following challenges: scenes can be dominated by static regions, making object tracking more difficult; and moving object might have larger pose variation between frames compared to the static regions. We show qualitative results from indoor scenes with objects in various shapes. The technique enables on-the-fly object model generation to be used for robotic manipulation.

##### Abstract (translated by Google)
我们提出了静态区域和场景中刚性移动物体的同时三维重建技术。 RGB-D帧被表示为点和面的特征集合。我们将这些特征分类为静态和动态区域，并为它们中的每一个生成单独的地图，静态和对象地图。为了对每个帧中的特征进行健壮地分类，我们融合了多个基于RANSAC的注册结果，这些注册结果通过将不同组的特征注册到不同的地图获得，包括（1）静态地图的所有特征，（2）每个对象的所有特征地图和（3）每个形成一个段的特征的子集到每个对象地图。这种多组注册方法旨在克服以下挑战：场景可以由静态区域支配，使对象跟踪更加困难;与静态区域相比，移动对象在帧之间可能具有较大的姿态变化。我们用各种形状的物体显示室内场景的定性结果。该技术使运行中的对象模型生成可用于机器人操作。

##### URL
[http://arxiv.org/abs/1802.04738](http://arxiv.org/abs/1802.04738)

##### PDF
[http://arxiv.org/pdf/1802.04738](http://arxiv.org/pdf/1802.04738)

