---
layout: post
title: "Improving Foot-Mounted Inertial Navigation Through Real-Time Motion Classification"
date: 2018-07-13 20:26:05
categories: arXiv_RO
tags: arXiv_RO Object_Detection Survey Classification Detection
author: Brandon Wagstaff, Valentin Peretroukhin, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to improve the accuracy of a foot-mounted, zero-velocity-aided inertial navigation system (INS) by varying estimator parameters based on a real-time classification of motion type. We train a support vector machine (SVM) classifier using inertial data recorded by a single foot-mounted sensor to differentiate between six motion types (walking, jogging, running, sprinting, crouch-walking, and ladder-climbing) and report mean test classification accuracy of over 90% on a dataset with five different subjects. From these motion types, we select two of the most common (walking and running), and describe a method to compute optimal zero-velocity detection parameters tailored to both a specific user and motion type by maximizing the detector F-score. By combining the motion classifier with a set of optimal detection parameters, we show how we can reduce INS position error during mixed walking and running motion. We evaluate our adaptive system on a total of 5.9 km of indoor pedestrian navigation performed by five different subjects moving along a 130 m path with surveyed ground truth markers.

##### Abstract (translated by Google)
我们提出了一种方法，通过基于运动类型的实时分类改变估计器参数来提高脚踏式零速度辅助惯性导航系统（INS）的精度。我们使用单个脚安装传感器记录的惯性数据训练支持向量机（SVM）分类器，以区分六种运动类型（步行，慢跑，跑步，短跑，蹲伏和爬梯）并报告平均测试分类对具有五个不同主题的数据集的准确度超过90％。从这些运动类型中，我们选择两个最常见的（步行和跑步），并描述通过最大化检测器F得分来计算适合特定用户和运动类型的最佳零速度检测参数的方法。通过将运动分类器与一组最佳检测参数相结合，我们展示了如何在混合行走和跑步运动期间减少INS位置误差。我们评估我们的自适应系统，总共5.9公里的室内行人导航，由沿着130米路径移动的五个不同的主体与调查的地面真实标记一起执行。

##### URL
[http://arxiv.org/abs/1707.01152](http://arxiv.org/abs/1707.01152)

##### PDF
[http://arxiv.org/pdf/1707.01152](http://arxiv.org/pdf/1707.01152)

