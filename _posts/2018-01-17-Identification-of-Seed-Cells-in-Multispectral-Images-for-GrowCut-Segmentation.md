---
layout: post
title: "Identification of Seed Cells in Multispectral Images for GrowCut Segmentation"
date: 2018-01-17 01:57:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Classification
author: Wuilan Torres, Antonio Rueda-Toicen
mathjax: true
---

* content
{:toc}

##### Abstract
The segmentation of satellite images is a necessary step to perform object-oriented image classification, which has become relevant due to its applicability on images with a high spatial resolution. To perform object-oriented image classification, the studied image must first be segmented in uniform regions. This segmentation requires manual work by an expert user, who must exhaustively explore the image to establish thresholds that generate useful and representative segments without oversegmenting and without discarding representative segments. We propose a technique that automatically segments the multispectral image while facing these issues. We identify in the image homogenous zones according to their spectral signatures through the use of morphological filters. These homogenous zones are representatives of different types of land coverings in the image and are used as seeds for the GrowCut multispectral segmentation algorithm. GrowCut is a cellular automaton with competitive region growth, its cells are linked to every pixel in the image through three parameters: the pixel's spectral signature, a label, and a strength factor that represents the strength with which a cell defends its label. The seed cells possess maximum strength and maintain their state throughout the automaton's evolution. Starting from seed cells, each cell in the image is iteratively attacked by its neighboring cells. When the automaton stops updating its states, we obtain a segmented image where each pixel has taken the label of one of its cells. In this paper the algorithm was applied in an image acquired by Landsat8 on agricultural land of Calabozo, Guarico, Venezuela where there are different types of land coverings: agriculture, urban regions, water bodies, and savannas with different degrees of human intervention. The segmentation obtained is presented as irregular polygons enclosing geographical objects.

##### Abstract (translated by Google)
卫星图像的分割是执行面向对象的图像分类的必要步骤，由于其对于高空间分辨率的图像的适用性已经变得相关。为了执行面向对象的图像分类，所研究的图像必须首先在均匀区域中分割。这种分割需要专家用户的手动工作，他们必须彻底地探索图像，以建立阈值，产生有用和具有代表性的片段，而不需要进行校正，也不需要丢弃具有代表性的片段。我们提出了一种在面对这些问题时自动分割多光谱图像的技术。我们通过使用形态滤波器根据它们的光谱特征在图像中识别同质区域。这些同质区域是图像中不同类型土地覆盖的代表，并被用作GrowCut多光谱分割算法的种子。 GrowCut是一个具有竞争性区域增长的元胞自动机，其单元通过三个参数与图像中的每个像素相关联：像素的光谱特征，标签和表示细胞捍卫其标签的强度的强度因子。种子细胞具有最大的强度并在整个自动机的演化过程中保持其状态。从种子细胞开始，图像中的每个细胞被其相邻细胞迭代攻击。当自动机停止更新其状态时，我们获得一个分割图像，其中每个像素已经取得了其中一个单元的标签。本文将该算法应用于Landsat8在委内瑞拉瓜里科Calabozo农地上的图像，这里有不同类型的土地覆盖：农业，城市地区，水体和人类干扰的不同程度的稀树草原。所获得的分割被呈现为封闭地理对象的不规则多边形。

##### URL
[http://arxiv.org/abs/1801.05525](http://arxiv.org/abs/1801.05525)

##### PDF
[http://arxiv.org/pdf/1801.05525](http://arxiv.org/pdf/1801.05525)

