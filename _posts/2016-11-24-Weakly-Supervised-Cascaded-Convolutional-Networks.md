---
layout: post
title: "Weakly Supervised Cascaded Convolutional Networks"
date: 2016-11-24 17:07:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised CNN Classification Detection
author: Ali Diba, Vivek Sharma, Ali Pazandeh, Hamed Pirsiavash, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a challenging task in visual understanding domain, and even more so if the supervision is to be weak. Recently, few efforts to handle the task without expensive human annotations is established by promising deep neural network. A new architecture of cascaded networks is proposed to learn a convolutional neural network (CNN) under such conditions. We introduce two such architectures, with either two cascade stages or three which are trained in an end-to-end pipeline. The first stage of both architectures extracts best candidate of class specific region proposals by training a fully convolutional network. In the case of the three stage architecture, the middle stage provides object segmentation, using the output of the activation maps of first stage. The final stage of both architectures is a part of a convolutional neural network that performs multiple instance learning on proposals extracted in the previous stage(s). Our experiments on the PASCAL VOC 2007, 2010, 2012 and large scale object datasets, ILSVRC 2013, 2014 datasets show improvements in the areas of weakly-supervised object detection, classification and localization.

##### Abstract (translated by Google)
目标检测在视觉理解领域是一项具有挑战性的任务，如果监督力量薄弱，更是如此。最近，没有昂贵的人类注释处理任务的努力是有前途的深层神经网络建立。在此条件下，提出了一种新的级联网络结构来学习卷积神经网络（CNN）。我们引入两个这样的架构，或者是两个级联阶段，或者是三个在端到端流水线上进行培训的阶段。两个架构的第一阶段通过训练一个完全卷积网络来提取类别特定区域提议的最佳候选者。在三阶段体系结构的情况下，中间阶段使用第一阶段的激活图的输出提供对象分割。两种体系结构的最后阶段是卷积神经网络的一部分，对前一阶段提取的提案进行多重实例学习。我们在PASCAL VOC 2007,2010,2012和大型目标数据集ILSVRC 2013,2014数据集上进行的实验显示，在弱监督目标检测，分类和定位方面有所改进。

##### URL
[https://arxiv.org/abs/1611.08258](https://arxiv.org/abs/1611.08258)

##### PDF
[https://arxiv.org/pdf/1611.08258](https://arxiv.org/pdf/1611.08258)

