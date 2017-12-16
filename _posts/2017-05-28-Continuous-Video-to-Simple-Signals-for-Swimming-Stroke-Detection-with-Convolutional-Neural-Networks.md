---
layout: post
title: "Continuous Video to Simple Signals for Swimming Stroke Detection with Convolutional Neural Networks"
date: 2017-05-28 06:14:06
categories: arXiv_CV
tags: arXiv_CV Knowledge Action_Recognition CNN Detection Recognition
author: Brandon Victor, Zhen He, Stuart Morgan, Dino Miniutti
mathjax: true
---

* content
{:toc}

##### Abstract
In many sports, it is useful to analyse video of an athlete in competition for training purposes. In swimming, stroke rate is a common metric used by coaches; requiring a laborious labelling of each individual stroke. We show that using a Convolutional Neural Network (CNN) we can automatically detect discrete events in continuous video (in this case, swimming strokes). We create a CNN that learns a mapping from a window of frames to a point on a smooth 1D target signal, with peaks denoting the location of a stroke, evaluated as a sliding window. To our knowledge this process of training and utilizing a CNN has not been investigated before; either in sports or fundamental computer vision research. Most research has been focused on action recognition and using it to classify many clips in continuous video for action localisation. In this paper we demonstrate our process works well on the task of detecting swimming strokes in the wild. However, without modifying the model architecture or training method, the process is also shown to work equally well on detecting tennis strokes, implying that this is a general process. The outputs of our system are surprisingly smooth signals that predict an arbitrary event at least as accurately as humans (manually evaluated from a sample of negative results). A number of different architectures are evaluated, pertaining to slightly different problem formulations and signal targets.

##### Abstract (translated by Google)
在许多运动中，分析一名运动员在比赛中进行训练的视频是有用的。在游泳中，中风率是教练常用的指标;需要对每个中风进行费力的标记。我们显示，使用卷积神经网络（CNN），我们可以自动检测连续视频中的离散事件（在这种情况下，游泳笔画）。我们创建一个CNN，学习从一帧窗口到一个平滑的一维目标信号上的一个点的映射，峰值表示一个笔画的位置，被评估为一个滑动窗口。据我们所知，培训和利用有线电视新闻网的过程还没有经过调查。无论是在运动或基础的计算机视觉研究。大部分的研究都集中在动作识别上，并用它来分类连续视频中的许多片段以进行动作定位。在本文中，我们展示了我们的过程在探测野外游泳中的任务方面效果很好。然而，在不修改模型架构或训练方法的情况下，该过程也显示出在检测网球运动方面同样好，这意味着这是一个普遍的过程。我们系统的输出是令人惊讶的平滑信号，可以至少与人类一样准确预测任意事件（从负面结果样本中手动评估）。评估了许多不同的架构，涉及到略有不同的问题公式和信号目标。

##### URL
[https://arxiv.org/abs/1705.09894](https://arxiv.org/abs/1705.09894)

##### PDF
[https://arxiv.org/pdf/1705.09894](https://arxiv.org/pdf/1705.09894)

