---
layout: post
title: "Identifying First-person Camera Wearers in Third-person Videos"
date: 2017-04-20 21:16:26
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding CNN Object_Tracking Recognition
author: Chenyou Fan, Jangwon Lee, Mingze Xu, Krishna Kumar Singh, Yong Jae Lee, David J. Crandall, Michael S. Ryoo
mathjax: true
---

* content
{:toc}

##### Abstract
We consider scenarios in which we wish to perform joint scene understanding, object tracking, activity recognition, and other tasks in environments in which multiple people are wearing body-worn cameras while a third-person static camera also captures the scene. To do this, we need to establish person-level correspondences across first- and third-person videos, which is challenging because the camera wearer is not visible from his/her own egocentric video, preventing the use of direct feature matching. In this paper, we propose a new semi-Siamese Convolutional Neural Network architecture to address this novel challenge. We formulate the problem as learning a joint embedding space for first- and third-person videos that considers both spatial- and motion-domain cues. A new triplet loss function is designed to minimize the distance between correct first- and third-person matches while maximizing the distance between incorrect ones. This end-to-end approach performs significantly better than several baselines, in part by learning the first- and third-person features optimized for matching jointly with the distance measure itself.

##### Abstract (translated by Google)
我们考虑在其中多人佩戴体戴式相机的环境中执行联合场景理解，对象跟踪，活动识别和其他任务的场景，而第三人称静态相机也拍摄场景。为此，我们需要在第一人称视频和第三人视频之间建立人际关系，因为相机佩戴者不能从他/她自己的以自己为中心的视频中看到，因此不能使用直接特征匹配。在本文中，我们提出了一个新的半连体卷积神经网络体系结构来解决这个新的挑战。我们将问题规定为学习第一人称和第三人视频的联合嵌入空间，同时考虑空间和运动领域的线索。一个新的三重损失函数被设计用于最小化正确的第一人称和第三人称匹配之间的距离，同时最大化不正确之间的距离。这种端到端的方法比几个基线表现得好得多，部分是通过学习与距离测量本身匹配而优化的第一和第三人特征。

##### URL
[https://arxiv.org/abs/1704.06340](https://arxiv.org/abs/1704.06340)

##### PDF
[https://arxiv.org/pdf/1704.06340](https://arxiv.org/pdf/1704.06340)

