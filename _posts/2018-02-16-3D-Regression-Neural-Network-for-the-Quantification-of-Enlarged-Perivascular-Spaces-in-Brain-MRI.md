---
layout: post
title: "3D Regression Neural Network for the Quantification of Enlarged Perivascular Spaces in Brain MRI"
date: 2018-02-16 12:49:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN CNN Detection Relation
author: Florian Dubost, Hieab Adams, Gerda Bortsova, M. Arfan Ikram, Wiro Niessen, Meike Vernooij, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Enlarged perivascular spaces (EPVS) in the brain are an emerging imaging marker for cerebral small vessel disease, and have been shown to be related to increased risk of various neurological diseases, including stroke and dementia. Automatic quantification of EPVS would greatly help to advance research into its etiology and its potential as a risk indicator of disease. We propose a convolutional network regression method to quantify the extent of EPVS in the basal ganglia from 3D brain MRI. We first segment the basal ganglia and subsequently apply a 3D convolutional regression network designed for small object detection within this region of interest. The network takes an image as input, and outputs a quantification score of EPVS. The network has significantly more convolution operations than pooling ones and no final activation, allowing it to span the space of real numbers. We validated our approach using a dataset of 2000 brain MRI scans scored visually. Experiments with varying sizes of training and test sets showed that a good performance can be achieved with a training set of only 200 scans. With a training set of 1000 scans, the intraclass correlation coefficient (ICC) between our scoring method and the expert's visual score was 0.74. Our method outperforms by a large margin - more than 0.10 - four more conventional automated approaches based on intensities, scale-invariant feature transform, and random forest. We show that the network learns the structures of interest and investigate the influence of hyper-parameters on the performance. We also evaluate the reproducibility of our network using a set of 60 subjects scanned twice (scan-rescan reproducibility). On this set our network achieves an ICC of 0.93, while the intrarater agreement reaches 0.80. Furthermore, the automatic EPVS scoring correlates similarly to age as visual scoring.

##### Abstract (translated by Google)
脑部扩大的血管周围间隙（EPVS）是脑血管疾病的新兴影像学标志物，已被证明与各种神经系统疾病（包括中风和痴呆）风险增加有关。 EPVS的自动量化将大大有助于促进研究其病因及其作为疾病风险指标的潜力。我们提出了一种卷积网络回归方法来量化3D脑MRI对基底节区EPVS的程度。我们首先分割基底神经节，然后应用为这个感兴趣区域内的小物体检测设计的3D卷积回归网络。网络将图像作为输入，并输出EPVS的量化分数。网络的卷积操作比集中操作要多得多，并且没有最终的激活，从而允许它跨越实数的空间。我们验证了我们的方法，使用2000个脑部MRI扫描的数据集进行视觉评分。不同规模的训练和测试集的实验表明，只有200次扫描的训练集可以获得良好的性能。使用1000次扫描的训练集，我们的评分方法与专家的视觉评分之间的组内相关系数（ICC）为0.74。我们的方法的性能优于0.10  - 超过了传统的基于强度，尺度不变特征变换和随机森林的自动化方法。我们表明，网络学习感兴趣的结构，并调查超参数对性能的影响。我们还使用一套60名受试者扫描两次（扫描重新扫描重现性）评估我们网络的可重复性。在这个集合中，我们的网络实现了0.93的ICC，而intrarater协议达到了0.80。此外，自动EPVS评分与年龄与视觉评分类似。

##### URL
[https://arxiv.org/abs/1802.05914](https://arxiv.org/abs/1802.05914)

##### PDF
[https://arxiv.org/pdf/1802.05914](https://arxiv.org/pdf/1802.05914)

