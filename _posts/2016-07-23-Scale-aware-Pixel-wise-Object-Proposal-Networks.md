---
layout: post
title: "Scale-aware Pixel-wise Object Proposal Networks"
date: 2016-07-23 12:10:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Zequn Jie, Xiaodan Liang, Jiashi Feng, Wen Feng Lu, Eng Hock Francis Tay, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Object proposal is essential for current state-of-the-art object detection pipelines. However, the existing proposal methods generally fail in producing results with satisfying localization accuracy. The case is even worse for small objects which however are quite common in practice. In this paper we propose a novel Scale-aware Pixel-wise Object Proposal (SPOP) network to tackle the challenges. The SPOP network can generate proposals with high recall rate and average best overlap (ABO), even for small objects. In particular, in order to improve the localization accuracy, a fully convolutional network is employed which predicts locations of object proposals for each pixel. The produced ensemble of pixel-wise object proposals enhances the chance of hitting the object significantly without incurring heavy extra computational cost. To solve the challenge of localizing objects at small scale, two localization networks which are specialized for localizing objects with different scales are introduced, following the divide-and-conquer philosophy. Location outputs of these two networks are then adaptively combined to generate the final proposals by a large-/small-size weighting network. Extensive evaluations on PASCAL VOC 2007 show the SPOP network is superior over the state-of-the-art models. The high-quality proposals from SPOP network also significantly improve the mean average precision (mAP) of object detection with Fast-RCNN framework. Finally, the SPOP network (trained on PASCAL VOC) shows great generalization performance when testing it on ILSVRC 2013 validation set.

##### Abstract (translated by Google)
对象建议对于当前最先进的对象检测管线是必不可少的。但是，现有的提案方法通常不能以满意的定位精度产生结果。对于那些在实践中相当普遍的小物件，情况更糟。在本文中，我们提出了一个新颖的尺寸感知像素智能对象建议（SPOP）网络来应对挑战。 SPOP网络可以生成具有高召回率和平均最佳重叠（ABO）的提议，即使对于小的对象也是如此。具体而言，为了提高定位精度，采用完全卷积网络，其预测每个像素的对象提议的位置。所生成的像素对象提议的集合增加了显着击中对象的机会，而不会产生额外的计算成本。为了解决小规模物体本地化的挑战，本文引入了两个专门针对不同尺度物体进行定位的定位网络，遵循分而治之的思想。然后将这两个网络的位置输出自适应地组合，以通过大/小尺寸加权网络产生最终提议。对PASCAL VOC 2007的广泛评估表明SPOP网络优于最先进的型号。 SPOP网络提出的高质量建议也使用Fast-RCNN框架显着提高了目标检测的均值精度（mAP）。最后，SPOP网络（在PASCAL VOC上进行培训）在ILSVRC 2013验证集上进行测试时表现出很好的泛化性能。

##### URL
[https://arxiv.org/abs/1601.04798](https://arxiv.org/abs/1601.04798)

##### PDF
[https://arxiv.org/pdf/1601.04798](https://arxiv.org/pdf/1601.04798)

