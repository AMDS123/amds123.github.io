---
layout: post
title: "Detect What You Can: Detecting and Representing Objects using Holistic Models and Body Parts"
date: 2014-06-08 21:44:18
categories: arXiv_CV
tags: arXiv_CV
author: Xianjie Chen, Roozbeh Mottaghi, Xiaobai Liu, Sanja Fidler, Raquel Urtasun, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting objects becomes difficult when we need to deal with large shape deformation, occlusion and low resolution. We propose a novel approach to i) handle large deformations and partial occlusions in animals (as examples of highly deformable objects), ii) describe them in terms of body parts, and iii) detect them when their body parts are hard to detect (e.g., animals depicted at low resolution). We represent the holistic object and body parts separately and use a fully connected model to arrange templates for the holistic object and body parts. Our model automatically decouples the holistic object or body parts from the model when they are hard to detect. This enables us to represent a large number of holistic object and body part combinations to better deal with different "detectability" patterns caused by deformations, occlusion and/or low resolution. We apply our method to the six animal categories in the PASCAL VOC dataset and show that our method significantly improves state-of-the-art (by 4.1% AP) and provides a richer representation for objects. During training we use annotations for body parts (e.g., head, torso, etc), making use of a new dataset of fully annotated object parts for PASCAL VOC 2010, which provides a mask for each part.

##### Abstract (translated by Google)
当我们需要处理大的形变，遮挡和低分辨率时，检测物体变得困难。我们提出了一种新的方法来处理动物的大变形和部分遮挡（作为高度可变形的物体的例子），ii）用身体部位来描述它们，iii）当它们的身体部位很难被检测到时， ，以低分辨率描绘的动物）。我们分别表示整体对象和身体部位，并使用完全连接的模型为整体对象和身体部位排列模板。当模型很难被检测到时，我们的模型会自动将整体物体或身体部分从模型中分离出来。这使我们能够代表大量的整体对象和身体部位组合，以更好地处理由变形，遮挡和/或低分辨率引起的不同“可检测性”模式。我们将我们的方法应用于PASCAL VOC数据集中的六个动物类别，并显示我们的方法显着提高了最新的（达到4.1％的AP）并为对象提供了更丰富的表示。在训练期间，我们使用针对身体部位（例如头部，躯干等）的注释，利用用于PASCAL VOC 2010的全注释对象部分的新数据集，其为每个部分提供掩模。

##### URL
[https://arxiv.org/abs/1406.2031](https://arxiv.org/abs/1406.2031)

##### PDF
[https://arxiv.org/pdf/1406.2031](https://arxiv.org/pdf/1406.2031)

