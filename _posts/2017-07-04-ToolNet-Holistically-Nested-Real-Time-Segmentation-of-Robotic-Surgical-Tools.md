---
layout: post
title: "ToolNet: Holistically-Nested Real-Time Segmentation of Robotic Surgical Tools"
date: 2017-07-04 19:53:12
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Optimization Deep_Learning Prediction
author: Luis C. Garcia-Peraza-Herrera, Wenqi Li, Lucas Fidon, Caspar Gruijthuijsen, Alain Devreker, George Attilakos, Jan Deprest, Emmanuel Vander Poorten, Danail Stoyanov, Tom Vercauteren, Sebastien Ourselin
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time tool segmentation from endoscopic videos is an essential part of many computer-assisted robotic surgical systems and of critical importance in robotic surgical data science. We propose two novel deep learning architectures for automatic segmentation of non-rigid surgical instruments. Both methods take advantage of automated deep-learning-based multi-scale feature extraction while trying to maintain an accurate segmentation quality at all resolutions. The two proposed methods encode the multi-scale constraint inside the network architecture. The first proposed architecture enforces it by cascaded aggregation of predictions and the second proposed network does it by means of a holistically-nested architecture where the loss at each scale is taken into account for the optimization process. As the proposed methods are for real-time semantic labeling, both present a reduced number of parameters. We propose the use of parametric rectified linear units for semantic labeling in these small architectures to increase the regularization ability of the design and maintain the segmentation accuracy without overfitting the training sets. We compare the proposed architectures against state-of-the-art fully convolutional networks. We validate our methods using existing benchmark datasets, including ex vivo cases with phantom tissue and different robotic surgical instruments present in the scene. Our results show a statistically significant improved Dice Similarity Coefficient over previous instrument segmentation methods. We analyze our design choices and discuss the key drivers for improving accuracy.

##### Abstract (translated by Google)
内窥镜视频的实时工具分割是许多计算机辅助机器人手术系统的重要组成部分，在机器人手术数据科学中至关重要。我们提出了两种新颖的深度学习体系结构，用于非刚性手术器械的自动分割。这两种方法都利用了基于自动深度学习的多尺度特征提取，同时试图在所有分辨率下保持精确的分割质量。两种提出的方​​法对网络体系结构内的多尺度约束进行编码。第一个提出的体系结构通过级联的预测实现它，第二个建议的网络通过全局嵌套体系结构来实现，其中在优化过程中考虑每个尺度的损失。由于所提出的方法是用于实时语义标记，所以提出的参数数量减少。我们提出在这些小体系结构中使用参数整形线性单元进行语义标注，以提高设计的正则化能力，并保持分割的准确性，而不会过度拟合训练集。我们将所提出的架构与最先进的完全卷积网络进行比较。我们使用现有的基准数据集来验证我们的方法，包括具有幻像组织的离体病例和现场存在的不同机器人手术器械。我们的结果显示，与以前的仪器分割方法相比，骰子相似系数有显着的改善。我们分析我们的设计选择并讨论提高准确性的关键驱动因素。

##### URL
[https://arxiv.org/abs/1706.08126](https://arxiv.org/abs/1706.08126)

##### PDF
[https://arxiv.org/pdf/1706.08126](https://arxiv.org/pdf/1706.08126)

