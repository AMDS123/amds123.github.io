---
layout: post
title: "Recurrent neural networks for aortic image sequence segmentation with sparse annotations"
date: 2018-08-01 11:20:54
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation GAN CNN RNN
author: Wenjia Bai, Hideaki Suzuki, Chen Qin, Giacomo Tarroni, Ozan Oktay, Paul M. Matthews, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of image sequences is an important task in medical image analysis, which enables clinicians to assess the anatomy and function of moving organs. However, direct application of a segmentation algorithm to each time frame of a sequence may ignore the temporal continuity inherent in the sequence. In this work, we propose an image sequence segmentation algorithm by combining a fully convolutional network with a recurrent neural network, which incorporates both spatial and temporal information into the segmentation task. A key challenge in training this network is that the available manual annotations are temporally sparse, which forbids end-to-end training. We address this challenge by performing non-rigid label propagation on the annotations and introducing an exponentially weighted loss function for training. Experiments on aortic MR image sequences demonstrate that the proposed method significantly improves both accuracy and temporal smoothness of segmentation, compared to a baseline method that utilises spatial information only. It achieves an average Dice metric of 0.960 for the ascending aorta and 0.953 for the descending aorta.

##### Abstract (translated by Google)
图像序列的分割是医学图像分析中的重要任务，其使临床医生能够评估运动器官的解剖学和功能。然而，将分割算法直接应用于序列的每个时间帧可以忽略序列中固有的时间连续性。在这项工作中，我们提出了一种图像序列分割算法，通过将完全卷积网络与递归神经网络相结合，将空间和时间信息结合到分割任务中。培训该网络的一个关键挑战是可用的手动注释在时间上是稀疏的，这禁止端到端的培训。我们通过在注释上执行非刚性标签传播并引入指数加权损失函数来解决这一挑战。对主动脉MR图像序列的实验表明，与仅利用空间信息的基线方法相比，所提出的方法显着改善了分割的准确性和时间平滑性。它实现了升主动脉的平均Dice度量为0.960，降主动脉的平均Dice度量为0.953。

##### URL
[https://arxiv.org/abs/1808.00273](https://arxiv.org/abs/1808.00273)

##### PDF
[https://arxiv.org/pdf/1808.00273](https://arxiv.org/pdf/1808.00273)

