---
layout: post
title: "Failing to Learn: Autonomously Identifying Perception Failures for Self-driving Cars"
date: 2017-07-12 01:58:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Deep_Learning Detection
author: Manikandasriram Srinivasan Ramanagopal, Cyrus Anderson, Ram Vasudevan, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major open challenges in self-driving cars is the ability to detect cars and pedestrians to safely navigate in the world. Deep learning-based object detector approaches have enabled great advances in using camera imagery to detect and classify objects. But for a safety critical application such as autonomous driving, the error rates of the current state-of-the-art are still too high to enable safe operation. Moreover, our characterization of object detector performance is primarily limited to testing on prerecorded datasets. Errors that occur on novel data go undetected without additional human labels. In this paper, we propose an automated method to identify mistakes made by object detectors without ground truth labels. We show that inconsistencies in object detector output between a pair of similar images can be used to identify false negatives(e.g. missed detections). In particular, we study two distinct cues - temporal and stereo inconsistencies - using data that is readily available on most autonomous vehicles. Our method can be used with any camera-based object detector and we evaluate the technique on several sets of real world data. The proposed method achieves over 97% precision in automatically identifying missed detections produced by one of the leading state-of-the-art object detectors in the literature. We also release a new tracking dataset with over 100 sequences totaling more than 80,000 labeled images from a game engine to facilitate further research.

##### Abstract (translated by Google)
自动驾驶汽车面临的主要挑战之一是能够检测汽车和行人在世界上安全航行。基于深度学习的对象检测器方法已经在使用相机图像来检测和分类对象方面取得了巨大的进步。但是对于自动驾驶这样的安全性要求很高的应用来说，现有技术水平的误差率仍然太高，无法安全运行。而且，我们对物体检测器性能的表征主要局限于在预先记录的数据集上进行测试。新颖数据上出现的错误在没有附加人标签的情况下不会被发现。在本文中，我们提出了一种自动方法来识别没有地面实况标签的物体探测器所造成的错误。我们表明，一对相似的图像之间的物体检测器输出的不一致可以用于识别假阴性（例如错过的检测）。特别是，我们研究了两个不同的线索 - 时间和立体不一致 - 使用大多数自主车辆上容易获得的数据。我们的方法可以与任何基于相机的物体探测器一起使用，并且我们在多组真实世界的数据上评估技术。所提出的方法在自动识别由文献中领先的最先进的物体检测器之一所产生的错过检测中实现了超过97％的精度。我们还发布了一个新的跟踪数据集，超过100个序列，共有来自游戏引擎的超过80,000个标记图像，以便于进一步研究。

##### URL
[https://arxiv.org/abs/1707.00051](https://arxiv.org/abs/1707.00051)

##### PDF
[https://arxiv.org/pdf/1707.00051](https://arxiv.org/pdf/1707.00051)

