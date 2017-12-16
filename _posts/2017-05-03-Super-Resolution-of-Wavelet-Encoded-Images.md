---
layout: post
title: "Super-Resolution of Wavelet-Encoded Images"
date: 2017-05-03 05:42:14
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Vildan Atalay Aydin, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
Multiview super-resolution image reconstruction (SRIR) is often cast as a resampling problem by merging non-redundant data from multiple low-resolution (LR) images on a finer high-resolution (HR) grid, while inverting the effect of the camera point spread function (PSF). One main problem with multiview methods is that resampling from nonuniform samples (provided by LR images) and the inversion of the PSF are highly nonlinear and ill-posed problems. Non-linearity and ill-posedness are typically overcome by linearization and regularization, often through an iterative optimization process, which essentially trade off the very same information (i.e. high frequency) that we want to recover. We propose a novel point of view for multiview SRIR: Unlike existing multiview methods that reconstruct the entire spectrum of the HR image from the multiple given LR images, we derive explicit expressions that show how the high-frequency spectra of the unknown HR image are related to the spectra of the LR images. Therefore, by taking any of the LR images as the reference to represent the low-frequency spectra of the HR image, one can reconstruct the super-resolution image by focusing only on the reconstruction of the high-frequency spectra. This is very much like single-image methods, which extrapolate the spectrum of one image, except that we rely on information provided by all other views, rather than by prior constraints as in single-image methods (which may not be an accurate source of information). This is made possible by deriving and applying explicit closed-form expressions that define how the local high frequency information that we aim to recover for the reference high resolution image is related to the local low frequency information in the sequence of views. Results and comparisons with recently published state-of-the-art methods show the superiority of the proposed solution.

##### Abstract (translated by Google)
多视点超分辨率图像重建（SRIR）通常通过合并来自更精细的高分辨率（HR）网格上的多个低分辨率（LR）图像的非冗余数据，同时反转相机点的效果扩散函数（PSF）。多视图方法的一个主要问题是非均匀样本（由LR图像提供）的重采样和PSF的反演是高度非线性和不适合的问题。非线性和不适定性通常通过线性化和正则化来克服，通常通过迭代优化过程，其本质上是折衷于我们想要恢复的相同信息（即高频）。我们提出了一种多视角SRIR的新颖观点：与现有的多视图方法，从多个给定的LR图像重建HR图像的整个光谱，我们得到明确的表达，显示未知的HR图像的高频谱如何相关到LR图像的光谱。因此，通过以LR图像中的任何一个作为参考来表示HR图像的低频谱，可以通过仅关注高频谱的重构来重建超分辨率图像。这与单幅图像方法非常相似，除了我们依赖所有其他视图提供的信息，而不是像单幅图像方法中的先验约束外（这可能不是一个精确的来源信息）。这可以通过导出和应用明确的闭式表达式来实现，该表达式定义了我们旨在为参考高分辨率图像恢复的本地高频信息如何与视图序列中的局部低频信息相关。与最近公布的最新方法的结果和比较显示了所提出的解决方案的优越性。

##### URL
[https://arxiv.org/abs/1705.01258](https://arxiv.org/abs/1705.01258)

##### PDF
[https://arxiv.org/pdf/1705.01258](https://arxiv.org/pdf/1705.01258)

