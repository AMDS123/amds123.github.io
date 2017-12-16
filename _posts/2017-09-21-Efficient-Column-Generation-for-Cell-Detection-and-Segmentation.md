---
layout: post
title: "Efficient Column Generation for Cell Detection and Segmentation"
date: 2017-09-21 14:15:23
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Optimization Inference Detection
author: Chong Zhang, Shaofei Wang, Miguel A. Gonzalez-Ballester, Julian Yarkony
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of instance segmentation in biological images with crowded and compact cells. We formulate this task as an integer program where variables correspond to cells and constraints enforce that cells do not overlap. To solve this integer program, we propose a column generation formulation where the pricing program is solved via exact optimization of very small scale integer programs. Column generation is tightened using odd set inequalities which fit elegantly into pricing problem optimization. Our column generation approach achieves fast stable anytime inference for our instance segmentation problems. We demonstrate on three distinct light microscopy datasets, with several hundred cells each, that our proposed algorithm rapidly achieves or exceeds state of the art accuracy.

##### Abstract (translated by Google)
我们研究了拥挤和紧凑的细胞在生物图像中的实例分割问题。我们将此任务作为一个整数程序来制定，其中变量与单元格和约束条件相对应，强制单元格不重叠。为了解决这个整数程序，我们提出了一个列生成公式，其中定价程序是通过精确优化非常小规模的整数程序来解决的。使用奇数集不等式来收集列生成，这些不等式可以优化地匹配定价问题优化。我们的列生成方法实现了快速稳定的随时推断我们的实例分割问题。我们展示了三个不同的光学显微镜数据集，每个数百个细胞，我们提出的算法迅速达到或超过最先进的精度。

##### URL
[https://arxiv.org/abs/1709.07337](https://arxiv.org/abs/1709.07337)

##### PDF
[https://arxiv.org/pdf/1709.07337](https://arxiv.org/pdf/1709.07337)

