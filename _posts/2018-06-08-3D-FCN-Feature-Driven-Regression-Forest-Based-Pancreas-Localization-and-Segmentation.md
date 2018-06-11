---
layout: post
title: "3D FCN Feature Driven Regression Forest-Based Pancreas Localization and Segmentation"
date: 2018-06-08 08:34:30
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: Masahiro Oda, Natsuki Shimizu, Holger R. Roth, Ken&#x27;ichi Karasawa, Takayuki Kitasaka, Kazunari Misawa, Michitaka Fujiwara, Daniel Rueckert, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a fully automated atlas-based pancreas segmentation method from CT volumes utilizing 3D fully convolutional network (FCN) feature-based pancreas localization. Segmentation of the pancreas is difficult because it has larger inter-patient spatial variations than other organs. Previous pancreas segmentation methods failed to deal with such variations. We propose a fully automated pancreas segmentation method that contains novel localization and segmentation. Since the pancreas neighbors many other organs, its position and size are strongly related to the positions of the surrounding organs. We estimate the position and the size of the pancreas (localized) from global features by regression forests. As global features, we use intensity differences and 3D FCN deep learned features, which include automatically extracted essential features for segmentation. We chose 3D FCN features from a trained 3D U-Net, which is trained to perform multi-organ segmentation. The global features include both the pancreas and surrounding organ information. After localization, a patient-specific probabilistic atlas-based pancreas segmentation is performed. In evaluation results with 146 CT volumes, we achieved 60.6% of the Jaccard index and 73.9% of the Dice overlap.

##### Abstract (translated by Google)
本文提出了一种全自动的基于Atlas的胰腺分割方法，利用基于3D全卷积网络（FCN）特征的胰腺定位的CT体积。胰腺的分割很困难，因为它比其他器官具有更大的患者间空间变化。先前的胰腺分割方法未能处理这种变化。我们提出了一种全自动胰腺分割方法，其中包含新颖的定位和分割。由于胰腺邻近许多其他器官，其位置和大小与周围器官的位置密切相关。我们通过回归森林估计胰腺的位置和大小（局部化）。作为全局特征，我们使用强度差异和3D FCN深度学习特征，其中包括自动提取的分割基本特征。我们从训练过的3D U-Net中选择了3D FCN特征，训练完成多器官分割。全球特征包括胰腺和周围器官信息。本地化后，执行基于患者特异性概率图谱的胰腺分割。在146个CT量的评估结果中，我们达到Jaccard指数的60.6％和骰子重叠的73.9％。

##### URL
[http://arxiv.org/abs/1806.03019](http://arxiv.org/abs/1806.03019)

##### PDF
[http://arxiv.org/pdf/1806.03019](http://arxiv.org/pdf/1806.03019)

