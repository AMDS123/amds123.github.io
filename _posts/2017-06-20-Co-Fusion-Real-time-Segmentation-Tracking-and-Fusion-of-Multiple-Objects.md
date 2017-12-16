---
layout: post
title: "Co-Fusion: Real-time Segmentation, Tracking and Fusion of Multiple Objects"
date: 2017-06-20 19:10:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking SLAM
author: Martin Rünz, Lourdes Agapito
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce Co-Fusion, a dense SLAM system that takes a live stream of RGB-D images as input and segments the scene into different objects (using either motion or semantic cues) while simultaneously tracking and reconstructing their 3D shape in real time. We use a multiple model fitting approach where each object can move independently from the background and still be effectively tracked and its shape fused over time using only the information from pixels associated with that object label. Previous attempts to deal with dynamic scenes have typically considered moving regions as outliers, and consequently do not model their shape or track their motion over time. In contrast, we enable the robot to maintain 3D models for each of the segmented objects and to improve them over time through fusion. As a result, our system can enable a robot to maintain a scene description at the object level which has the potential to allow interactions with its working environment; even in the case of dynamic scenes.

##### Abstract (translated by Google)
在本文中，我们将介绍Co-Fusion，一种以RGB-D图像的实时流作为输入并将场景分割成不同对象（使用运动或语义提示）同时同时实时跟踪和重建它们的3D形状的密集SLAM系统时间。我们使用多模型拟合方法，其中每个对象可以独立于背景移动并且仍然被有效地跟踪，并且其形状仅使用来自与该对象标签相关联的像素的信息随时间融合。先前的处理动态场景的尝试通常将移动区域视为异常值，因此不会模拟其形状或随着时间的推移跟踪其运动。相比之下，我们使机器人能够维护每个分割对象的3D模型，并通过融合随着时间的推移来改善它们。因此，我们的系统可以使机器人在对象级别维护场景描述，这有可能允许与其工作环境交互;即使在动态场景的情况下。

##### URL
[https://arxiv.org/abs/1706.06629](https://arxiv.org/abs/1706.06629)

##### PDF
[https://arxiv.org/pdf/1706.06629](https://arxiv.org/pdf/1706.06629)

