---
layout: post
title: "Training object class detectors with click supervision"
date: 2017-05-19 17:19:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Dim P. Papadopoulos, Jasper R. R. Uijlings, Frank Keller, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Training object class detectors typically requires a large set of images with objects annotated by bounding boxes. However, manually drawing bounding boxes is very time consuming. In this paper we greatly reduce annotation time by proposing center-click annotations: we ask annotators to click on the center of an imaginary bounding box which tightly encloses the object instance. We then incorporate these clicks into existing Multiple Instance Learning techniques for weakly supervised object localization, to jointly localize object bounding boxes over all training images. Extensive experiments on PASCAL VOC 2007 and MS COCO show that: (1) our scheme delivers high-quality detectors, performing substantially better than those produced by weakly supervised techniques, with a modest extra annotation effort; (2) these detectors in fact perform in a range close to those trained from manually drawn bounding boxes; (3) as the center-click task is very fast, our scheme reduces total annotation time by 9x to 18x.

##### Abstract (translated by Google)
训练对象类别检测器通常需要大量的图像和由边界框注释的对象。但是，手动绘制边界框非常耗时。在本文中，我们通过提出中心点击注释来大大减少注释时间：我们要求注释者点击紧密包围对象实例的虚构边界框的中心。然后，我们将这些点击合并到现有的多实例学习技术中，用于弱监督对象定位，共同定位所有训练图像上的对象边界框。在PASCAL VOC 2007和MS COCO上进行的大量实验表明：（1）我们的方案提供高质量的探测器，性能比弱监督技术产生的要好得多，只需要额外的注释; （2）这些探测器实际上在接近从手动绘制的边界框训练的那些范围内执行; （3）由于中心点击任务非常快，我们的方案将总注释时间减少了9倍到18倍。

##### URL
[https://arxiv.org/abs/1704.06189](https://arxiv.org/abs/1704.06189)

##### PDF
[https://arxiv.org/pdf/1704.06189](https://arxiv.org/pdf/1704.06189)

