---
layout: post
title: "RIDI: Robust IMU Double Integration"
date: 2017-12-25 04:43:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Quantitative
author: Hang Yan, Qi Shan, Yasutaka Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel data-driven approach for inertial navigation, which learns to estimate trajectories of natural human motions just from an inertial measurement unit (IMU) in every smartphone. The key observation is that human motions are repetitive and consist of a few major modes (e.g., standing, walking, or turning). Our algorithm regresses a velocity vector from the history of linear accelerations and angular velocities, then corrects low-frequency bias in the linear accelerations, which are integrated twice to estimate positions. We have acquired training data with ground-truth motions across multiple human subjects and multiple phone placements (e.g., in a bag or a hand). The qualitatively and quantitatively evaluations have demonstrated that our algorithm has surprisingly shown comparable results to full Visual Inertial navigation. To our knowledge, this paper is the first to integrate sophisticated machine learning techniques with inertial navigation, potentially opening up a new line of research in the domain of data-driven inertial navigation. We will publicly share our code and data to facilitate further research.

##### Abstract (translated by Google)
本文提出了一种新颖的数据驱动的惯性导航方法，学习如何从每个智能手机的惯性测量单元（IMU）中估算自然人体运动的轨迹。关键的观察是人类的运动是重复的，包括一些主要模式（例如，站立，走路或转弯）。我们的算法从线性加速度和角速度的历史中回归速度矢量，然后校正线性加速度中的低频偏差，其被整合两次以估计位置。我们已经通过多个人类主题和多个手机展示位置（例如一个手提包或一只手）获得了具有地面真实运动的训练数据。定性和定量评估表明，我们的算法已经出乎意料地显示出与全视觉惯性导航相当的结果。就我们所知，本文首次将复杂的机器学习技术与惯性导航技术相结合，有可能在数据驱动的惯性导航领域开辟一条新的研究领域。我们将公开分享我们的代码和数据以促进进一步的研究。

##### URL
[http://arxiv.org/abs/1712.09004](http://arxiv.org/abs/1712.09004)

##### PDF
[http://arxiv.org/pdf/1712.09004](http://arxiv.org/pdf/1712.09004)

