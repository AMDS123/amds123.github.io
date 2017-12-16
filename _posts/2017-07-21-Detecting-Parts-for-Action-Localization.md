---
layout: post
title: "Detecting Parts for Action Localization"
date: 2017-07-21 21:40:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Detection
author: Nicolas Chesneau, Grégory Rogez, Karteek Alahari, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new framework for action localization that tracks people in videos and extracts full-body human tubes, i.e., spatio-temporal regions localizing actions, even in the case of occlusions or truncations. This is achieved by training a novel human part detector that scores visible parts while regressing full-body bounding boxes. The core of our method is a convolutional neural network which learns part proposals specific to certain body parts. These are then combined to detect people robustly in each frame. Our tracking algorithm connects the image detections temporally to extract full-body human tubes. We apply our new tube extraction method on the problem of human action localization, on the popular JHMDB dataset, and a very recent challenging dataset DALY (Daily Action Localization in YouTube), showing state-of-the-art results.

##### Abstract (translated by Google)
在本文中，我们提出了一个新的动作本地化框架，用于追踪视频中的人物，即使在遮挡或截断的情况下，也可以提取全身人体管，即时空区域本地化动作。这是通过训练一个新颖的人体部分探测器来实现的，该探测器在回归全身包围盒的同时对可见部分进行打分。我们的方法的核心是一个卷积神经网络，学习部分特定的身体部位的建议。然后将这些结合在一起，在每个框架中鲁棒地检测人员。我们的跟踪算法连接图像检测临时提取全身人体管。我们在人类动作定位问题，流行的JHMDB数据集以及最近具有挑战性的DALY数据集DALY（YouTube中的Daily Action Localization）上应用了我们的新管提取方法，显示了最新的结果。

##### URL
[https://arxiv.org/abs/1707.06005](https://arxiv.org/abs/1707.06005)

##### PDF
[https://arxiv.org/pdf/1707.06005](https://arxiv.org/pdf/1707.06005)

