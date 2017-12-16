---
layout: post
title: "Light Source Point Cluster Selection Based Atmosphere Light Estimation"
date: 2017-01-12 05:56:28
categories: arXiv_CV
tags: arXiv_CV
author: Wenbo Zhang, Xiaorong Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Atmosphere light value is a highly critical parameter in defogging algorithms that are based on an atmosphere scattering model. Any error in atmosphere light value will produce a direct impact on the accuracy of scattering computation and thus bring chromatic distortion to restored images. To address this problem, this paper propose a method that relies on clustering statistics to estimate atmosphere light value. It starts by selecting in the original image some potential atmosphere light source points, which are grouped into point clusters by means of clustering technique. From these clusters, a number of clusters containing candidate atmosphere light source points are selected, the points are then analyzed statistically, and the cluster containing the most candidate points is used for estimating atmosphere light value. The mean brightness vector of the candidate atmosphere light points in the chosen point cluster is taken as the estimate of atmosphere light value, while their geometric center in the image is accepted as the location of atmosphere light. Experimental results suggest that this statistics clustering method produces more accurate atmosphere brightness vectors and light source locations. This accuracy translates to, from a subjective perspective, more natural defogging effect on the one hand and to the improvement in various objective image quality indicators on the other hand.

##### Abstract (translated by Google)
大气光照值是基于大气散射模型的除雾算法中非常关键的参数。大气光线的任何误差都会对散射计算的准确性产生直接的影响，从而给恢复的图像带来色差。为了解决这个问题，本文提出了一种依靠聚类统计来估计大气光照值的方法。首先在原始图像中选取一些潜在的大气光源点，通过聚类技术将其分为点群。从这些聚类中，选择包含候选大气光源点的多个聚类，然后对这些点进行统计分析，并将包含最多候选点的聚类用于估计大气光照值。将所选点簇中候选大气光点的平均亮度矢量作为大气光源的估计值，以图像中的几何中心作为大气光的位置。实验结果表明，这种统计聚类方法产生更精确的大气亮度矢量和光源位置。这种精确度一方面转化为主观视角下更为自然的除雾效果，另一方面转化为各种客观图像质量指标的改善。

##### URL
[https://arxiv.org/abs/1701.03244](https://arxiv.org/abs/1701.03244)

##### PDF
[https://arxiv.org/pdf/1701.03244](https://arxiv.org/pdf/1701.03244)

