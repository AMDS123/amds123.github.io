---
layout: post
title: "StuffNet: Using 'Stuff' to Improve Object Detection"
date: 2017-01-30 03:10:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Samarth Brahmbhatt, Henrik I. Christensen, James Hays
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Convolutional Neural Network (CNN) based algorithm - StuffNet - for object detection. In addition to the standard convolutional features trained for region proposal and object detection [31], StuffNet uses convolutional features trained for segmentation of objects and 'stuff' (amorphous categories such as ground and water). Through experiments on Pascal VOC 2010, we show the importance of features learnt from stuff segmentation for improving object detection performance. StuffNet improves performance from 18.8% mAP to 23.9% mAP for small objects. We also devise a method to train StuffNet on datasets that do not have stuff segmentation labels. Through experiments on Pascal VOC 2007 and 2012, we demonstrate the effectiveness of this method and show that StuffNet also significantly improves object detection performance on such datasets.

##### Abstract (translated by Google)
我们提出了基于卷积神经网络（CNN）的算法 -  StuffNet  - 用于物体检测。 StuffNet除了为区域建议和目标检测训练的标准卷积特征之外，还使用卷积特征训练来分割对象和“东西”（无定形类如地面和水）。通过对Pascal VOC 2010的实验，我们展示了从东西分割学习的特征对于提高目标检测性能的重要性。 StuffNet将小型物体的性能从18.8％提高到23.9％。我们还设计了一个方法来训练没有东西分段标签的数据集上的StuffNet。通过对Pascal VOC 2007和2012的实验，我们证明了这种方法的有效性，并显示StuffNet也显着提高了这些数据集上的对象检测性能。

##### URL
[https://arxiv.org/abs/1610.05861](https://arxiv.org/abs/1610.05861)

##### PDF
[https://arxiv.org/pdf/1610.05861](https://arxiv.org/pdf/1610.05861)

