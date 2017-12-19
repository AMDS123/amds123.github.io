---
layout: post
title: "Sketch-based Image Retrieval from Millions of Images under Rotation, Translation and Scale Variations"
date: 2015-10-31 08:50:43
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Quantitative Detection
author: Sarthak Parui, Anurag Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
Proliferation of touch-based devices has made sketch-based image retrieval practical. While many methods exist for sketch-based object detection/image retrieval on small datasets, relatively less work has been done on large (web)-scale image retrieval. In this paper, we present an efficient approach for image retrieval from millions of images based on user-drawn sketches. Unlike existing methods for this problem which are sensitive to even translation or scale variations, our method handles rotation, translation, scale (i.e. a similarity transformation) and small deformations. The object boundaries are represented as chains of connected segments and the database images are pre-processed to obtain such chains that have a high chance of containing the object. This is accomplished using two approaches in this work: a) extracting long chains in contour segment networks and b) extracting boundaries of segmented object proposals. These chains are then represented by similarity-invariant variable length descriptors. Descriptor similarities are computed by a fast Dynamic Programming-based partial matching algorithm. This matching mechanism is used to generate a hierarchical k-medoids based indexing structure for the extracted chains of all database images in an offline process which is used to efficiently retrieve a small set of possible matched images for query chains. Finally, a geometric verification step is employed to test geometric consistency of multiple chain matches to improve results. Qualitative and quantitative results clearly demonstrate superiority of the approach over existing methods.

##### Abstract (translated by Google)
基于触摸的设备的扩展使基于草图的图像检索成为可能。虽然在小数据集上存在许多基于草图的对象检测/图像检索的方法，但是在大规模（网络）规模的图像检索上已经做了相对较少的工作。在本文中，我们提出了一个基于用户绘制的草图从数百万图像检索图像的有效方法。与现有的对于即使是平移或尺度变化都很敏感的问题的方法不同，我们的方法处理旋转，平移，尺度（即相似变换）和小变形。对象边界被表示为连接段的链，并且数据库图像被预处理以获得具有包含该对象的高可能性的链。这是通过两种方法完成的：a）在轮廓线网络中提取长链，b）提取分割对象提议的边界。这些链然后由相似不变可变长度描述符表示。通过基于快速动态规划的部分匹配算法计​​算描述符相似度。该匹配机制被用于在离线过程中为所有数据库图像的提取链生成分层的基于k-medoids的索引结构，该索引结构用于有效地检索查询链的一小组可能的匹配图像。最后，采用几何验证步骤来测试多个链条匹配的几何一致性以改善结果。定性和定量的结果清楚地表明了方法优于现有的方法。

##### URL
[https://arxiv.org/abs/1511.00099](https://arxiv.org/abs/1511.00099)

##### PDF
[https://arxiv.org/pdf/1511.00099](https://arxiv.org/pdf/1511.00099)

