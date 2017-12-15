---
layout: post
title: "Robust and Low-Rank Representation for Fast Face Identification with Occlusions"
date: 2017-11-11 20:38:50
categories: arXiv_CV
tags: arXiv_CV Face RNN
author: Michael Iliadis, Haohong Wang, Rafael Molina, Aggelos K. Katsaggelos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an iterative method to address the face identification problem with block occlusions. Our approach utilizes a robust representation based on two characteristics in order to model contiguous errors (e.g., block occlusion) effectively. The first fits to the errors a distribution described by a tailored loss function. The second describes the error image as having a specific structure (resulting in low-rank in comparison to image size). We will show that this joint characterization is effective for describing errors with spatial continuity. Our approach is computationally efficient due to the utilization of the Alternating Direction Method of Multipliers (ADMM). A special case of our fast iterative algorithm leads to the robust representation method which is normally used to handle non-contiguous errors (e.g., pixel corruption). Extensive results on representative face databases (in constrained and unconstrained environments) document the effectiveness of our method over existing robust representation methods with respect to both identification rates and computational time. Code is available at Github, where you can find implementations of the F-LR-IRNNLS and F-IRNNLS (fast version of the RRC) : this https URL

##### Abstract (translated by Google)
在本文中，我们提出了一种迭代方法来解决块闭塞的人脸识别问题。我们的方法利用基于两个特征的鲁棒表示，以便有效地模拟连续的错误（例如块阻塞）。第一个适合错误的定制损失函数描述的分布。第二个将错误图像描述为具有特定结构（导致与图像大小相比较低）。我们将证明这种联合描述对于描述具有空间连续性的误差是有效的。由于使用交替方向乘法器（ADMM），我们的方法在计算上是有效的。我们的快速迭代算法的一个特例导致通常用于处理不连续错误（例如，像素损坏）的鲁棒表示方法。对于代表性人脸数据库（在受限制的和不受限制的环境中）的广泛的结果记录了我们的方法在识别率和计算时间方面相对于现有的鲁棒表示方法的有效性。代码可以在Github上找到，在这里你可以找到F-LR-IRNNLS和F-IRNNLS（RRC的快速版本）的实现：这个https URL

##### URL
[https://arxiv.org/abs/1605.02266](https://arxiv.org/abs/1605.02266)

##### PDF
[https://arxiv.org/pdf/1605.02266](https://arxiv.org/pdf/1605.02266)

