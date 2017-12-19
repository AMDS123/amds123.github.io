---
layout: post
title: "Multi-Contrast MRI Reconstruction with Structure-Guided Total Variation"
date: 2015-11-20 15:08:17
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Matthias J. Ehrhardt, Marta M. Betcke
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic resonance imaging (MRI) is a versatile imaging technique that allows different contrasts depending on the acquisition parameters. Many clinical imaging studies acquire MRI data for more than one of these contrasts---such as for instance T1 and T2 weighted images---which makes the overall scanning procedure very time consuming. As all of these images show the same underlying anatomy one can try to omit unnecessary measurements by taking the similarity into account during reconstruction. We will discuss two modifications of total variation---based on i) location and ii) direction---that take structural a priori knowledge into account and reduce to total variation in the degenerate case when no structural knowledge is available. We solve the resulting convex minimization problem with the alternating direction method of multipliers that separates the forward operator from the prior. For both priors the corresponding proximal operator can be implemented as an extension of the fast gradient projection method on the dual problem for total variation. We tested the priors on six data sets that are based on phantoms and real MRI images. In all test cases exploiting the structural information from the other contrast yields better results than separate reconstruction with total variation in terms of standard metrics like peak signal-to-noise ratio and structural similarity index. Furthermore, we found that exploiting the two dimensional directional information results in images with well defined edges, superior to those reconstructed solely using a priori information about the edge location.

##### Abstract (translated by Google)
磁共振成像（MRI）是一种多功能成像技术，根据采集参数可以实现不同的对比度。许多临床成像研究采集的MRI数据不止一种对比度 - 例如T1和T2加权像 - 这使整个扫描过程非常耗时。由于所有这些图像都显示相同的底层解剖结构，因此可以通过在重建期间考虑相似性来尝试省略不必要的测量。我们将讨论基于i）位置和ii）方向的总体变化的两种修改，即当没有结构化知识时，将结构先验知识考虑在内，并将其归结为退化情况下的全变量。我们利用乘法器的交替方向方法来解决所得到的凸最小化问题，其将前向运算符与前一个运算符分开。对于这两个先验，相应的近端算子可以作为快速梯度投影方法在总变差对偶问题上的扩展。我们测试了基于幻影和真实MRI图像的六个数据集的先验。在所有的测试用例中，利用来自另一个对比的结构信息产生比单独重构更好的结果，其中总体变化的标准度量如峰值信噪比和结构相似性指数。此外，我们发现利用二维方向信息导致具有良好定义的边缘的图像，优于仅利用关于边缘位置的先验信息重建的图像。

##### URL
[https://arxiv.org/abs/1511.06631](https://arxiv.org/abs/1511.06631)

##### PDF
[https://arxiv.org/pdf/1511.06631](https://arxiv.org/pdf/1511.06631)

