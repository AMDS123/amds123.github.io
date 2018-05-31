---
layout: post
title: "Transfer Learning for Unseen Robot Detection and Joint Estimation on a Multi-Objective Convolutional Neural Network"
date: 2018-05-30 08:12:58
categories: arXiv_RO
tags: arXiv_RO CNN Transfer_Learning Classification Deep_Learning Detection Recognition
author: Justinas Miseikis, Inka Brijacak, Saeed Yahyanejad, Kyrre Glette, Ole Jakob Elle, Jim Torresen
mathjax: true
---

* content
{:toc}

##### Abstract
A significant problem of using deep learning techniques is the limited amount of data available for training. There are some datasets available for the popular problems like item recognition and classification or self-driving cars, however, it is very limited for the industrial robotics field. In previous work, we have trained a multi-objective Convolutional Neural Network (CNN) to identify the robot body in the image and estimate 3D positions of the joints by using just a 2D image, but it was limited to a range of robots produced by Universal Robots (UR). In this work, we extend our method to work with a new robot arm - Kuka LBR iiwa, which has a significantly different appearance and an additional joint. However, instead of collecting large datasets once again, we collect a number of smaller datasets containing a few hundred frames each and use transfer learning techniques on the CNN trained on UR robots to adapt it to a new robot having different shapes and visual features. We have proven that transfer learning is not only applicable in this field, but it requires smaller well-prepared training datasets, trains significantly faster and reaches similar accuracy compared to the original method, even improving it on some aspects.

##### Abstract (translated by Google)
使用深度学习技术的一个重要问题是可用于训练的数据量有限。有一些数据集可用于流行问题，如物品识别和分类或自动驾驶汽车，但是它对于工业机器人领域非常有限。在以前的工作中，我们已经训练了一个多目标卷积神经网络（CNN）来识别图像中的机器人身体并通过仅使用2D图像来估计关节的三维位置，但它仅限于一系列机器人通用机器人（UR）。在这项工作中，我们扩展了我们的方法，使用新型机器人手臂 -  Kuka LBR iiwa，它具有明显不同的外观和额外的关节。然而，我们不是再次收集大型数据集，而是收集许多包含几百帧的较小数据集，并使用在UR机器人上训练的CNN上的转移学习技术来使其适应具有不同形状和视觉特征的新机器人。我们已经证明，转移学习不仅适用于该领域，而且需要较小的准备好的训练数据集，训练速度明显更快，并且与原始方法相比具有相似的准确性，甚至可以在某些方面进行改进。

##### URL
[http://arxiv.org/abs/1805.11849](http://arxiv.org/abs/1805.11849)

##### PDF
[http://arxiv.org/pdf/1805.11849](http://arxiv.org/pdf/1805.11849)

