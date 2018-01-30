---
layout: post
title: "Multiple Object Detection, Tracking and Long-Term Dynamics Learning in Large 3D Maps"
date: 2018-01-28 21:36:38
categories: arXiv_RO
tags: arXiv_RO Object_Detection Tracking Detection
author: Nils Bore, Patric Jensfelt, John Folkesson
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a method for tracking and learning the dynamics of all objects in a large scale robot environment. A mobile robot patrols the environment and visits the different locations one by one. Movable objects are discovered by change detection, and tracked throughout the robot deployment. For tracking, we extend the Rao-Blackwellized particle filter of previous work with birth and death processes, enabling the method to handle an arbitrary number of objects. Target births and associations are sampled using Gibbs sampling. The parameters of the system are then learnt using the Expectation Maximization algorithm in an unsupervised fashion. The system therefore enables learning of the dynamics of one particular environment, and of its objects. The algorithm is evaluated on data collected autonomously by a mobile robot in an office environment during a real-world deployment. We show that the algorithm automatically identifies and tracks the moving objects within 3D maps and infers plausible dynamics models, significantly decreasing the modeling bias of our previous work. The proposed method represents an improvement over previous methods for environment dynamics learning as it allows for learning of fine grained processes.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个方法来跟踪和学习大型机器人环境中的所有对象的动态。移动机器人巡视环境并逐一访问不同的地点。可移动物体通过变化检测发现，并在整个机器人部署过程中进行跟踪。为了跟踪，我们扩展了先前工作的Rao-Blackwellized粒子滤波器的出生和死亡过程，使该方法能够处理任意数量的对象。目标出生和协会采用吉布斯抽样进行抽样。然后使用期望最大化算法以无监督的方式学习系统的参数。因此该系统能够学习一个特定环境及其对象的动态。在实际部署期间，在办公室环境中通过移动机器人自主收集的数据对算法进行评估。我们表明，该算法自动识别和跟踪三维地图内的移动对象，推断似是而非的动力学模型，显着减少了我们以前的工作建模偏见。所提出的方法代表了对先前的环境动态学习方法的改进，因为它允许学习细粒度的过程。

##### URL
[http://arxiv.org/abs/1801.09292](http://arxiv.org/abs/1801.09292)

##### PDF
[http://arxiv.org/pdf/1801.09292](http://arxiv.org/pdf/1801.09292)

