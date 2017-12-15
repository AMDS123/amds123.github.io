---
layout: post
title: "DOC: Deep OCclusion Estimation From a Single Image"
date: 2016-07-24 07:16:54
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Peng Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering the occlusion relationships between objects is a fundamental human visual ability which yields important information about the 3D world. In this paper we propose a deep network architecture, called DOC, which acts on a single image, detects object boundaries and estimates the border ownership (i.e. which side of the boundary is foreground and which is background). We represent occlusion relations by a binary edge map, to indicate the object boundary, and an occlusion orientation variable which is tangential to the boundary and whose direction specifies border ownership by a left-hand rule. We train two related deep convolutional neural networks, called DOC, which exploit local and non-local image cues to estimate this representation and hence recover occlusion relations. In order to train and test DOC we construct a large-scale instance occlusion boundary dataset using PASCAL VOC images, which we call the PASCAL instance occlusion dataset (PIOD). This contains 10,000 images and hence is two orders of magnitude larger than existing occlusion datasets for outdoor images. We test two variants of DOC on PIOD and on the BSDS occlusion dataset and show they outperform state-of-the-art methods. Finally, we perform numerous experiments investigating multiple settings of DOC and transfer between BSDS and PIOD, which provides more insights for further study of occlusion estimation.

##### Abstract (translated by Google)
恢复对象之间的遮挡关系是一个基本的人类视觉能力，它产生关于3D世界的重要信息。在本文中，我们提出了一个名为DOC的深层网络体系结构，它在单个图像上起作用，检测对象边界并估计边界所有权（即边界的哪一边是前景，哪边是背景）。我们用一个二元边缘图来表示遮挡关系，表示物体的边界，以及一个与边界相切，其方向用左手规则指定边界所有权的遮挡方向变量。我们训练两个相关的深度卷积神经网络，称为DOC，利用局部和非局部图像线索来估计这个表示，从而恢复遮挡关系。为了训练和测试DOC，我们使用PASCAL VOC图像（我们称之为PASCAL实例遮挡数据集（PIOD））构建大型实例遮挡边界数据集。这包含10,000个图像，因此比现有的户外图像的遮挡数据集大两个数量级。我们在PIOD和BSDS遮挡数据集上测试了DOC的两种变体，并显示它们超越了最先进的方法。最后，我们进行了大量的实验来研究DOC的多种设置以及BSDS和PIOD之间的转换，这为进一步研究遮挡估计提供了更多的见解。

##### URL
[https://arxiv.org/abs/1511.06457](https://arxiv.org/abs/1511.06457)

##### PDF
[https://arxiv.org/pdf/1511.06457](https://arxiv.org/pdf/1511.06457)

