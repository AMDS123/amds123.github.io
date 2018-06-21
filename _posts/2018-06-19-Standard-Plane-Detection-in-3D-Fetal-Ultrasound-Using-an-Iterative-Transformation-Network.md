---
layout: post
title: "Standard Plane Detection in 3D Fetal Ultrasound Using an Iterative Transformation Network"
date: 2018-06-19 22:29:20
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Inference Classification Detection Relation
author: Yuanwei Li, Bishesh Khanal, Benjamin Hou, Amir Alansary, Juan J. Cerrolaza, Matthew Sinclair, Jacqueline Matthew, Chandni Gupta, Caroline Knight, Bernhard Kainz, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Standard scan plane detection in fetal brain ultrasound (US) forms a crucial step in the assessment of fetal development. In clinical settings, this is done by manually manoeuvring a 2D probe to the desired scan plane. With the advent of 3D US, the entire fetal brain volume containing these standard planes can be easily acquired. However, manual standard plane identification in 3D volume is labour-intensive and requires expert knowledge of fetal anatomy. We propose a new Iterative Transformation Network (ITN) for the automatic detection of standard planes in 3D volumes. ITN uses a convolutional neural network to learn the relationship between a 2D plane image and the transformation parameters required to move that plane towards the location/orientation of the standard plane in the 3D volume. During inference, the current plane image is passed iteratively to the network until it converges to the standard plane location. We explore the effect of using different transformation representations as regression outputs of ITN. Under a multi-task learning framework, we introduce additional classification probability outputs to the network to act as confidence measures for the regressed transformation parameters in order to further improve the localisation accuracy. When evaluated on 72 US volumes of fetal brain, our method achieves an error of 3.83mm/12.7 degrees and 3.80mm/12.6 degrees for the transventricular and transcerebellar planes respectively and takes 0.46s per plane.

##### Abstract (translated by Google)
胎儿脑部超声（US）中的标准扫描平面检测是评估胎儿发育的关键步骤。在临床设置中，这是通过手动操纵二维探头到所需的扫描平面来完成的。随着3D美国的出现，包含这些标准平面的整个胎儿脑容量可以容易地获得。然而，3D体积中的手动标准平面识别是劳动密集型的并且需要胎儿解剖学方面的专业知识。我们提出了一种新的迭代转换网络（ITN），用于自动检测3D卷中的标准平面。 ITN使用卷积神经网络来学习2D平面图像与将该平面移动到3D体积中标准平面的位置/方向所需的变换参数之间的关系。在推断过程中，当前平面图像迭代地传递到网络，直到它收敛到标准平面位置。我们探索使用不同变换表示作为ITN的回归输出的效果。在多任务学习框架下，我们向网络引入附加的分类概率输出，作为回归变换参数的置信度量度，以进一步提高定位精度。当对72个美国胎儿脑部进行评估时，我们的方法分别对于跨室内和小脑平面的平面分别达到3.83mm / 12.7和3.80mm / 12.6度的误差，并且每个平面的误差为0.46s。

##### URL
[http://arxiv.org/abs/1806.07486](http://arxiv.org/abs/1806.07486)

##### PDF
[http://arxiv.org/pdf/1806.07486](http://arxiv.org/pdf/1806.07486)

