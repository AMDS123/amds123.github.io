---
layout: post
title: "Fast Convergence for Object Detection by Learning how to Combine Error Functions"
date: 2018-08-13 22:20:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Benjamin Schnieders, Karl Tuyls
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce an innovative method to improve the convergence speed and accuracy of object detection neural networks. Our approach, CONVERGE-FAST-AUXNET, is based on employing multiple, dependent loss metrics and weighting them optimally using an on-line trained auxiliary network. Experiments are performed in the well-known RoboCup@Work challenge environment. A fully convolutional segmentation network is trained on detecting objects' pickup points. We empirically obtain an approximate measure for the rate of success of a robotic pickup operation based on the accuracy of the object detection network. Our experiments show that adding an optimally weighted Euclidean distance loss to a network trained on the commonly used Intersection over Union (IoU) metric reduces the convergence time by 42.48%. The estimated pickup rate is improved by 39.90%. Compared to state-of-the-art task weighting methods, the improvement is 24.5% in convergence, and 15.8% on the estimated pickup rate.

##### Abstract (translated by Google)
在本文中，我们介绍了一种创新方法，以提高目标检测神经网络的收敛速度和准确性。我们的方法CONVERGE-FAST-AUXNET基于采用多个相关损耗度量，并使用在线训练的辅助网络对其进行最佳加权。实验在众所周知的RoboCup @ Work挑战环境中进行。完全卷积分割网络训练有关检测物体的拾取点。我们凭经验检测网络的精度，凭经验获得机器人拾取操作成功率的近似测量。我们的实验表明，将最佳加权欧氏距离损失添加到经常使用的联合交叉（IoU）度量标准训练的网络上，可使收敛时间减少42.48％。估计的取货率提高了39.90％。与最先进的任务加权方法相比，收敛率提高了24.5％，估计提取率提高了15.8％。

##### URL
[http://arxiv.org/abs/1808.04480](http://arxiv.org/abs/1808.04480)

##### PDF
[http://arxiv.org/pdf/1808.04480](http://arxiv.org/pdf/1808.04480)

