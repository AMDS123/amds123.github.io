---
layout: post
title: "Too Far to See? Not Really! --- Pedestrian Detection with Scale-aware Localization Policy"
date: 2017-09-01 10:32:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Prediction Detection
author: Xiaowei Zhang, Li Cheng, Bo Li, Hai-Miao Hu
mathjax: true
---

* content
{:toc}

##### Abstract
A major bottleneck of pedestrian detection lies on the sharp performance deterioration in the presence of small-size pedestrians that are relatively far from the camera. Motivated by the observation that pedestrians of disparate spatial scales exhibit distinct visual appearances, we propose in this paper an active pedestrian detector that explicitly operates over multiple-layer neuronal representations of the input still image. More specifically, convolutional neural nets such as ResNet and faster R-CNNs are exploited to provide a rich and discriminative hierarchy of feature representations as well as initial pedestrian proposals. Here each pedestrian observation of distinct size could be best characterized in terms of the ResNet feature representation at a certain layer of the hierarchy; Meanwhile, initial pedestrian proposals are attained by faster R-CNNs techniques, i.e. region proposal network and follow-up region of interesting pooling layer employed right after the specific ResNet convolutional layer of interest, to produce joint predictions on the bounding-box proposals' locations and categories (i.e. pedestrian or not). This is engaged as input to our active detector where for each initial pedestrian proposal, a sequence of coordinate transformation actions is carried out to determine its proper x-y 2D location and layer of feature representation, or eventually terminated as being background. Empirically our approach is demonstrated to produce overall lower detection errors on widely-used benchmarks, and it works particularly well with far-scale pedestrians. For example, compared with 60.51% log-average miss rate of the state-of-the-art MS-CNN for far-scale pedestrians (those below 80 pixels in bounding-box height) of the Caltech benchmark, the miss rate of our approach is 41.85%, with a notable reduction of 18.68%.

##### Abstract (translated by Google)
行人检测的一个主要瓶颈在于距离摄像机较远的小型行人的急剧性能下降。由于观察到不同空间尺度的行人表现出不同的视觉外观，我们在本文中提出了一种主动行人检测器，其明确地对输入静止图像的多层神经元表示进行操作。更具体地说，诸如ResNet和更快的R-CNN之类的卷积神经网络被利用来提供丰富和有区别的特征表示以及初始行人建议。在这里，每个不同大小的行人观察可以在层次结构的某一层的ResNet特征表示方面得到最好的表征;同时，通过更快的R-CNN技术，即在特定ResNet卷积层之后使用的区域提议网络和有趣汇聚层的后续区域，对边界框提议的位置产生联合预测和类别（即行人与否）。这被作为输入到我们的主动探测器，其中对于每个初始步行者建议，执行一系列坐标变换动作以确定其合适的x-y二维位置和特征表示层，或者最终终止为背景。经验证明，我们的方法被证明在广泛使用的基准测试中产生较低的检测错误，对于远程行人来说，它特别适用。例如，加州理工学院基准测试结果显示，对于远程行人（包围盒高度低于80像素）的最新MS-CNN的对数平均失败率为60.51％，我们的失误率的做法是41.85％，显着减少了18.68％。

##### URL
[https://arxiv.org/abs/1709.00235](https://arxiv.org/abs/1709.00235)

##### PDF
[https://arxiv.org/pdf/1709.00235](https://arxiv.org/pdf/1709.00235)

