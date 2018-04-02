---
layout: post
title: "Joint Person Segmentation and Identification in Synchronized First- and Third-person Videos"
date: 2018-03-29 18:46:03
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Mingze Xu, Chenyou Fan, Yuchen Wang, Michael S Ryoo, David J Crandall
mathjax: true
---

* content
{:toc}

##### Abstract
In a world in which cameras are becoming more and more pervasive, scenes in public spaces are often captured from multiple perspectives by diverse types of cameras, including surveillance and wearable cameras. An important problem is how to organize these heterogeneous collections of videos by finding connections between them, such as identifying common correspondences between people both appearing in the videos and wearing the cameras. In this paper, we consider scenarios in which multiple cameras of different types are observing a scene involving multiple people, and we wish to solve two specific, related problems: (1) given two or more synchronized third-person videos of a scene, produce a pixel-level segmentation of each visible person and identify corresponding people across different views (i.e., determine who in camera A corresponds with whom in camera B), and (2) given one or more synchronized third-person videos as well as a first-person video taken by a wearable camera, segment and identify the camera wearer in the third-person videos. Unlike previous work which requires ground truth bounding boxes to estimate the correspondences, we jointly perform the person segmentation and identification. We find that solving these two problems simultaneously is mutually beneficial, because better fine-grained segmentations allow us to better perform matching across views, and using information from multiple views helps us perform more accurate segmentation. We evaluate our approach on a challenging dataset of interacting people captured from multiple wearable cameras, and show that our proposed method performs significantly better than the state-of-the-art on both person segmentation and identification.

##### Abstract (translated by Google)
在摄像机变得越来越普及的世界中，公共场所中的场景通常由多种类型的摄像机（包括监控摄像机和可穿戴摄像机）从多个角度捕获。一个重要的问题是如何通过查找它们之间的连接来组织这些异构的视频集合，例如识别出现在视频中的人们之间的通用对应关系以及佩戴相机。在本文中，我们考虑了不同类型的多个摄像机观察涉及多个人的场景的场景，并且我们希望解决两个具体的相关问题：（1）给定场景的两个或更多个同步的第三人视频，产生（2）给定一个或多个同步的第三人称视频以及第一人称视频的第一人视频由可穿戴相机拍摄的人员视频，细分并识别第三方视频中的相机佩戴者。与以往需要地面真实边界框估计对应关系的工作不同，我们共同执行人员分割和识别。我们发现同时解决这两个问题是互惠的，因为更好的细粒度分割使我们能够更好地执行视图间的匹配，并且使用来自多个视图的信息有助于我们执行更精确的分割。我们评估了我们在从多个可穿戴相机捕获的具有挑战性的数据集上评估我们的方法，并且表明我们提出的方法在人物分割和识别方面的表现明显优于现有技术。

##### URL
[https://arxiv.org/abs/1803.11217](https://arxiv.org/abs/1803.11217)

##### PDF
[https://arxiv.org/pdf/1803.11217](https://arxiv.org/pdf/1803.11217)

