---
layout: post
title: "Automatic Liver Lesion Segmentation Using A Deep Convolutional Neural Network Method"
date: 2017-04-24 13:58:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Xiao Han
mathjax: true
---

* content
{:toc}

##### Abstract
Liver lesion segmentation is an important step for liver cancer diagnosis, treatment planning and treatment evaluation. LiTS (Liver Tumor Segmentation Challenge) provides a common testbed for comparing different automatic liver lesion segmentation methods. We participate in this challenge by developing a deep convolutional neural network (DCNN) method. The particular DCNN model works in 2.5D in that it takes a stack of adjacent slices as input and produces the segmentation map corresponding to the center slice. The model has 32 layers in total and makes use of both long range concatenation connections of U-Net [1] and short-range residual connections from ResNet [2]. The model was trained using the 130 LiTS training datasets and achieved an average Dice score of 0.67 when evaluated on the 70 test CT scans, which ranked first for the LiTS challenge at the time of the ISBI 2017 conference.

##### Abstract (translated by Google)
肝脏病变分割是肝癌诊断，治疗计划和治疗评估的重要步骤。 LiTS（肝肿瘤分割挑战）为比较不同的自动肝脏病变分割方法提供了一个共同的试验台。我们通过开发深度卷积神经网络（DCNN）方法来参与这个挑战。特定的DCNN模型在2.5D中工作，因为它将一堆相邻的切片作为输入，并产生对应于中心切片的分割图。该模型共有32层，利用U-Net的长距离级联连接[1]和ResNet的短距离剩余连接[2]。该模型使用130个LiTS训练数据集进行训练，并且在70次CT扫描评估中获得0.67的平均Dice评分，在ISBI 2017年会议期间排名第一。

##### URL
[https://arxiv.org/abs/1704.07239](https://arxiv.org/abs/1704.07239)

##### PDF
[https://arxiv.org/pdf/1704.07239](https://arxiv.org/pdf/1704.07239)

