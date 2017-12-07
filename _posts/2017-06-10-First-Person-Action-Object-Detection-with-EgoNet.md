---
layout: post
title: "First Person Action-Object Detection with EgoNet"
date: 2017-06-10 18:04:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Gedas Bertasius, Hyun Soo Park, Stella X. Yu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Unlike traditional third-person cameras mounted on robots, a first-person camera, captures a person's visual sensorimotor object interactions from up close. In this paper, we study the tight interplay between our momentary visual attention and motor action with objects from a first-person camera. We propose a concept of action-objects---the objects that capture person's conscious visual (watching a TV) or tactile (taking a cup) interactions. Action-objects may be task-dependent but since many tasks share common person-object spatial configurations, action-objects exhibit a characteristic 3D spatial distance and orientation with respect to the person. We design a predictive model that detects action-objects using EgoNet, a joint two-stream network that holistically integrates visual appearance (RGB) and 3D spatial layout (depth and height) cues to predict per-pixel likelihood of action-objects. Our network also incorporates a first-person coordinate embedding, which is designed to learn a spatial distribution of the action-objects in the first-person data. We demonstrate EgoNet's predictive power, by showing that it consistently outperforms previous baseline approaches. Furthermore, EgoNet also exhibits a strong generalization ability, i.e., it predicts semantically meaningful objects in novel first-person datasets. Our method's ability to effectively detect action-objects could be used to improve robots' understanding of human-object interactions.

##### Abstract (translated by Google)
与机器人上安装的传统第三人称摄像机不同，第一人称摄像机捕捉人的视觉感知运动物体的相互作用。在本文中，我们研究了我们的瞬间视觉注意力和运动行为与来自第一人称相机的物体之间的紧密相互作用。我们提出了一个动作对象的概念---捕捉人的有意识的视觉（看电视）或触觉（吃杯子）互动的对象。动作对象可以是依赖于任务的，但是由于许多任务共享普通的人物对象空间配置，所以动作对象相对于人呈现出特征性的3D空间距离和取向。我们设计了一个预测模型，使用EgoNet（一种联合的双流网络）来检测动作对象，EgoNet整体集成了视觉外观（RGB）和3D空间布局（深度和高度）线索，以预测动作对象的每像素可能性。我们的网络还包含一个第一人称坐标嵌入，用于学习第一人称数据中动作对象的空间分布。我们通过展示EgoNet的预测能力来证明它始终优于以前的基准方法。此外，EgoNet还表现出强大的泛化能力，即在新的第一人称数据集中预测语义上有意义的对象。我们的方法有效地检测动作对象的能力可以用来提高机器人对人与物体相互作用的理解。

##### URL
[https://arxiv.org/abs/1603.04908](https://arxiv.org/abs/1603.04908)

##### PDF
[https://arxiv.org/pdf/1603.04908](https://arxiv.org/pdf/1603.04908)

