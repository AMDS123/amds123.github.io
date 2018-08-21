---
layout: post
title: "Deep Multiple Instance Learning for Airplane Detection in High Resolution Imagery"
date: 2018-08-19 07:36:22
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Detection
author: Mohammad Reza Mohammadi
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic airplane detection in aerial imagery has a variety of applications. Two of the major challenges in this area are variations in scale and direction of the airplanes. In order to solve these challenges, we present a rotation-and-scale invariant airplane proposal generator. This proposal generator is developed based on the symmetric and regular boundaries of airplanes from the top view called symmetric line segments (SLS). Then, the generated proposals are used to train a deep convolutional neural network for removing non-airplane proposals. Since each airplane can have multiple SLS proposals, where some of them are not in the direction of the fuselage, we collect all proposals correspond to one ground truth as a positive bag and the others as the negative instances. To have multiple instance deep learning, we modify the training approach of the network to learn from each positive bag at least one instance as well as all negative instances. Finally, we employ non-maximum suppression to remove duplicate detections. Our experiments on NWPU VHR-10 dataset show that our method is a promising approach for automatic airplane detection in very high resolution images. Moreover, the proposed algorithm can estimate the direction of the airplanes using box-level annotations as an extra achievement.

##### Abstract (translated by Google)
航拍图像中的自动飞机检测具有多种应用。该领域的两个主要挑战是飞机的规模和方向的变化。为了解决这些挑战，我们提出了一种旋转和尺度不变的飞机建议发生器。该提议生成器是基于顶视图中称为对称线段（SLS）的飞机的对称和规则边界而开发的。然后，生成的提议用于训练深度卷积神经网络以移除非飞机提议。由于每架飞机可以有多个SLS建议，其中一些不在机身的方向，我们收集所有建议对应一个基础事实作为一个积极的包，其他作为负面实例。为了进行多实例深度学习，我们修改了网络的训练方法，以便从每个正面包中学习至少一个实例以及所有负面实例。最后，我们使用非最大抑制来删除重复检测。我们对NWPU VHR-10数据集的实验表明，我们的方法是一种很有前途的方法，可用于高分辨率图像中的自动飞机检测。此外，所提出的算法可以使用盒级注释来估计飞机的方向作为额外的成就。

##### URL
[http://arxiv.org/abs/1808.06178](http://arxiv.org/abs/1808.06178)

##### PDF
[http://arxiv.org/pdf/1808.06178](http://arxiv.org/pdf/1808.06178)

