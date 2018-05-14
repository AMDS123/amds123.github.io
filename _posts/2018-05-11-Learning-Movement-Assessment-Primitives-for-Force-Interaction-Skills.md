---
layout: post
title: "Learning Movement Assessment Primitives for Force Interaction Skills"
date: 2018-05-11 12:22:17
categories: arXiv_RO
tags: arXiv_RO
author: Xiang Zhang, Athanasios S. Polydoros, Justus Piater
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel, reusable and task-agnostic primitive for assessing the outcome of a force-interaction robotic skill, useful e.g.\ for applications such as quality control in industrial manufacturing. The proposed method is easily programmed by kinesthetic teaching, and the desired adaptability and reusability are achieved by machine learning models. The primitive records sensory data during both demonstrations and reproductions of a movement. Recordings include the end-effector's Cartesian pose and exerted wrench at each time step. The collected data are then used to train Gaussian Processes which create models of the wrench as a function of the robot's pose. The similarity between the wrench models of the demonstration and the movement's reproduction is derived by measuring their Hellinger distance. This comparison creates features that are fed as inputs to a Naive Bayes classifier which estimates the movement's probability of success. The evaluation is performed on two diverse robotic assembly tasks -- snap-fitting and screwing -- with a total of 5 use cases, 11 demonstrations, and more than 200 movement executions. The performance metrics prove the proposed method's capability of generalization to different demonstrations and movements.

##### Abstract (translated by Google)
我们提出了一种新颖的，可重复使用的和任务不可知的原型，用于评估力量交互机器人技能的结果，例如用于工业制造中的质量控制等应用。所提出的方法易于通过运动学教学进行编程，并且通过机器学习模型实现期望的适应性和可重用性。原始动作记录了动作演示和复制过程中的感官数据。记录包括末端执行器的笛卡尔姿态，并在每个时间步骤施加扳手。所收集的数据然后用于训练高斯过程，其创建扳手的模型作为机器人姿态的函数。演示的扳手模型和运动的复制之间的相似性是通过测量他们的海尔辛距离得出的。这种比较创建了作为输入馈送到朴素贝叶斯分类器的特征，该分类器估计运动的成功概率。评估是在两种不同的机器人装配任务上进行的 - 卡扣和拧紧 - 总共有5个用例，11个演示和200多个移动执行。性能指标证明了该方法对不同示范和运动的泛化能力。

##### URL
[http://arxiv.org/abs/1805.04354](http://arxiv.org/abs/1805.04354)

##### PDF
[http://arxiv.org/pdf/1805.04354](http://arxiv.org/pdf/1805.04354)

