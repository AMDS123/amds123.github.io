---
layout: post
title: "Space-Filling Curve Indices as Acceleration Structure for Exemplar-Based Inpainting"
date: 2017-12-18 10:28:36
categories: arXiv_CV
tags: arXiv_CV
author: Tim Dahmen, Patrick Trampert, Joachim Weickert, Philipp Slusallek
mathjax: true
---

* content
{:toc}

##### Abstract
Exemplar-based inpainting is the process of reconstructing missing parts of an image by searching the remaining data for patches that fit seamlessly. The image is completed to a plausible-looking solution by repeatedly inserting the patch that is the best match according to some cost function. We present an acceleration structure that uses a multi-index scheme to accelerate this search procedure drastically, particularly in the case of very large datasets. The index scheme uses ideas such as dimensionality reduction and k-nearest neighbor search on space-filling curves that are well known in the field of multimedia databases. Our method has a theoretic runtime of O(log2 n) per iteration and reaches a speedup factor of up to 660 over the original method. The approach has the advantage of being agnostic to most modelbased parts of exemplar-based inpainting such as the order in which patches are processed and the cost function used to determine patch similarity. Thus, the acceleration structure can be used in conjunction with most exemplar-based inpainting algorithms.

##### Abstract (translated by Google)
基于范例的修补是通过搜索剩余数据以无缝地匹配补丁来重建图像的缺失部分的过程。通过根据一些成本函数重复插入最佳匹配的补丁，图像被完成为看似合理的解决方案。我们提出了一个使用多索引方案的加速结构来加速这个搜索过程，特别是在非常大的数据集的情况下。索引方案使用多维数据库领域众所周知的空间填充曲线上的降维和k最近邻搜索等思想。我们的方法具有每次迭代O（log2 n）的理论运行时间，并且在原始方法上达到高达660的加速因子。该方法的优点是对基于样本的修补的大多数基于模型的部分是不可知的，例如修补程序的处理顺序和用于确定修补程序相似性的成本函数。因此，加速结构可以与大多数基于示例的修补算法结合使用。

##### URL
[http://arxiv.org/abs/1712.06326](http://arxiv.org/abs/1712.06326)

##### PDF
[http://arxiv.org/pdf/1712.06326](http://arxiv.org/pdf/1712.06326)

