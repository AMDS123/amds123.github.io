---
layout: post
title: "Multi-Person Pose Estimation with Local Joint-to-Person Associations"
date: 2016-08-31 09:26:57
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Detection
author: Umar Iqbal, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
Despite of the recent success of neural networks for human pose estimation, current approaches are limited to pose estimation of a single person and cannot handle humans in groups or crowds. In this work, we propose a method that estimates the poses of multiple persons in an image in which a person can be occluded by another person or might be truncated. To this end, we consider multi-person pose estimation as a joint-to-person association problem. We construct a fully connected graph from a set of detected joint candidates in an image and resolve the joint-to-person association and outlier detection using integer linear programming. Since solving joint-to-person association jointly for all persons in an image is an NP-hard problem and even approximations are expensive, we solve the problem locally for each person. On the challenging MPII Human Pose Dataset for multiple persons, our approach achieves the accuracy of a state-of-the-art method, but it is 6,000 to 19,000 times faster.

##### Abstract (translated by Google)
尽管神经网络最近在人体姿态估计方面取得了成功，但目前的方法仅限于对单个人进行估计，不能处理群体或人群中的人类。在这项工作中，我们提出了一种方法，可以估计一个人可能被另一个人遮挡或可能被截断的图像中的多个人的姿势。为此，我们将多人姿势估计视为联合人际关联问题。我们从图像中的一组检测到的关节候选人构建一个完全连通的图，并使用整数线性规划解决联合人与关联和异常检测。由于图像中所有人共同联合解决人与人之间的联系是一个NP难题，甚至近似值也很昂贵，所以我们在每个人的本地解决问题。在具有挑战性的多人MPII人体姿态数据集上，我们的方法达到了最先进方法的精确度，但速度却快了6000到19000倍。

##### URL
[https://arxiv.org/abs/1608.08526](https://arxiv.org/abs/1608.08526)

##### PDF
[https://arxiv.org/pdf/1608.08526](https://arxiv.org/pdf/1608.08526)

