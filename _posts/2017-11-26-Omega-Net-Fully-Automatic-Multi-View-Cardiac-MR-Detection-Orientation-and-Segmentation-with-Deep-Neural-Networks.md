---
layout: post
title: "Omega-Net: Fully Automatic, Multi-View Cardiac MR Detection, Orientation, and Segmentation with Deep Neural Networks"
date: 2017-11-26 17:45:06
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Semantic_Segmentation Detection
author: Davis M. Vigneault, Weidi Xie, Carolyn Y. Ho, David A. Bluemke, J. Alison Noble
mathjax: true
---

* content
{:toc}

##### Abstract
Pixelwise segmentation of the left ventricular (LV) myocardium and the four cardiac chambers in 2-D steady state free precession (SSFP) cine sequences is an essential preprocessing step for a wide range of analyses. Variability in contrast, appearance, orientation, and placement of the heart between patients, clinical views, scanners, and protocols makes fully automatic semantic segmentation a notoriously difficult problem. Here, we present ${\Omega}$-Net (Omega-Net): a novel convolutional neural network (CNN) architecture for simultaneous detection, transformation into a canonical orientation, and semantic segmentation. First, a coarse-grained segmentation is performed on the input image, second, the features learned during this coarse-grained segmentation are used to predict the parameters needed to transform the input image into a canonical orientation, and third, a fine-grained segmentation is performed on the transformed image. In this work, ${\Omega}$-Nets of varying depths were trained to detect five foreground classes in any of three clinical views (short axis, SA, four-chamber, 4C, two-chamber, 2C), without prior knowledge of the view being segmented. This constitutes a substantially more challenging problem compared with prior work. The architecture was trained on a cohort of patients with hypertrophic cardiomyopathy (HCM, N = 42) and healthy control subjects (N = 21). Network performance as measured by weighted foreground intersection-over-union (IoU) was substantially improved in the best-performing ${\Omega}$- Net compared with U-Net segmentation without detection or orientation (0.858 vs 0.834). We believe this architecture represents a substantive advancement over prior approaches, with implications for biomedical image segmentation more generally.

##### Abstract (translated by Google)
在二维稳态自由进动（SSFP）电影序列中对左心室（LV）心肌和四个心脏腔室的像素分割是广泛分析的基本预处理步骤。在患者，临床观察者，扫描仪和协议之间的心脏的对比度，外观，取向和放置的可变性使全自动语义分割成为一个众所周知的难题。在这里，我们提出了一个新的卷积神经网络（CNN）体系结构，用于同时检测，转换成规范的方向和语义分割。首先，对输入图像进行粗粒度分割，其次，在粗粒度分割过程中学习的特征用于预测将输入图像转换为规范方向所需的参数;第三，细粒度分割在变换的图像上执行。在这项工作中，不同深度的网络被训练成在三个临床视图（短轴，SA，四室，4C，两室，2C）的任何一个中检测五个前景类别，而没有先验知识的视图被分割。与以前的工作相比，这构成了一个更具挑战性的问题。该架构在肥厚型心肌病（HCM，N = 42）和健康对照组（N = 21）的队列中进行训练。与没有检测或定位的U-Net分割（0.858对0.834）相比，通过加权前景交叉相交（IoU）测量的网络性能在最佳性能的$ {\ Omega} $  -  Net中被显着改善。我们相信这种架构代表了先前方法的实质性进步，更普遍地涉及生物医学图像分割。

##### URL
[https://arxiv.org/abs/1711.01094](https://arxiv.org/abs/1711.01094)

##### PDF
[https://arxiv.org/pdf/1711.01094](https://arxiv.org/pdf/1711.01094)

