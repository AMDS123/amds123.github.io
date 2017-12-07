---
layout: post
title: "Modelling Observation Correlations for Active Exploration and Robust Object Detection"
date: 2014-01-18 21:37:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Javier Velez, Garrett Hemann, Albert S. Huang, Ingmar Posner, Nicholas Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Today, mobile robots are expected to carry out increasingly complex tasks in multifarious, real-world environments. Often, the tasks require a certain semantic understanding of the workspace. Consider, for example, spoken instructions from a human collaborator referring to objects of interest; the robot must be able to accurately detect these objects to correctly understand the instructions. However, existing object detection, while competent, is not perfect. In particular, the performance of detection algorithms is commonly sensitive to the position of the sensor relative to the objects in the scene. This paper presents an online planning algorithm which learns an explicit model of the spatial dependence of object detection and generates plans which maximize the expected performance of the detection, and by extension the overall plan performance. Crucially, the learned sensor model incorporates spatial correlations between measurements, capturing the fact that successive measurements taken at the same or nearby locations are not independent. We show how this sensor model can be incorporated into an efficient forward search algorithm in the information space of detected objects, allowing the robot to generate motion plans efficiently. We investigate the performance of our approach by addressing the tasks of door and text detection in indoor environments and demonstrate significant improvement in detection performance during task execution over alternative methods in simulated and real robot experiments.

##### Abstract (translated by Google)
今天，移动机器人有望在多种多样的现实环境中执行日益复杂的任务。通常，任务需要对工作空间有一定的语义理解。例如，考虑来自人类合作者的关于感兴趣对象的口头指示;机器人必须能够准确地检测到这些物体，以正确理解说明。但是，现有的对象检测虽然胜任，但并不完美。具体而言，检测算法的性能通常对传感器相对于场景中的物体的位置敏感。本文提出了一种在线规划算法，该算法学习目标检测的空间依赖性的显式模型，并产生使检测的预期性能最大化的计划，并且扩展总体计划性能。重要的是，学习的传感器模型结合了测量之间的空间相关性，捕捉在相同或附近位置进行的连续测量不是独立的事实。我们展示了如何将这个传感器模型纳入检测对象的信息空间的高效前向搜索算法，使机器人能够有效地生成运动计划。我们通过解决室内环境中门和文本检测的任务来调查我们的方法的性能，并且在模拟和真实机器人实验中的替代方法的任务执行期间证明检测性能的显着改进。

##### URL
[https://arxiv.org/abs/1401.4612](https://arxiv.org/abs/1401.4612)

##### PDF
[https://arxiv.org/pdf/1401.4612](https://arxiv.org/pdf/1401.4612)

