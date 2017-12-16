---
layout: post
title: "Self-Supervised Learning for Spinal MRIs"
date: 2017-08-01 14:44:48
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Amir Jamaludin, Timor Kadir, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
A significant proportion of patients scanned in a clinical setting have follow-up scans. We show in this work that such longitudinal scans alone can be used as a form of 'free' self-supervision for training a deep network. We demonstrate this self-supervised learning for the case of T2-weighted sagittal lumbar Magnetic Resonance Images (MRIs). A Siamese convolutional neural network (CNN) is trained using two losses: (i) a contrastive loss on whether the scan is of the same person (i.e. longitudinal) or not, together with (ii) a classification loss on predicting the level of vertebral bodies. The performance of this pre-trained network is then assessed on a grading classification task. We experiment on a dataset of 1016 subjects, 423 possessing follow-up scans, with the end goal of learning the disc degeneration radiological gradings attached to the intervertebral discs. We show that the performance of the pre-trained CNN on the supervised classification task is (i) superior to that of a network trained from scratch; and (ii) requires far fewer annotated training samples to reach an equivalent performance to that of the network trained from scratch.

##### Abstract (translated by Google)
在临床中扫描的患者中有相当比例的患者有随访扫描。我们在这项工作中表明，这样的纵向扫描本身可以用作训练深度网络的“自由”自我监督的一种形式。我们证明这种自我监督学习的T2加权矢状腰椎磁共振图像（MRIs）的情况。一个连体卷积神经网络（CNN）使用两种损失进行训练：（i）扫描是否是同一个人（即纵向）的对比损失，连同（ii）预测椎骨水平的分类损失身体。这个预先训练的网络的表现然后评估分级分类任务。我们对1016名受试者的数据集进行了实验，其中423名具有随访扫描，最终目的是学习椎间盘附着的椎间盘退变放射分级。我们表明，预先训练的CNN在监督分类任务上的性能（i）优于从头开始训练的网络的性能; （ii）需要少得多的注释培训样本才能达到与从零开始培训的网络相同的绩效。

##### URL
[https://arxiv.org/abs/1708.00367](https://arxiv.org/abs/1708.00367)

##### PDF
[https://arxiv.org/pdf/1708.00367](https://arxiv.org/pdf/1708.00367)

