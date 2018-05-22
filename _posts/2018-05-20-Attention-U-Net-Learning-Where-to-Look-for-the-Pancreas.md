---
layout: post
title: "Attention U-Net: Learning Where to Look for the Pancreas"
date: 2018-05-20 23:33:30
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Attention GAN CNN Prediction
author: Ozan Oktay, Jo Schlemper, Loic Le Folgoc, Matthew Lee, Mattias Heinrich, Kazunari Misawa, Kensaku Mori, Steven McDonagh, Nils Y Hammerla, Bernhard Kainz, Ben Glocker, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel attention gate (AG) model for medical imaging that automatically learns to focus on target structures of varying shapes and sizes. Models trained with AGs implicitly learn to suppress irrelevant regions in an input image while highlighting salient features useful for a specific task. This enables us to eliminate the necessity of using explicit external tissue/organ localisation modules of cascaded convolutional neural networks (CNNs). AGs can be easily integrated into standard CNN architectures such as the U-Net model with minimal computational overhead while increasing the model sensitivity and prediction accuracy. The proposed Attention U-Net architecture is evaluated on two large CT abdominal datasets for multi-class image segmentation. Experimental results show that AGs consistently improve the prediction performance of U-Net across different datasets and training sizes while preserving computational efficiency. The code for the proposed architecture is publicly available.

##### Abstract (translated by Google)
我们提出了一种用于医学成像的新型注意门（AG）模型，可自动学习将注意力集中在各种形状和大小的目标结构上。使用AG进行训练的模型隐式学习抑制输入图像中的不相关区域，同时突出显示对特定任务有用的显着特征。这使我们能够消除使用级联卷积神经网络（CNN）的显式外部组织/器官定位模块的必要性。 AG可以很容易地集成到标准的CNN体​​系结构中，如U-Net模型，同时提高模型灵敏度和预测精度，同时计算开销最小。提出的注意U-Net体系结构在两个大型CT腹部数据集上进行评估，用于多级图像分割。实验结果表明，在保持计算效率的同时，AG在不同数据集和训练大小下一致地提高了U-Net的预测性能。所提出架构的代码是公开可用的。

##### URL
[http://arxiv.org/abs/1804.03999](http://arxiv.org/abs/1804.03999)

##### PDF
[http://arxiv.org/pdf/1804.03999](http://arxiv.org/pdf/1804.03999)

