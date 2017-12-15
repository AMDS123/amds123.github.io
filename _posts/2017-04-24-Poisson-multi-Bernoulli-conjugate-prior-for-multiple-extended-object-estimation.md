---
layout: post
title: "Poisson multi-Bernoulli conjugate prior for multiple extended object estimation"
date: 2017-04-24 08:35:10
categories: arXiv_CV
tags: arXiv_CV Tracking Prediction
author: Karl Granstrom, Maryam Fatemi, Lennart Svensson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a Poisson multi-Bernoulli mixture (PMBM) conjugate prior for multiple extended object filtering. A Poisson point process is used to describe the existence of yet undetected targets, while a multi-Bernoulli mixture describes the distribution of the targets that have been detected. The prediction and update equations are presented for the standard transition density and measurement likelihood. Both the prediction and the update preserve the PMBM form of the density, and in this sense the PMBM density is a conjugate prior. However, the unknown data associations lead to an intractably large number of terms in the PMBM density, and approximations are necessary for tractability. A gamma Gaussian inverse Wishart implementation is presented, along with methods to handle the data association problem. A simulation study shows that the extended target PMBM filter outperforms the extended target $\delta$-GLMB and LMB filters. An experiment with Lidar data illustrates the benefit of tracking both detected and undetected targets.

##### Abstract (translated by Google)
本文提出了一个泊松多伯努利混合物（PMBM）共轭先于多个扩展对象过滤。泊松点过程用于描述尚未检测到的目标的存在，而多伯努利混合描述已经检测到的目标的分布。针对标准转换密度和测量可能性给出了预测和更新方程。预测和更新都保留了密度的PMBM形式，在这个意义上，PMBM密度是一个共轭的先验。然而，未知的数据关联导致PMBM密度中难以处理的大量术语，并且近似值对于易处理性是必要的。介绍了伽玛高斯逆Wishart实现，以及处理数据关联问题的方法。仿真研究表明，扩展目标PMBM滤波器优于扩展目标$ \ delta $ -GLMB和LMB滤波器。激光雷达数据的实验说明跟踪检测到的和未检测到的目标的好处。

##### URL
[https://arxiv.org/abs/1605.06311](https://arxiv.org/abs/1605.06311)

##### PDF
[https://arxiv.org/pdf/1605.06311](https://arxiv.org/pdf/1605.06311)

