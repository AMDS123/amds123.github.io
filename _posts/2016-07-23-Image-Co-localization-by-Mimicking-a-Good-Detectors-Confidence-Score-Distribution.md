---
layout: post
title: "Image Co-localization by Mimicking a Good Detector's Confidence Score Distribution"
date: 2016-07-23 11:09:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Yao Li, Linqiao Liu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Given a set of images containing objects from the same category, the task of image co-localization is to identify and localize each instance. This paper shows that this problem can be solved by a simple but intriguing idea, that is, a common object detector can be learnt by making its detection confidence scores distributed like those of a strongly supervised detector. More specifically, we observe that given a set of object proposals extracted from an image that contains the object of interest, an accurate strongly supervised object detector should give high scores to only a small minority of proposals, and low scores to most of them. Thus, we devise an entropy-based objective function to enforce the above property when learning the common object detector. Once the detector is learnt, we resort to a segmentation approach to refine the localization. We show that despite its simplicity, our approach outperforms state-of-the-art methods.

##### Abstract (translated by Google)
给定一组包含来自同一类别的对象的图像，图像共同定位的任务是识别和本地化每个实例。本文表明，这个问题可以通过一个简单而有趣的想法来解决，也就是说，一个普通的物体检测器可以通过使得它的检测可信度分布像一个强有力的检测器那样被分配来学习。更具体地说，我们观察到，从包含感兴趣对象的图像中提取的一组对象提议，准确的强有力监督的对象检测器应该只给予很少一部分提议的高分，并且对其中大部分提供低分。因此，我们设计一个基于熵的目标函数，在学习通用对象检测器的时候执行上述属性。一旦探测器被学习，我们诉诸分割的方法来完善本地化。我们表明，尽管其简单，我们的方法胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1603.04619](https://arxiv.org/abs/1603.04619)

##### PDF
[https://arxiv.org/pdf/1603.04619](https://arxiv.org/pdf/1603.04619)

