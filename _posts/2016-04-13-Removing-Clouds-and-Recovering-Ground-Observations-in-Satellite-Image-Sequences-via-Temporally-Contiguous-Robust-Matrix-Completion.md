---
layout: post
title: "Removing Clouds and Recovering Ground Observations in Satellite Image Sequences via Temporally Contiguous Robust Matrix Completion"
date: 2016-04-13 19:13:17
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jialei Wang, Peder A. Olsen, Andrew R. Conn, Aurelie C. Lozano
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of removing and replacing clouds in satellite image sequences, which has a wide range of applications in remote sensing. Our approach first detects and removes the cloud-contaminated part of the image sequences. It then recovers the missing scenes from the clean parts using the proposed "TECROMAC" (TEmporally Contiguous RObust MAtrix Completion) objective. The objective function balances temporal smoothness with a low rank solution while staying close to the original observations. The matrix whose the rows are pixels and columnsare days corresponding to the image, has low-rank because the pixels reflect land-types such as vegetation, roads and lakes and there are relatively few variations as a result. We provide efficient optimization algorithms for TECROMAC, so we can exploit images containing millions of pixels. Empirical results on real satellite image sequences, as well as simulated data, demonstrate that our approach is able to recover underlying images from heavily cloud-contaminated observations.

##### Abstract (translated by Google)
我们考虑在卫星图像序列中去除和替换云的问题，在遥感中有着广泛的应用。我们的方法首先检测并去除图像序列中被云污染的部分。然后使用提议的“TECROMAC”（TEmporally Contiguous RObust MAtrix Completion）目标从清洁零件中恢复丢失的场景。目标函数平衡时间平滑与低级解决方案，同时保持接近原始观察。由于像素反映的是植被，道路，湖泊等陆地类型，其像素和列的行数是与图像对应的天数，因此具有较低的等级，因此变化相对较小。我们为TECROMAC提供了高效的优化算法，所以我们可以利用包含数百万像素的图像。实际卫星图像序列的实验结果以及模拟数据表明，我们的方法能够从重度云受污染的观测中恢复基础图像。

##### URL
[https://arxiv.org/abs/1604.03915](https://arxiv.org/abs/1604.03915)

##### PDF
[https://arxiv.org/pdf/1604.03915](https://arxiv.org/pdf/1604.03915)

