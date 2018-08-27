---
layout: post
title: "Attention Gated Networks: Learning to Leverage Salient Regions in Medical Images"
date: 2018-08-22 19:17:23
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Attention GAN CNN Image_Classification Classification Prediction Detection
author: Jo Schlemper, Ozan Oktay, Michiel Schaap, Mattias Heinrich, Bernhard Kainz, Ben Glocker, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel attention gate (AG) model for medical image analysis that automatically learns to focus on target structures of varying shapes and sizes. Models trained with AGs implicitly learn to suppress irrelevant regions in an input image while highlighting salient features useful for a specific task. This enables us to eliminate the necessity of using explicit external tissue/organ localisation modules when using convolutional neural networks (CNNs). AGs can be easily integrated into standard CNN models such as VGG or U-Net architectures with minimal computational overhead while increasing the model sensitivity and prediction accuracy. The proposed AG models are evaluated on a variety of tasks, including medical image classification and segmentation. For classification, we demonstrate the use case of AGs in scan plane detection for fetal ultrasound screening. We show that the proposed attention mechanism can provide efficient object localisation while improving the overall prediction performance by reducing false positives. For segmentation, the proposed architecture is evaluated on two large 3D CT abdominal datasets with manual annotations for multiple organs. Experimental results show that AG models consistently improve the prediction performance of the base architectures across different datasets and training sizes while preserving computational efficiency. Moreover, AGs guide the model activations to be focused around salient regions, which provides better insights into how model predictions are made. The source code for the proposed AG models is publicly available.

##### Abstract (translated by Google)
我们提出了一种用于医学图像分析的新型注意门（AG）模型，该模型自动学习聚焦于不同形状和大小的目标结构。用AG训练的模型隐含地学习抑制输入图像中的不相关区域，同时突出显示对特定任务有用的显着特征。这使我们能够在使用卷积神经网络（CNN）时消除使用显式外部组织/器官定位模块的必要性。 AG可以轻松集成到标准CNN模型（如VGG或U-Net架构）中，只需最小的计算开销，同时提高模型灵敏度和预测精度。所提出的AG模型在各种任务上进行评估，包括医学图像分类和分割。为了分类，我们在扫描平面检测中证明了AG用于胎儿超声筛查的用例。我们表明，所提出的注意机制可以提供有效的对象定位，同时通过减少误报来提高整体预测性能。对于分割，所提出的体系结构在两个大的3D CT腹部数据集上进行评估，其具有针对多个器官的手动注释。实验结果表明，AG模型在保持计算效率的同时，不断提高不同数据集和训练大小的基础架构的预测性能。此外，AG指导模型激活集中在显着区域，这提供了更好的洞察模型预测的方式。建议的AG模型的源代码是公开的。

##### URL
[http://arxiv.org/abs/1808.08114](http://arxiv.org/abs/1808.08114)

##### PDF
[http://arxiv.org/pdf/1808.08114](http://arxiv.org/pdf/1808.08114)

