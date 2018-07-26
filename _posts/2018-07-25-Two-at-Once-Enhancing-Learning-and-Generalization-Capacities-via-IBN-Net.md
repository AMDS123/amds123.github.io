---
layout: post
title: "Two at Once: Enhancing Learning and Generalization Capacities via IBN-Net"
date: 2018-07-25 05:51:15
categories: arXiv_CV
tags: arXiv_CV CNN
author: Xingang Pan, Ping Luo, Jianping Shi, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have achieved great successes in many computer vision problems. Unlike existing works that designed CNN architectures to improve performance on a single task of a single domain and not generalizable, we present IBN-Net, a novel convolutional architecture, which remarkably enhances a CNN's modeling ability on one domain (e.g. Cityscapes) as well as its generalization capacity on another domain (e.g. GTA5) without finetuning. IBN-Net carefully integrates Instance Normalization (IN) and Batch Normalization (BN) as building blocks, and can be wrapped into many advanced deep networks to improve their performances. This work has three key contributions. (1) By delving into IN and BN, we disclose that IN learns features that are invariant to appearance changes, such as colors, styles, and virtuality/reality, while BN is essential for preserving content related information. (2) IBN-Net can be applied to many advanced deep architectures, such as DenseNet, ResNet, ResNeXt, and SENet, and consistently improve their performance without increasing computational cost. (3) When applying the trained networks to new domains, e.g. from GTA5 to Cityscapes, IBN-Net achieves comparable improvements as domain adaptation methods, even without using data from the target domain. With IBN-Net, we won the 1st place on the WAD 2018 Challenge Drivable Area track, with an mIoU of 86.18%.

##### Abstract (translated by Google)
卷积神经网络（CNN）在许多计算机视觉问题上取得了巨大成功。与设计CNN架构以提高单个域的单个任务的性能而不是一般化的现有工作不同，我们提出了IBN-Net，一种新颖的卷积架构，它显着增强了CNN在一个域（例如Cityscapes）上的建模能力以及它在另一个域（例如GTA5）上的泛化能力，没有微调。 IBN-Net仔细地将实例规范化（IN）和批量规范化（BN）集成为构建块，并且可以包含在许多高级深度网络中以提高其性能。这项工作有三个关键贡献。 （1）通过深入研究IN和BN，我们发现IN学习了外观变化不变的特征，如颜色，样式和虚拟/现实，而BN对于保存内容相关信息至关重要。 （2）IBN-Net可以应用于许多先进的深层体系结构，如DenseNet，ResNet，ResNeXt和SENet，并且在不增加计算成本的情况下不断提高其性能。 （3）将训练好的网络应用于新域时，例如从GTA5到Cityscapes，IBN-Net实现了与域适应方法相当的改进，即使不使用来自目标域的数据。凭借IBN-Net，我们赢得了WAD 2018 Challenge Drivable Area赛道的第一名，其中mIoU为86.18％。

##### URL
[http://arxiv.org/abs/1807.09441](http://arxiv.org/abs/1807.09441)

##### PDF
[http://arxiv.org/pdf/1807.09441](http://arxiv.org/pdf/1807.09441)

