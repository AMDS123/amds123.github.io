---
layout: post
title: "Crowd counting via scale-adaptive convolutional neural network"
date: 2017-11-21 06:54:10
categories: arXiv_CV
tags: arXiv_CV CNN
author: Lu Zhang, Miaojing Shi, Qiaobo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The task of crowd counting is to automatically estimate the pedestrian number in crowd images. To cope with the scale and perspective changes that commonly exist in crowd images, state-of-the-art approaches employ multi-column CNN architectures to regress density maps of crowd images. Multiple columns have different receptive fields corresponding to pedestrians (heads) of different scales. We instead propose a scale-adaptive CNN (SaCNN) architecture with a backbone of fixed small receptive fields. We extract feature maps from multiple layers and adapt them to have the same output size; we combine them to produce the final density map. The number of people is computed by integrating the density map. We also introduce a relative count loss along with the density map loss to improve the network generalization on crowd scenes with few pedestrians, where most representative approaches perform poorly on. We conduct extensive experiments on the ShanghaiTech, UCF_CC_50 and WorldExpo datasets as well as a new dataset SmartCity that we collect for crowd scenes with few people. The results demonstrate significant improvements of SaCNN over the state-of-the-art.

##### Abstract (translated by Google)
人群统计的任务是自动估算人群图像中的行人数量。为了应对人群图像中普遍存在的尺度和视角变化，最先进的方法采用多列CNN架构来回归人群图像的密度图。多列具有与不同尺度的行人（头部）对应的不同的感受野。相反，我们提出了一个规模适应性的CNN（SaCNN）架构，它具有固定的小接受域的骨干。我们从多个图层中提取特征图，并调整它们以获得相同的输出大小。我们将它们结合起来以产生最终的密度图。通过对密度图进行积分来计算人数。我们还介绍了相对计数损失和密度映射损失，以改善在行人少的人群场景中的网络泛化，其中大多数代表性方法表现不佳。我们在ShanghaiTech，UCF_CC_50和WorldExpo数据集上进行了广泛的实验，以及我们为少数人群收集的新数据集SmartCity。结果表明SaCNN比现有技术有显着的改进。

##### URL
[https://arxiv.org/abs/1711.04433](https://arxiv.org/abs/1711.04433)

##### PDF
[https://arxiv.org/pdf/1711.04433](https://arxiv.org/pdf/1711.04433)

