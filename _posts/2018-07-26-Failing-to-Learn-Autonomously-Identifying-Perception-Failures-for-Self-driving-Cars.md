---
layout: post
title: "Failing to Learn: Autonomously Identifying Perception Failures for Self-driving Cars"
date: 2018-07-26 19:41:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Deep_Learning Detection
author: Manikandasriram Srinivasan Ramanagopal, Cyrus Anderson, Ram Vasudevan, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major open challenges in self-driving cars is the ability to detect cars and pedestrians to safely navigate in the world. Deep learning-based object detector approaches have enabled great advances in using camera imagery to detect and classify objects. But for a safety critical application, such as autonomous driving, the error rates of the current state of the art are still too high to enable safe operation. Moreover, the characterization of object detector performance is primarily limited to testing on prerecorded datasets. Errors that occur on novel data go undetected without additional human labels. In this letter, we propose an automated method to identify mistakes made by object detectors without ground truth labels. We show that inconsistencies in the object detector output between a pair of similar images can be used as hypotheses for false negatives (e.g., missed detections) and using a novel set of features for each hypothesis, an off-the-shelf binary classifier can be used to find valid errors. In particular, we study two distinct cues - temporal and stereo inconsistencies - using data that are readily available on most autonomous vehicles. Our method can be used with any camera-based object detector and we illustrate the technique on several sets of real world data. We show that a state-of-the-art detector, tracker, and our classifier trained only on synthetic data can identify valid errors on KITTI tracking dataset with an average precision of 0.94. We also release a new tracking dataset with 104 sequences totaling 80,655 labeled pairs of stereo images along with ground truth disparity from a game engine to facilitate further research. The dataset and code are available at https://fcav.engin.umich.edu/research/failing-to-learn

##### Abstract (translated by Google)
自动驾驶汽车面临的主要开放挑战之一是能够探测到汽车和行人在世界范围内安全航行。基于深度学习的物体探测器方法在使用摄像机图像来检测和分类对象方面取得了很大进展。但是对于诸如自动驾驶的安全关键应用，当前技术水平的错误率仍然太高而不能实现安全操作。此外，物体探测器性能的表征主要限于对预先记录的数据集进行测试。如果没有额外的人工标签，新数据上发生的错误就无法检测到。在这封信中，我们提出了一种自动方法，用于识别物体探测器所产生的错误，而无需地面实况标签。我们表明，一对相似图像之间的对象检测器输出的不一致性可以用作假阴性（例如，遗漏检测）的假设，并且对于每个假设使用一组新的特征，现成的二元分类器可以是用于查找有效的错误。特别是，我们使用大多数自动驾驶车辆随时可用的数据研究两种截然不同的线索 - 时间和立体声不一致。我们的方法可以用于任何基于摄像头的物体探测器，我们在几组真实世界数据上说明了该技术。我们表明，只有合成数据训练的最先进的探测器，跟踪器和分类器才能识别KITTI跟踪数据集上的有效误差，平均精度为0.94。我们还发布了一个新的跟踪数据集，其中包含104个序列，总共80,655个标记的立体图像对，以及来自游戏引擎的地面实况差异，以便于进一步研究。数据集和代码可在https://fcav.engin.umich.edu/research/failing-to-learn获得。

##### URL
[http://arxiv.org/abs/1707.00051](http://arxiv.org/abs/1707.00051)

##### PDF
[http://arxiv.org/pdf/1707.00051](http://arxiv.org/pdf/1707.00051)

