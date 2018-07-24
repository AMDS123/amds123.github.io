---
layout: post
title: "Occlusion-aware R-CNN: Detecting Pedestrians in a Crowd"
date: 2018-07-23 02:36:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Shifeng Zhang, Longyin Wen, Xiao Bian, Zhen Lei, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Pedestrian detection in crowded scenes is a challenging problem since the pedestrians often gather together and occlude each other. In this paper, we propose a new occlusion-aware R-CNN (OR-CNN) to improve the detection accuracy in the crowd. Specifically, we design a new aggregation loss to enforce proposals to be close and locate compactly to the corresponding objects. Meanwhile, we use a new part occlusion-aware region of interest (PORoI) pooling unit to replace the RoI pooling layer in order to integrate the prior structure information of human body with visibility prediction into the network to handle occlusion. Our detector is trained in an end-to-end fashion, which achieves state-of-the-art results on three pedestrian detection datasets, i.e., CityPersons, ETH, and INRIA, and performs on-pair with the state-of-the-arts on Caltech.

##### Abstract (translated by Google)
在拥挤的场景中的行人检测是一个具有挑战性的问题，因为行人经常聚集在一起并相互遮挡。在本文中，我们提出了一种新的遮挡感知R-CNN（OR-CNN）来提高人群中的检测精度。具体来说，我们设计了一个新的聚合损失来强制提出要近距离并紧凑地定位到相应的对象。同时，我们使用新的部分遮挡感知区域（PORoI）汇集单元来替换RoI汇集层，以便将人体的先前结构信息与可见性预测集成到网络中以处理遮挡。我们的探测器以端到端的方式进行训练，在三个行人检测数据集（即CityPersons，ETH和INRIA）上实现最先进的结果，并与状态进行配对。 - 加州理工学院。

##### URL
[http://arxiv.org/abs/1807.08407](http://arxiv.org/abs/1807.08407)

##### PDF
[http://arxiv.org/pdf/1807.08407](http://arxiv.org/pdf/1807.08407)

