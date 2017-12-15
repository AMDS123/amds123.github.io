---
layout: post
title: "Tracing liquid level and material boundaries in transparent vessels using the graph cut computer vision approach"
date: 2016-01-31 00:20:39
categories: arXiv_CV
tags: arXiv_CV Detection Recognition
author: Sagi Eppel
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of boundaries of materials stored in transparent vessels is essential for identifying properties such as liquid level and phase boundaries, which are vital for controlling numerous processes in the industry and chemistry laboratory. This work presents a computer vision method for identifying the boundary of materials in transparent vessels using the graph-cut algorithm. The method receives an image of a transparent vessel containing a material and the contour of the vessel in the image. The boundary of the material in the vessel is found by the graph cut method. In general the method uses the vessel region of the image to create a graph, where pixels are vertices, and the cost of an edge between two pixels is inversely correlated with their intensity difference. The bottom 10% of the vessel region in the image is assumed to correspond to the material phase and defined as the graph and source. The top 10% of the pixels in the vessels are assumed to correspond to the air phase and defined as the graph sink. The minimal cut that splits the resulting graph between the source and sink (hence, material and air) is traced using the max-flow/min-cut approach. This cut corresponds to the boundary of the material in the image. The method gave high accuracy in boundary recognition for a wide range of liquid, solid, granular and powder materials in various glass vessels from everyday life and the chemistry laboratory, such as bottles, jars, Glasses, Chromotography colums and separatory funnels.

##### Abstract (translated by Google)
检测储存在透明容器中的物质的边界对于识别诸如液位和相界的性质是至关重要的，这对于控制工业和化学实验室中的众多过程是至关重要的。这项工作提出了一种计算机视觉方法来识别透明容器中的材料的边界使用图切割算法。该方法接收包含材料的透明容器的图像以及图像中的容器的轮廓。图形切割法找出容器内物料的边界。通常，该方法使用图像的血管区域来创建图形，其中像素是顶点，两个像素之间的边缘的成本与它们的强度差异成反比。假设图像中血管区域的底部10％对应于材料相并定义为图形和来源。假设容器中像素的前10％对应于空气相位并被定义为图像接收器。使用最大流量/最小切割方法追踪源和汇（因此，材料和空气）之间的最终切割。这个切口对应于图像中材料的边界。该方法在日常生活和化学实验室的各种玻璃容器如瓶子，罐子，玻璃，色谱柱和分液漏斗中为各种液体，固体，颗粒和粉末材料提供了高精度的边界识别。

##### URL
[https://arxiv.org/abs/1602.00177](https://arxiv.org/abs/1602.00177)

##### PDF
[https://arxiv.org/pdf/1602.00177](https://arxiv.org/pdf/1602.00177)

