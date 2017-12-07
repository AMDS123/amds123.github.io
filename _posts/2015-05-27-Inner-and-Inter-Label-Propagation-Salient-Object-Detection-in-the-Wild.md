---
layout: post
title: "Inner and Inter Label Propagation: Salient Object Detection in the Wild"
date: 2015-05-27 05:24:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hongyang Li, Huchuan Lu, Zhe Lin, Xiaohui Shen, Brian Price
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel label propagation based method for saliency detection. A key observation is that saliency in an image can be estimated by propagating the labels extracted from the most certain background and object regions. For most natural images, some boundary superpixels serve as the background labels and the saliency of other superpixels are determined by ranking their similarities to the boundary labels based on an inner propagation scheme. For images of complex scenes, we further deploy a 3-cue-center-biased objectness measure to pick out and propagate foreground labels. A co-transduction algorithm is devised to fuse both boundary and objectness labels based on an inter propagation scheme. The compactness criterion decides whether the incorporation of objectness labels is necessary, thus greatly enhancing computational efficiency. Results on five benchmark datasets with pixel-wise accurate annotations show that the proposed method achieves superior performance compared with the newest state-of-the-arts in terms of different evaluation metrics.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于标签传播的显着性检测方法。一个关键的观察是，可以通过传播从最确定的背景和对象区域提取的标签来估计图像中的显着性。对于大多数自然图像，一些边界超像素用作背景标签，其他超像素的显着性是通过基于内部传播方案将它们与边界标签的相似性排序来确定的。对于复杂场景的图像，我们进一步部署一个3线索中心偏向的对象度量来挑选和传播前景标签。设计了一种共同转导算法，以基于互传播方案来融合边界和目标标签。紧凑性标准决定了是否需要引入对象标签，从而大大提高了计算效率。对五个具有像素精确注释的基准数据集的结果显示，所提出的方法在不同的评估度量方面与最新的现有技术相比实现了优越的性能。

##### URL
[https://arxiv.org/abs/1505.07192](https://arxiv.org/abs/1505.07192)

##### PDF
[https://arxiv.org/pdf/1505.07192](https://arxiv.org/pdf/1505.07192)

