---
layout: post
title: "Progressive Representation Adaptation for Weakly Supervised Object Localization"
date: 2017-10-12 17:58:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Classification Detection
author: Dong Li, Jia-Bin Huang, Yali Li, Shengjin Wang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of weakly supervised object localization where only image-level annotations are available for training object detectors. Numerous methods have been proposed to tackle this problem through mining object proposals. However, a substantial amount of noise in object proposals causes ambiguities for learning discriminative object models. Such approaches are sensitive to model initialization and often converge to undesirable local minimum solutions. In this paper, we propose to overcome these drawbacks by progressive representation adaptation with two main steps: 1) classification adaptation and 2) detection adaptation. In classification adaptation, we transfer a pre-trained network to a multi-label classification task for recognizing the presence of a certain object in an image. Through the classification adaptation step, the network learns discriminative representations that are specific to object categories of interest. In detection adaptation, we mine class-specific object proposals by exploiting two scoring strategies based on the adapted classification network. Class-specific proposal mining helps remove substantial noise from the background clutter and potential confusion from similar objects. We further refine these proposals using multiple instance learning and segmentation cues. Using these refined object bounding boxes, we fine-tune all the layer of the classification network and obtain a fully adapted detection network. We present detailed experimental validation on the PASCAL VOC and ILSVRC datasets. Experimental results demonstrate that our progressive representation adaptation algorithm performs favorably against the state-of-the-art methods.

##### Abstract (translated by Google)
我们解决了弱监督对象定位的问题，只有图像级别的注释可用于训练对象检测器。已经提出了许多方法来通过挖掘对象建议来解决这个问题。然而，对象建议中的大量噪声会导致学习歧视性对象模型的含糊不清。这种方法对模型初始化很敏感，常常会收敛到不希望的局部最小解。在本文中，我们提出通过逐步表征自适应来克服这些缺点，主要有两个步骤：1）分类适应和2）检测适应。在分类适应中，我们将预先训练的网络转移到多标签分类任务，以识别图像中某个对象的存在。通过分类适配步骤，网络学习特定于感兴趣的对象类别的区别表示。在检测适应中，我们利用基于适应的分类网络的两种评分策略挖掘特定于类别的对象提议。特定于类别的提案挖掘有助于消除背景混乱中的大量噪音以及类似对象可能造成的混淆。我们使用多实例学习和分割线索进一步完善这些建议。使用这些细化的对象边界框，我们对分类网络的所有层进行微调，并获得完全适应的检测网络。我们对PASCAL VOC和ILSVRC数据集进行详细的实验验证。实验结果表明，我们的渐进表示适应算法有利于对付最先进的方法。

##### URL
[https://arxiv.org/abs/1710.04647](https://arxiv.org/abs/1710.04647)

##### PDF
[https://arxiv.org/pdf/1710.04647](https://arxiv.org/pdf/1710.04647)

