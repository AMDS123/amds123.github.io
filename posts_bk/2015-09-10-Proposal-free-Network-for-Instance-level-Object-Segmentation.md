---
layout: post
title: "Proposal-free Network for Instance-level Object Segmentation"
date: 2015-09-10 01:12:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Xiaodan Liang, Yunchao Wei, Xiaohui Shen, Jianchao Yang, Liang Lin, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Instance-level object segmentation is an important yet under-explored task. The few existing studies are almost all based on region proposal methods to extract candidate segments and then utilize object classification to produce final results. Nonetheless, generating accurate region proposals itself is quite challenging. In this work, we propose a Proposal-Free Network (PFN ) to address the instance-level object segmentation problem, which outputs the instance numbers of different categories and the pixel-level information on 1) the coordinates of the instance bounding box each pixel belongs to, and 2) the confidences of different categories for each pixel, based on pixel-to-pixel deep convolutional neural network. All the outputs together, by using any off-the-shelf clustering method for simple post-processing, can naturally generate the ultimate instance-level object segmentation results. The whole PFN can be easily trained in an end-to-end way without the requirement of a proposal generation stage. Extensive evaluations on the challenging PASCAL VOC 2012 semantic segmentation benchmark demonstrate that the proposed PFN solution well beats the state-of-the-arts for instance-level object segmentation. In particular, the $AP^r$ over 20 classes at 0.5 IoU reaches 58.7% by PFN, significantly higher than 43.8% and 46.3% by the state-of-the-art algorithms, SDS [9] and [16], respectively.

##### Abstract (translated by Google)
实例级别的对象分割是一项重要而尚未深入研究的任务。现有的几项研究几乎都是基于区域提议方法来提取候选区段，然后利用目标分类产生最终结果。尽管如此，生成准确的区域建议本身也颇具挑战性。在这项工作中，我们提出了一个无方案网络（PFN）来解决实例级别的对象分割问题，该问题输出不同类别的实例号和像素级信息：1）每个像素的实例边界框的坐标属于，2）基于像素到像素深度卷积神经网络的每个像素的不同类别的置信度。所有的输出通过使用任何现成的聚类方法进行简单的后处理，可以自然地生成最终的实例级对象分割结果。整个PFN可以很容易地以端到端的方式进行培训，而无需建立生成阶段的要求。对具有挑战性的PASCAL VOC 2012语义分割基准的广泛评估表明，所提出的PFN解决方案很好地胜过了实例级别对象分割的最新技术。尤其是，0.5 IoU的20个类别的$ AP ^ r $达到PFN的58.7％，分别高于最先进的算法SDS [9]和[16]的43.8％和46.3％ 。

##### URL
[https://arxiv.org/abs/1509.02636](https://arxiv.org/abs/1509.02636)

##### PDF
[https://arxiv.org/pdf/1509.02636](https://arxiv.org/pdf/1509.02636)

