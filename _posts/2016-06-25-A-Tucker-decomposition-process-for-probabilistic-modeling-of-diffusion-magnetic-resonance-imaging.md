---
layout: post
title: "A Tucker decomposition process for probabilistic modeling of diffusion magnetic resonance imaging"
date: 2016-06-25 21:28:08
categories: arXiv_CV
tags: arXiv_CV GAN
author: Hernan Dario Vargas Cardona, Mauricio A. Alvarez, Alvaro A. Orozco
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion magnetic resonance imaging (dMRI) is an emerging medical technique used for describing water diffusion in an organic tissue. Typically, rank-2 tensors quantify this diffusion. From this quantification, it is possible to calculate relevant scalar measures (i.e. fractional anisotropy and mean diffusivity) employed in clinical diagnosis of neurological diseases. Nonetheless, 2nd-order tensors fail to represent complex tissue structures like crossing fibers. To overcome this limitation, several researchers proposed a diffusion representation with higher order tensors (HOT), specifically 4th and 6th orders. However, the current acquisition protocols of dMRI data allow images with a spatial resolution between 1 $mm^3$ and 2 $mm^3$. This voxel size is much smaller than tissue structures. Therefore, several clinical procedures derived from dMRI may be inaccurate. Interpolation has been used to enhance resolution of dMRI in a tensorial space. Most interpolation methods are valid only for rank-2 tensors and a generalization for HOT data is missing. In this work, we propose a novel stochastic process called Tucker decomposition process (TDP) for performing HOT data interpolation. Our model is based on the Tucker decomposition and Gaussian processes as parameters of the TDP. We test the TDP in 2nd, 4th and 6th rank HOT fields. For rank-2 tensors, we compare against direct interpolation, log-Euclidean approach and Generalized Wishart processes. For rank-4 and rank-6 tensors we compare against direct interpolation. Results obtained show that TDP interpolates accurately the HOT fields and generalizes to any rank.

##### Abstract (translated by Google)
扩散磁共振成像（dMRI）是用于描述有机组织中水分扩散的新兴医学技术。通常，二阶张量量化了这种扩散。根据这种量化，可以计算在神经疾病的临床诊断中使用的相关标量量度（即分数各向异性和平均扩散率）。尽管如此，二阶张量不能代表复杂的组织结构，如交叉纤维。为了克服这个限制，一些研究人员提出了一个高阶张量（HOT）的扩散表示，具体来说是4阶和6阶。然而，当前的dMRI数据采集协议允许图像的空间分辨率在1立方公尺到2美元之间。这个体素的大小比组织结构小得多。因此，从dMRI得到的几个临床程序可能是不准确的。已经使用插值来增强张量空间中的dMRI的分辨率。大多数插值方法仅对2阶张量有效，而且缺少HOT数据的推广。在这项工作中，我们提出了一个新的随机过程称为Tucker分解过程（TDP）进行HOT数据插值。我们的模型是基于塔克分解和高斯过程作为TDP的参数。我们测试TDP在第2,4,6热点领域。对于秩2张量，我们比较直接插值，对数欧几里德方法和广义Wishart过程。对于等级4和等级6张量，我们比较直接插值。得到的结果表明，TDP可以准确地内插HOT域，并推广到任何等级。

##### URL
[https://arxiv.org/abs/1606.07970](https://arxiv.org/abs/1606.07970)

##### PDF
[https://arxiv.org/pdf/1606.07970](https://arxiv.org/pdf/1606.07970)

