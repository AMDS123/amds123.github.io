---
layout: post
title: "End-to-end Multi-Modal Multi-Task Vehicle Control for Self-Driving Cars with Visual Perception"
date: 2018-01-20 21:59:08
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhengyuan Yang, Yixuan Zhang, Jerry Yu, Junjie Cai, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) have been successfully applied to autonomous driving tasks, many in an end-to-end manner. Previous end-to-end steering control methods take an image or an image sequence as the input and directly predict the steering angle with CNN. Although single task learning on steering angles has reported good performances, the steering angle alone is not sufficient for vehicle control. In this work, we propose a multi-task learning framework to predict the steering angle and speed control simultaneously in an end-to-end manner. Since it is nontrivial to predict accurate speed values with only visual inputs, we first propose a network to predict discrete speed commands and steering angles with image sequences. Moreover, we propose a multi-modal multi-task network to predict speed values and steering angles by taking previous feedback speeds and visual recordings as inputs. Experiments are conducted on the public Udacity dataset and a newly collected SAIC dataset. Results show that the proposed model predicts steering angles and speed values accurately. Furthermore, we improve the failure data synthesis methods to solve the problem of error accumulation in real road tests.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成功应用于自主驾驶任务，许多以端到端的方式进行。先前的端到端转向控制方法以图像或图像序列作为输入并直接预测与CNN的转向角。尽管转向角度上的单一任务学习已经表现出良好的性能，但是转向角本身并不足以用于车辆控制。在这项工作中，我们提出了一个多任务学习框架，以端到端的方式同时预测转向角度和速度控制。由于仅用可视输入来预测准确的速度值是不平凡的，所以我们首先提出一种网络来预测离散的速度命令和具有图像序列的转向角度。此外，我们提出了一个多模式多任务网络，通过采用以前的反馈速度和视频录像作为输入来预测速度值和转向角度。实验在公共Udacity数据集和新收集的SAIC数据集上进行。结果表明，该模型能准确预测转向角度和速度值。此外，我们改进了故障数据综合方法，以解决实际道路测试中的错误积累问题。

##### URL
[https://arxiv.org/abs/1801.06734](https://arxiv.org/abs/1801.06734)

##### PDF
[https://arxiv.org/pdf/1801.06734](https://arxiv.org/pdf/1801.06734)

