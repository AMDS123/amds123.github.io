---
layout: post
title: "Tensor-based approach to accelerate deformable part models"
date: 2017-06-29 11:33:18
categories: arXiv_CV
tags: arXiv_CV
author: D. V. Parkhomenko, I. L. Mazurenko
mathjax: true
---

* content
{:toc}

##### Abstract
This article provides next step towards solving speed bottleneck of any system that intensively uses convolutions operations (e.g. CNN). Method described in the article is applied on deformable part models (DPM) algorithm. Method described here is based on multidimensional tensors and provides efficient tradeoff between DPM performance and accuracy. Experiments on various databases, including Pascal VOC, show that the proposed method allows decreasing a number of convolutions up to 4.5 times compared with DPM v.5, while maintaining similar accuracy. If insignificant accuracy degradation is allowable, higher computational gain can be achieved. The method consists of filters tensor decomposition and convolutions shortening using the decomposed filter. Mathematical overview of the proposed method as well as simulation results are provided.

##### Abstract (translated by Google)
本文为解决集中使用卷积操作（如CNN）的任何系统的速度瓶颈提供了下一步。文章中描述的方法应用于可变形零件模型（DPM）算法。这里描述的方法基于多维张量，并提供DPM性能和准确性之间的有效折衷。在包括Pascal VOC在内的各种数据库上的实验表明，与DPM v.5相比，所提出的方法允许将多个卷积减少4.5倍，同时保持相似的精度。如果允许的精度下降不明显，则可以实现更高的计算增益。该方法由滤波器张量分解和卷积缩短使用分解滤波器。提出了该方法的数学综述以及仿真结果。

##### URL
[https://arxiv.org/abs/1707.03268](https://arxiv.org/abs/1707.03268)

##### PDF
[https://arxiv.org/pdf/1707.03268](https://arxiv.org/pdf/1707.03268)

