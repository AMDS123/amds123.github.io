---
layout: post
title: "VIGAN: Missing View Imputation with Generative Adversarial Networks"
date: 2017-11-01 15:43:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN
author: Chao Shang, Aaron Palmer, Jiangwen Sun, Ko-Shin Chen, Jin Lu, Jinbo Bi
mathjax: true
---

* content
{:toc}

##### Abstract
In an era when big data are becoming the norm, there is less concern with the quantity but more with the quality and completeness of the data. In many disciplines, data are collected from heterogeneous sources, resulting in multi-view or multi-modal datasets. The missing data problem has been challenging to address in multi-view data analysis. Especially, when certain samples miss an entire view of data, it creates the missing view problem. Classic multiple imputations or matrix completion methods are hardly effective here when no information can be based on in the specific view to impute data for such samples. The commonly-used simple method of removing samples with a missing view can dramatically reduce sample size, thus diminishing the statistical power of a subsequent analysis. In this paper, we propose a novel approach for view imputation via generative adversarial networks (GANs), which we name by VIGAN. This approach first treats each view as a separate domain and identifies domain-to-domain mappings via a GAN using randomly-sampled data from each view, and then employs a multi-modal denoising autoencoder (DAE) to reconstruct the missing view from the GAN outputs based on paired data across the views. Then, by optimizing the GAN and DAE jointly, our model enables the knowledge integration for domain mappings and view correspondences to effectively recover the missing view. Empirical results on benchmark datasets validate the VIGAN approach by comparing against the state of the art. The evaluation of VIGAN in a genetic study of substance use disorders further proves the effectiveness and usability of this approach in life science.

##### Abstract (translated by Google)
在大数据成为常态的时代，数据质量和完整性越来越少，数量越来越少。在许多学科中，数据是从不同来源收集的，从而产生多视图或多模式数据集。缺少的数据问题在多视图数据分析中一直面临着挑战。尤其是，当某些样本错过了整个数据视图时，会造成缺失的视图问题。经典的多重插值或矩阵完成方法在这里几乎没有效果，因为在特定的视图中没有信息可以基于这些样本的数据进行估算。去除缺失视图样本的常用简单方法可以大大减少样本大小，从而降低后续分析的统计功效。在本文中，我们提出了一种新颖的方法，通过生成敌对网络（GAN），我们命名为VIGAN视图插补。这种方法首先将每个视图视为一个独立的域，并使用来自每个视图的随机采样数据通过GAN标识域到域的映射，然后使用多模式降噪自动编码器（DAE）重建GAN中的缺失视图基于视图中的配对数据进行输出。然后，通过联合优化GAN和DAE，我们的模型实现了域映射和查看对应的知识集成，有效地恢复了缺失的视图。基准数据集上的实证结果通过与现有技术的比较验证了VIGAN方法。 VIGAN在物质使用障碍的遗传研究中的评估进一步证明了这种方法在生命科学中的有效性和可用性。

##### URL
[https://arxiv.org/abs/1708.06724](https://arxiv.org/abs/1708.06724)

##### PDF
[https://arxiv.org/pdf/1708.06724](https://arxiv.org/pdf/1708.06724)

