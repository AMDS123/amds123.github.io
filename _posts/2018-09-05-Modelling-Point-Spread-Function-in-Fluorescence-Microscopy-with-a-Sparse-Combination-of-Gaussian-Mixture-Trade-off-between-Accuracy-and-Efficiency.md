---
layout: post
title: "Modelling Point Spread Function in Fluorescence Microscopy with a Sparse Combination of Gaussian Mixture: Trade-off between Accuracy and Efficiency"
date: 2018-09-05 15:32:37
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Sparse
author: Denis K. Samuylov, Prateek Purwar, G&#xe1;bor Sz&#xe9;kely, Gr&#xe9;gory Paul
mathjax: true
---

* content
{:toc}

##### Abstract
Deblurring is a fundamental inverse problem in bioimaging. It requires modelling the point spread function (PSF), which captures the optical distortions entailed by the image formation process. The PSF limits the spatial resolution attainable for a given microscope. However, recent applications require a higher resolution, and have prompted the development of super-resolution techniques to achieve sub-pixel accuracy. This requirement restricts the class of suitable PSF models to analog ones. In addition, deblurring is computationally intensive, hence further requiring computationally efficient models. A custom candidate fitting both requirements is the Gaussian model. However, this model cannot capture the rich tail structures found in both theoretical and empirical PSFs. In this paper, we aim at improving the reconstruction accuracy beyond the Gaussian model, while preserving its computational efficiency. We introduce a new class of analog PSF models based on Gaussian mixtures. The number of Gaussian kernels controls both the modelling accuracy and the computational efficiency of the model: the lower the number of kernels, the lower accuracy and the higher efficiency. To explore the accuracy--efficiency trade-off, we propose a variational formulation of the PSF calibration problem, where a convex sparsity-inducing penalty on the number of Gaussian kernels allows trading accuracy for efficiency. We derive an efficient algorithm based on a fully-split formulation of alternating split Bregman. We assess our framework on synthetic and real data and demonstrate a better reconstruction accuracy in both geometry and photometry in point source localisation---a fundamental inverse problem in fluorescence microscopy.

##### Abstract (translated by Google)
去模糊是生物成像中的一个基本逆问题。它需要对点扩散函数（PSF）进行建模，其捕获图像形成过程所引起的光学畸变。 PSF限制了给定显微镜可达到的空间分辨率。然而，最近的应用需要更高的分辨率，并促使开发超分辨率技术以实现亚像素精度。此要求将适合的PSF模型类别限制为模拟模型。此外，去模糊是计算密集型的，因此进一步需要计算上有效的模型。满足这两个要求的自定义候选者是高斯模型。然而，该模型无法捕获理论和经验PSF中发现的丰富尾部结构。在本文中，我们的目标是提高超出高斯模型的重建精度，同时保持其计算效率。我们介绍了一类基于高斯混合的模拟PSF模型。高斯核的数量控制着模型的建模精度和计算效率：核的数量越少，精度越低，效率越高。为了探索准确性 - 效率权衡，我们提出了PSF校准问题的变分公式，其中对高斯核数量的凸性稀疏诱导罚分允许交易准确性以提高效率。我们推导出一种基于交替分裂Bregman的完全分裂公式的有效算法。我们评估了合成和真实数据的框架，并证明了点源定位中几何和光度测量的更好的重建精度 - 荧光显微镜中的一个基本逆问题。

##### URL
[http://arxiv.org/abs/1809.01579](http://arxiv.org/abs/1809.01579)

##### PDF
[http://arxiv.org/pdf/1809.01579](http://arxiv.org/pdf/1809.01579)

