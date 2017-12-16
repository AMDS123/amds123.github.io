---
layout: post
title: "The Stixel world: A medium-level representation of traffic scenes"
date: 2017-04-02 10:38:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Face Tracking Detection
author: Marius Cordts, Timo Rehfeld, Lukas Schneider, David Pfeiffer, Markus Enzweiler, Stefan Roth, Marc Pollefeys, Uwe Franke
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress in advanced driver assistance systems and the race towards autonomous vehicles is mainly driven by two factors: (1) increasingly sophisticated algorithms that interpret the environment around the vehicle and react accordingly, and (2) the continuous improvements of sensor technology itself. In terms of cameras, these improvements typically include higher spatial resolution, which as a consequence requires more data to be processed. The trend to add multiple cameras to cover the entire surrounding of the vehicle is not conducive in that matter. At the same time, an increasing number of special purpose algorithms need access to the sensor input data to correctly interpret the various complex situations that can occur, particularly in urban traffic. By observing those trends, it becomes clear that a key challenge for vision architectures in intelligent vehicles is to share computational resources. We believe this challenge should be faced by introducing a representation of the sensory data that provides compressed and structured access to all relevant visual content of the scene. The Stixel World discussed in this paper is such a representation. It is a medium-level model of the environment that is specifically designed to compress information about obstacles by leveraging the typical layout of outdoor traffic scenes. It has proven useful for a multitude of automotive vision applications, including object detection, tracking, segmentation, and mapping. In this paper, we summarize the ideas behind the model and generalize it to take into account multiple dense input streams: the image itself, stereo depth maps, and semantic class probability maps that can be generated, e.g., by CNNs. Our generalization is embedded into a novel mathematical formulation for the Stixel model. We further sketch how the free parameters of the model can be learned using structured SVMs.

##### Abstract (translated by Google)
先进的驾驶辅助系统和自主车辆的竞赛最近的进展主要由两个因素驱动：（1）越来越复杂的算法，解释车辆周围的环境并作出相应的反应;（2）传感器技术本身的不断改进。就照相机而言，这些改进通常包括更高的空间分辨率，因此需要更多的数据进行处理。添加多台摄像机以覆盖整个车辆周围的趋势不利于此。同时，越来越多的专用算法需要访问传感器输入数据来正确解释可能发生的各种复杂情况，特别是在城市交通中。通过观察这些趋势，很明显，智能车辆的视觉体系结构的一个关键挑战是共享计算资源。我们认为，应该面对这个挑战，通过引入感官数据的表示，提供对场景的所有相关视觉内容的压缩和结构化访问。本文讨论的斯蒂克塞尔世界就是这样一种表象。这是一个中等规模的环境模型，专门用于利用户外交通场景的典型布局压缩障碍信息。它已被证明是有用的多种汽车视觉应用，包括对象检测，跟踪，分割和映射。在本文中，我们总结了模型背后的思想，并将其推广到考虑多个密集输入流：图像本身，立体声深度图以及可由CNN生成的语义类概率图。我们的推广被嵌入到Stixel模型的一个新的数学公式中。我们进一步描绘了如何使用结构化SVM学习模型的自由参数。

##### URL
[https://arxiv.org/abs/1704.00280](https://arxiv.org/abs/1704.00280)

##### PDF
[https://arxiv.org/pdf/1704.00280](https://arxiv.org/pdf/1704.00280)

