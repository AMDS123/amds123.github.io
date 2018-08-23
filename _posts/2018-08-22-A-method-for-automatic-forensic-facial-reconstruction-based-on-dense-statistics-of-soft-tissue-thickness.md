---
layout: post
title: "A method for automatic forensic facial reconstruction based on dense statistics of soft tissue thickness"
date: 2018-08-22 12:43:51
categories: arXiv_CV
tags: arXiv_CV Face
author: Thomas Gietzen, Robert Brylka, Jascha Achenbach, Katja zum Hebel, Elmar Sch&#xf6;mer, Mario Botsch, Ulrich Schwanecke, Ralf Schulze
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method for automated estimation of a human face given a skull remain. The proposed method is based on three statistical models. A volumetric (tetrahedral) skull model encoding the variations of different skulls, a surface head model encoding the head variations, and a dense statistic of facial soft tissue thickness (FSTT). All data are automatically derived from computed tomography (CT) head scans and optical face scans. In order to obtain a proper dense FSTT statistic, we register a skull model to each skull extracted from a CT scan and determine the FSTT value for each vertex of the skull model towards the associated extracted skin surface. The FSTT values at predefined landmarks from our statistic are well in agreement with data from the literature. 
 To recover a face from a skull remain, we first fit our skull model to the given skull. Next, we generate spheres with radius of the respective FSTT value obtained from our statistic at each vertex of the registered skull. Finally, we fit a head model to the union of all spheres. The proposed automated method enables a probabilistic face-estimation that facilitates forensic recovery even from incomplete skull remains. The FSTT statistic allows the generation of plausible head variants, which can be adjusted intuitively using principal component analysis. We validate our face recovery process using an anonymized head CT scan. The estimation generated from the given skull visually compares well with the skin surface extracted from the CT scan itself.

##### Abstract (translated by Google)
在本文中，我们提出了一种在留下颅骨的情况下自动估计人脸的方法。所提出的方法基于三种统计模型。体积（四面体）颅骨模型编码不同头骨的变化，编码头部变化的表面头部模型，以及面部软组织厚度（FSTT）的密集统计。所有数据都自动从计算机断层扫描（CT）头部扫描和光学面部扫描中获得。为了获得适当密集的FSTT统计量，我们将头骨模型登记到从CT扫描中提取的每个颅骨，并确定颅骨模型的每个顶点朝向相关提取的皮肤表面的FSTT值。来自我们统计数据的预定义地标的FSTT值与文献中的数据非常一致。
 为了从头骨中恢复脸部，我们首先将头骨模型贴合到给定的头骨上。接下来，我们生成具有相应FSTT值的半径的球体，所述FSTT值是从注册颅骨的每个顶点处的统计获得的。最后，我们将头模型拟合到所有领域的联合。所提出的自动化方法使得概率面部估计能够促进法医恢复，即使是不完整的颅骨残留物也是如此。 FSTT统计数据允许生成合理的头部变体，可以使用主成分分析直观地进行调整。我们使用匿名头部CT扫描验证我们的面部恢复过程。从给定的颅骨产生的估计在视觉上与从CT扫描本身提取的皮肤表面很好地比较。

##### URL
[http://arxiv.org/abs/1808.07334](http://arxiv.org/abs/1808.07334)

##### PDF
[http://arxiv.org/pdf/1808.07334](http://arxiv.org/pdf/1808.07334)

