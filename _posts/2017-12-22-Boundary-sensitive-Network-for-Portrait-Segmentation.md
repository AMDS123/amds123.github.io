---
layout: post
title: "Boundary-sensitive Network for Portrait Segmentation"
date: 2017-12-22 22:32:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Quantitative
author: Xianzhi Du, Larry Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Compared to the general semantic segmentation problem, portrait segmentation has higher precision requirement on boundary area. However, this problem has not been well studied in previous works. In this paper, we propose a boundary-sensitive deep neural network (BSN) for portrait segmentation. BSN introduces three novel techniques. First, an individual boundary-sensitive kernel is proposed by dilating the contour line and assigning the boundary pixels with multi-class labels. Second, a global boundary-sensitive kernel is employed as a position sensitive prior to further constrain the overall shape of the segmentation map. Third, we train a boundary-sensitive attribute classifier jointly with the segmentation network to reinforce the network with semantic boundary shape information. We have evaluated BSN on the current largest public portrait segmentation dataset,~\ie, the PFCN dataset, as well as the portrait images collected from other three popular image segmentation datasets: COCO, COCO-Stuff, and PASCAL VOC. Our method achieves the superior quantitative and qualitative performance over state-of-the-arts on all the datasets, especially on the boundary area.

##### Abstract (translated by Google)
与一般的语义分割问题相比，纵向分割对边界区域的精度要求较高。但是，这个问题在以前的工作中还没有得到很好的研究。在本文中，我们提出了一种用于纵向分割的边界敏感的深度神经网络（BSN）。 BSN引入了三种新颖的技术。首先，通过扩大轮廓线并为边界像素分配多级标签，提出了一个单独的边界敏感核。其次，在进一步限制分割图的整体形状之前，将全局边界敏感内核用作位置敏感的。第三，与分割网络一起训练一个边界敏感属性分类器，用语义边界形状信息来加强网络。我们已经对当前最大的公共肖像分割数据集（即PFCN数据集）以及从其他三个流行的图像分割数据集（COCO，COCO-Stuff和PASCAL VOC）收集的肖像图像进行了评估。我们的方法在所有数据集上，特别是在边界区域，实现了比现有技术更高的定量和定性表现。

##### URL
[http://arxiv.org/abs/1712.08675](http://arxiv.org/abs/1712.08675)

##### PDF
[http://arxiv.org/pdf/1712.08675](http://arxiv.org/pdf/1712.08675)

