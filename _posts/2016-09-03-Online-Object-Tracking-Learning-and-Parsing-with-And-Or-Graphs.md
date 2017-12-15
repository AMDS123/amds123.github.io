---
layout: post
title: "Online Object Tracking, Learning and Parsing with And-Or Graphs"
date: 2016-09-03 00:26:58
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Inference
author: Tianfu Wu, Yang Lu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method, called AOGTracker, for simultaneously tracking, learning and parsing (TLP) of unknown objects in video sequences with a hierarchical and compositional And-Or graph (AOG) representation. %The AOG captures both structural and appearance variations of a target object in a principled way. The TLP method is formulated in the Bayesian framework with a spatial and a temporal dynamic programming (DP) algorithms inferring object bounding boxes on-the-fly. During online learning, the AOG is discriminatively learned using latent SVM to account for appearance (e.g., lighting and partial occlusion) and structural (e.g., different poses and viewpoints) variations of a tracked object, as well as distractors (e.g., similar objects) in background. Three key issues in online inference and learning are addressed: (i) maintaining purity of positive and negative examples collected online, (ii) controling model complexity in latent structure learning, and (iii) identifying critical moments to re-learn the structure of AOG based on its intrackability. The intrackability measures uncertainty of an AOG based on its score maps in a frame. In experiments, our AOGTracker is tested on two popular tracking benchmarks with the same parameter setting: the TB-100/50/CVPR2013 benchmarks, and the VOT benchmarks --- VOT 2013, 2014, 2015 and TIR2015 (thermal imagery tracking). In the former, our AOGTracker outperforms state-of-the-art tracking algorithms including two trackers based on deep convolutional network. In the latter, our AOGTracker outperforms all other trackers in VOT2013 and is comparable to the state-of-the-art methods in VOT2014, 2015 and TIR2015.

##### Abstract (translated by Google)
本文提出了一种称为AOGTracker的方法，用于在视频序列中利用分层和组合的或图（AOG）表示来同时跟踪，学习和解析（TLP）未知对象。 ％AOG以原理的方式捕捉目标对象的结构和外观变化。 TLP方法在贝叶斯框架中使用空间和时间动态规划（DP）算法在运行中推断对象边界框。在在线学习期间，使用潜在SVM来区分性地学习AOG以说明被跟踪对象（例如，类似对象）的外观（例如，照明和部分遮挡）和结构（例如，不同的姿势和视点）变化，在背景中。解决在线推理和学习中的三个关键问题：（i）保持在线收集的正面和负面实例的纯度，（ii）控制潜在结构学习中的模型复杂性，以及（iii）识别重新学习AOG结构的关键时刻基于其不可靠性。基于其分数图在一个框架内，Ack的不可靠度测量AOG的不确定性。在实验中，我们的AOGTracker在两个流行的跟踪基准上进行了测试，具有相同的参数设置：TB-100/50 / CVPR2013基准，以及VOT 2013,2014,2015和TIR2015（热成像跟踪）基准。在前者中，我们的AOGTracker优于最先进的跟踪算法，包括两个基于深度卷积网络的跟踪器。在后者中，我们的AOGTracker优于VOT2013中的所有其他跟踪器，并且与VOT2014,2015和TIR2015中的最新方法相当。

##### URL
[https://arxiv.org/abs/1509.08067](https://arxiv.org/abs/1509.08067)

##### PDF
[https://arxiv.org/pdf/1509.08067](https://arxiv.org/pdf/1509.08067)

