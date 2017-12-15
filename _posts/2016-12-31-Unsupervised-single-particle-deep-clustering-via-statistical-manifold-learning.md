---
layout: post
title: "Unsupervised single-particle deep clustering via statistical manifold learning"
date: 2016-12-31 07:43:07
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Jiayi Wu, Yong-Bei Ma, Charles Congdon, Bevin Brett, Shuobing Chen, Qi Ouyang, Youdong Mao
mathjax: true
---

* content
{:toc}

##### Abstract
Motivation: Structural heterogeneity in single-particle cryo-electron microscopy (cryo-EM) data represents a major challenge for high-resolution structure determination. Unsupervised classification may serve as the first step in the assessment of structural heterogeneity. Traditional algorithms for unsupervised classification, such as K-means clustering and maximum likelihood optimization, may classify images into wrong classes with decreasing signal-to-noise-ratio (SNR) in the image data, yet demand increased cost in computation. Overcoming these limitations requires further development on clustering algorithms for high-performance cryo-EM data analysis. Results: Here we introduce a statistical manifold learning algorithm for unsupervised single-particle deep clustering. We show that statistical manifold learning improves classification accuracy by about 40% in the absence of input references for lower SNR data. Applications to several experimental datasets suggest that our deep clustering approach can detect subtle structural difference among classes. Through code optimization over the Intel high-performance computing (HPC) processors, our software implementation can generate thousands of reference-free class averages within several hours from hundreds of thousands of single-particle cryo-EM images, which allows significant improvement in ab initio 3D reconstruction resolution and quality. Our approach has been successfully applied in several structural determination projects. We expect that it provides a powerful computational tool in analyzing highly heterogeneous structural data and assisting in computational purification of single-particle datasets for high-resolution reconstruction.

##### Abstract (translated by Google)
动机：单粒子冷冻电子显微镜（cryo-EM）数据中的结构异质性是高分辨率结构测定的主要挑战。无监督分类可以作为评估结构异质性的第一步。用于无监督分类的传统算法（例如K均值聚类和最大似然优化）可以将图像分类为具有降低的图像数据中的信噪比（SNR）的错误类别，但是需要增加计算成本。克服这些局限性需要进一步开发高性能冷冻电磁数据分析的聚类算法。结果：这里我们介绍一种统计流形学习算法的无监督单粒子深度聚类。我们表明，统计流形学习提高了分类精度约40％，在没有输入参考低SNR的数据。对几个实验数据集的应用表明，我们的深度聚类方法可以检测类之间微妙的结构差异。通过对英特尔高性能计算（HPC）处理器的代码优化，我们的软件实现可以在数十万小时内从数十万个单粒子冷冻电镜图像中生成数千个无参考平均分类平均值，从而实现从头开始的显着改进三维重建的分辨率和质量。我们的方法已经成功应用于几个结构测定项目。我们期望它提供了一个强大的计算工具，用于分析高度异构的结构数据，并帮助进行高分辨率重建的单粒子数据集的计算净化。

##### URL
[https://arxiv.org/abs/1604.04539](https://arxiv.org/abs/1604.04539)

##### PDF
[https://arxiv.org/pdf/1604.04539](https://arxiv.org/pdf/1604.04539)

