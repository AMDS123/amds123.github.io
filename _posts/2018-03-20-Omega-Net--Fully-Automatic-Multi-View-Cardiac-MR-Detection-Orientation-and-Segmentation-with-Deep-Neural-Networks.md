---
layout: post
title: "{Omega}-Net : Fully Automatic, Multi-View Cardiac MR Detection, Orientation, and Segmentation with Deep Neural Networks"
date: 2018-03-20 10:32:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Semantic_Segmentation Detection
author: Davis M. Vigneault, Weidi Xie, Carolyn Y. Ho, David A. Bluemke, J. Alison Noble
mathjax: true
---

* content
{:toc}

##### Abstract
Pixelwise segmentation of the left ventricular (LV) myocardium and the four cardiac chambers in 2-D steady state free precession (SSFP) cine sequences is an essential preprocessing step for a wide range of analyses. Variability in contrast, appearance, orientation, and placement of the heart between patients, clinical views, scanners, and protocols makes fully automatic semantic segmentation a notoriously difficult problem. Here, we present ${\Omega}$-Net (Omega-Net): a novel convolutional neural network (CNN) architecture for simultaneous localization, transformation into a canonical orientation, and semantic segmentation. First, an initial segmentation is performed on the input image, second, the features learned during this initial segmentation are used to predict the parameters needed to transform the input image into a canonical orientation, and third, a final segmentation is performed on the transformed image. In this work, ${\Omega}$-Nets of varying depths were trained to detect five foreground classes in any of three clinical views (short axis, SA, four-chamber, 4C, two-chamber, 2C), without prior knowledge of the view being segmented. The architecture was trained on a cohort of patients with hypertrophic cardiomyopathy and healthy control subjects. Network performance as measured by weighted foreground intersection-over-union (IoU) was substantially improved in the best-performing ${\Omega}$- Net compared with U-Net segmentation without localization or orientation. In addition, {\Omega}-Net was retrained from scratch on the 2017 MICCAI ACDC dataset, and achieves state-of-the-art results on the LV and RV bloodpools, and performed slightly worse in segmentation of the LV myocardium. We conclude this architecture represents a substantive advancement over prior approaches, with implications for biomedical image segmentation more generally.

##### Abstract (translated by Google)
在二维稳态自由进动（SSFP）电影序列中对左心室（LV）心肌和四个心脏腔室的像素分割是用于广泛分析的基本预处理步骤。在患者，临床视图，扫描仪和协议之间的心脏对比度，外观，取向和放置方面的可变性使得全自动语义分割成为一个众所周知的难题。在这里，我们提出了$ {\ Omega} $  -  Net（Omega-Net）：一种用于同时定位，转化为规范定向和语义分割的新型卷积神经网络（CNN）体系结构。首先，对输入图像执行初始分割，其次，将在该初始分割期间学习的特征用于预测将输入图像变换为规范定向所需的参数，以及第三，对变换后的图像执行最终分割。在这项工作中，不同深度的网络在三种临床视图（短轴，SA，四室，4C，双室，2C）中进行训练以检测五个前景类别，而没有先验知识的视图被分割。该架构在肥胖型心肌病患者和健康对照受试者队列中进行了培训。与没有本地化或定向的U-Net分割相比，通过加权前景交叉口联合（IoU）测量的网络性能在最佳性能的$ {\ Omega} $  -  Net中得到显着改善。此外，{\ Omega} -Net在2017年MICCAI ACDC数据集中从零开始重新训练，并在LV和RV血池中实现了最先进的结果，并且在LV心肌的分割方面表现稍差。我们得出结论，这种架构代表了先前方法的实质性进步，对生物医学图像分割更具普遍意义。

##### URL
[http://arxiv.org/abs/1711.01094](http://arxiv.org/abs/1711.01094)

##### PDF
[http://arxiv.org/pdf/1711.01094](http://arxiv.org/pdf/1711.01094)

