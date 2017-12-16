---
layout: post
title: "On the Empirical Effect of Gaussian Noise in Under-sampled MRI Reconstruction"
date: 2016-10-03 05:28:06
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction
author: Patrick Virtue, Michael Lustig
mathjax: true
---

* content
{:toc}

##### Abstract
In Fourier-based medical imaging, sampling below the Nyquist rate results in an underdetermined system, in which linear reconstructions will exhibit artifacts. Another consequence of under-sampling is lower signal to noise ratio (SNR) due to fewer acquired measurements. Even if an oracle provided the information to perfectly disambiguate the underdetermined system, the reconstructed image could still have lower image quality than a corresponding fully sampled acquisition because of the reduced measurement time. The effects of lower SNR and the underdetermined system are coupled during reconstruction, making it difficult to isolate the impact of lower SNR on image quality. To this end, we present an image quality prediction process that reconstructs fully sampled, fully determined data with noise added to simulate the loss of SNR induced by a given under-sampling pattern. The resulting prediction image empirically shows the effect of noise in under-sampled image reconstruction without any effect from an underdetermined system. We discuss how our image quality prediction process can simulate the distribution of noise for a given under-sampling pattern, including variable density sampling that produces colored noise in the measurement data. An interesting consequence of our prediction model is that we can show that recovery from underdetermined non-uniform sampling is equivalent to a weighted least squares optimization that accounts for heterogeneous noise levels across measurements. Through a series of experiments with synthetic and in vivo datasets, we demonstrate the efficacy of the image quality prediction process and show that it provides a better estimation of reconstruction image quality than the corresponding fully-sampled reference image.

##### Abstract (translated by Google)
在基于傅里叶的医学成像中，低于奈奎斯特速率的采样导致欠定系统，其中线性重建将显示伪影。欠采样的另一个结果是由于较少的采集测量而导致较低的信噪比（SNR）。即使甲骨文提供了信息以完全消除欠定系统，由于减少了测量时间，所以重构图像仍可能具有比相应的完全采样采集更低的图像质量。较低的信噪比和欠定系统的影响在重建过程中耦合，难以隔离较低的信噪比对图像质量的影响。为此，我们提出了一个图像质量预测过程，重建完全采样，充分确定的数据与噪声添加到模拟由给定的欠采样模式引起的信噪比损失。得到的预测图像经验性地显示欠采样图像重建中的噪声效应，而不受任何欠定系统的影响。我们讨论如何我们的图像质量预测过程可以模拟给定欠采样模式的噪声分布，包括在测量数据中产生有色噪声的可变密度采样。我们的预测模型的一个有趣的结果是，我们可以表明，从欠定非均匀采样恢复相当于一个加权最小二乘优化，考虑到跨测量异构噪声水平。通过一系列合成和体内数据集的实验，我们证明了图像质量预测过程的有效性，并显示出它比相应的完全采样参考图像提供了更好的重建图像质量估计。

##### URL
[https://arxiv.org/abs/1610.00410](https://arxiv.org/abs/1610.00410)

##### PDF
[https://arxiv.org/pdf/1610.00410](https://arxiv.org/pdf/1610.00410)

