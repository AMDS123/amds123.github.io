---
layout: post
title: "Optimizing Region Selection for Weakly Supervised Object Detection"
date: 2017-08-05 07:24:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection Gradient_Descent
author: Wenhui Jiang, Thuyen Ngo, B. S. Manjunath, Zhicheng Zhao, Fei Su
mathjax: true
---

* content
{:toc}

##### Abstract
Training object detectors with only image-level annotations is very challenging because the target objects are often surrounded by a large number of background clutters. Many existing approaches tackle this problem through object proposal mining. However, the collected positive regions are either low in precision or lack of diversity, and the strategy of collecting negative regions is not carefully designed, neither. Moreover, training is often slow because region selection and object detector training are processed separately. In this context, the primary contribution of this work is to improve weakly supervised detection with an optimized region selection strategy. The proposed method collects purified positive training regions by progressively removing easy background clutters, and selects discriminative negative regions by mining class-specific hard samples. This region selection procedure is further integrated into a CNN-based weakly supervised detection (WSD) framework, and can be performed in each stochastic gradient descent mini-batch during training. Therefore, the entire model can be trained end-to-end efficiently. Extensive evaluation results on PASCAL VOC 2007, VOC 2010 and VOC 2012 datasets are presented which demonstrate that the proposed method effectively improves WSD.

##### Abstract (translated by Google)
训练对象探测器只有图像级别的注释是非常具有挑战性的，因为目标对象往往被大量的背景混乱包围。许多现有的方法通过对象提议挖掘来解决这个问题。然而，收集到的积极区域要么精度低，要么缺乏多样性，收集阴性区域的策略也不是精心设计的。而且，由于区域选择和对象检测器训练是分开处理的，训练通常很慢。在这方面，这项工作的主要贡献是通过优化区域选择策略改进弱监督检测。所提出的方法通过逐步去除容易的背景杂波来收集纯化的正向训练区域，并且通过挖掘特定于类别的硬样本来选择判别性的负区域。该区域选择过程进一步集成到基于CNN的弱监督检测（WSD）框架中，并且可以在训练期间在每个随机梯度下降小批量中执行。因此，整个模型可以被有效地端对端地训练。对PASCAL VOC 2007，VOC 2010和VOC 2012数据集进行了广泛的评估，结果表明所提出的方法能够有效地改善WSD。

##### URL
[https://arxiv.org/abs/1708.01723](https://arxiv.org/abs/1708.01723)

