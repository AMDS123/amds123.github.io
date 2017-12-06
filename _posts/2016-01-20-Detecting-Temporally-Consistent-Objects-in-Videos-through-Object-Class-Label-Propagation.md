---
layout: post
title: "Detecting Temporally Consistent Objects in Videos through Object Class Label Propagation"
date: 2016-01-20 21:45:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Subarna Tripathi, Serge Belongie, Youngbae Hwang, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Object proposals for detecting moving or static video objects need to address issues such as speed, memory complexity and temporal consistency. We propose an efficient Video Object Proposal (VOP) generation method and show its efficacy in learning a better video object detector. A deep-learning based video object detector learned using the proposed VOP achieves state-of-the-art detection performance on the Youtube-Objects dataset. We further propose a clustering of VOPs which can efficiently be used for detecting objects in video in a streaming fashion. As opposed to applying per-frame convolutional neural network (CNN) based object detection, our proposed method called Objects in Video Enabler thRough LAbel Propagation (OVERLAP) needs to classify only a small fraction of all candidate proposals in every video frame through streaming clustering of object proposals and class-label propagation. Source code will be made available soon.

##### Abstract (translated by Google)
用于检测移动或静态视频对象的对象提议需要解决诸如速度，内存复杂度和时间一致性等问题。我们提出了一个高效的视频对象提议（VOP）生成方法，并展示了它在学习更好的视频对象检测器方面的功效。使用所提出的VOP学习的基于深度学习的视频对象检测器在Youtube-Objects数据集上实现了最先进的检测性能。我们进一步提出了一种可以有效地用于以流方式检测视频中的对象的VOP的聚类。与应用基于逐帧卷积神经网络（CNN）的对象检测相反，我们提出的在视频引擎中实现对象的方法（LAVER传播（OVERLAP））需要通过流聚类来对每个视频帧中的仅一小部分候选提议进行分类对象提议和类标签传播。源代码将很快提供。

##### URL
[https://arxiv.org/abs/1601.05447](https://arxiv.org/abs/1601.05447)

