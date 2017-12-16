---
layout: post
title: "SonoNet: Real-Time Detection and Localisation of Fetal Standard Scan Planes in Freehand Ultrasound"
date: 2017-07-25 16:12:50
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Christian F. Baumgartner, Konstantinos Kamnitsas, Jacqueline Matthew, Tara P. Fletcher, Sandra Smith, Lisa M. Koch, Bernhard Kainz, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying and interpreting fetal standard scan planes during 2D ultrasound mid-pregnancy examinations are highly complex tasks which require years of training. Apart from guiding the probe to the correct location, it can be equally difficult for a non-expert to identify relevant structures within the image. Automatic image processing can provide tools to help experienced as well as inexperienced operators with these tasks. In this paper, we propose a novel method based on convolutional neural networks which can automatically detect 13 fetal standard views in freehand 2D ultrasound data as well as provide a localisation of the fetal structures via a bounding box. An important contribution is that the network learns to localise the target anatomy using weak supervision based on image-level labels only. The network architecture is designed to operate in real-time while providing optimal output for the localisation task. We present results for real-time annotation, retrospective frame retrieval from saved videos, and localisation on a very large and challenging dataset consisting of images and video recordings of full clinical anomaly screenings. We found that the proposed method achieved an average F1-score of 0.798 in a realistic classification experiment modelling real-time detection, and obtained a 90.09% accuracy for retrospective frame retrieval. Moreover, an accuracy of 77.8% was achieved on the localisation task.

##### Abstract (translated by Google)
在二维超声中期妊娠检查期间识别和解释胎儿标准扫描平面是非常复杂的任务，需要多年的训练。除了将探针引导到正确的位置之外，非专家同样难以识别图像内的相关结构。自动图像处理可以提供工具来帮助经验丰富的经验丰富的操作人员完成这些任务。在本文中，我们提出了一种基于卷积神经网络的新方法，可以自动检测手绘2D超声数据中的13个胎儿标准视图，并通过边界框提供胎儿结构的定位。一个重要的贡献是网络学习只使用基于图像级标签的弱监督来定位目标解剖结构。网络体系结构旨在实时运行，同时为本地化任务提供最佳输出。我们提供实时注释的结果，从已保存的视频回顾框架检索，以及对由完整临床异常筛选的图像和视频记录组成的非常大且具有挑战性的数据集进行定位。我们发现，所提出的方法在一个实际的分类实验建模实时检测中实现了平均F1分数为0.798，并且为回顾性帧检索获得了90.09％的准确度。此外，本地化任务达到了77.8％的准确率。

##### URL
[https://arxiv.org/abs/1612.05601](https://arxiv.org/abs/1612.05601)

##### PDF
[https://arxiv.org/pdf/1612.05601](https://arxiv.org/pdf/1612.05601)

