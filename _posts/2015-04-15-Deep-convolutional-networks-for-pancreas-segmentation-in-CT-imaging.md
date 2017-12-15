---
layout: post
title: "Deep convolutional networks for pancreas segmentation in CT imaging"
date: 2015-04-15 16:55:46
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Image_Classification Classification Deep_Learning
author: Holger R. Roth, Amal Farag, Le Lu, Evrim B. Turkbey, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic organ segmentation is an important prerequisite for many computer-aided diagnosis systems. The high anatomical variability of organs in the abdomen, such as the pancreas, prevents many segmentation methods from achieving high accuracies when compared to other segmentation of organs like the liver, heart or kidneys. Recently, the availability of large annotated training sets and the accessibility of affordable parallel computing resources via GPUs have made it feasible for "deep learning" methods such as convolutional networks (ConvNets) to succeed in image classification tasks. These methods have the advantage that used classification features are trained directly from the imaging data. We present a fully-automated bottom-up method for pancreas segmentation in computed tomography (CT) images of the abdomen. The method is based on hierarchical coarse-to-fine classification of local image regions (superpixels). Superpixels are extracted from the abdominal region using Simple Linear Iterative Clustering (SLIC). An initial probability response map is generated, using patch-level confidences and a two-level cascade of random forest classifiers, from which superpixel regions with probabilities larger 0.5 are retained. These retained superpixels serve as a highly sensitive initial input of the pancreas and its surroundings to a ConvNet that samples a bounding box around each superpixel at different scales (and random non-rigid deformations at training time) in order to assign a more distinct probability of each superpixel region being pancreas or not. We evaluate our method on CT images of 82 patients (60 for training, 2 for validation, and 20 for testing). Using ConvNets we achieve average Dice scores of 68%+-10% (range, 43-80%) in testing. This shows promise for accurate pancreas segmentation, using a deep learning approach and compares favorably to state-of-the-art methods.

##### Abstract (translated by Google)
自动器官分割是许多计算机辅助诊断系统的重要先决条件。与肝脏，心脏或肾脏等器官的其他分割相比，腹部器官（如胰腺）的高解剖变异性阻止许多分割方法达到高精度。最近，大规模注释训练集的可用性以及通过GPU实现的价格合理的并行计算资源已经使得诸如卷积网络（ConvNet）的“深度学习”方法能够成功地进行图像分类任务。这些方法的优点是使用的分类特征直接从成像数据中训练。我们提出了一个全自动的自下而上的胰腺分割计算机断层扫描（CT）图像的腹部。该方法基于局部图像区域（超像素）的分层粗略分类。使用简单线性迭代聚类（SLIC）从腹部区域提取超像素。使用斑块级置信度和随机森林分类器的两级级联来生成初始概率响应图，其中保留了概率大于0.5的超像素区域。这些保留的超级像素作为胰腺及其周围的高度敏感的初始输入到ConvNet，其在不同尺度上围绕每个超像素周围的边界框（以及在训练时间处的随机非刚性变形）以便分配更明显的概率每个超像素区域是否是胰腺。我们对82例患者的CT图像进行了评估（60例为训练，2例为验证，20例为测试）。使用ConvNets，我们在测试中获得68％±10％（范围，43-80％）的平均Dice分数。这显示了对精确的胰腺分割的承诺，使用深度学习方法，并与最先进的方法相比。

##### URL
[https://arxiv.org/abs/1504.03967](https://arxiv.org/abs/1504.03967)

##### PDF
[https://arxiv.org/pdf/1504.03967](https://arxiv.org/pdf/1504.03967)

