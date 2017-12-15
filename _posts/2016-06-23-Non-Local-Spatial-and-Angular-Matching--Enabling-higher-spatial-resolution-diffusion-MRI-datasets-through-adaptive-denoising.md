---
layout: post
title: "Non Local Spatial and Angular Matching : Enabling higher spatial resolution diffusion MRI datasets through adaptive denoising"
date: 2016-06-23 09:28:29
categories: arXiv_CV
tags: arXiv_CV Sparse Quantitative
author: Samuel St-Jean, Pierrick Coupé, Maxime Descoteaux
mathjax: true
---

* content
{:toc}

##### Abstract
Diffusion magnetic resonance imaging datasets suffer from low Signal-to-Noise Ratio, especially at high b-values. Acquiring data at high b-values contains relevant information and is now of great interest for microstructural and connectomics studies. High noise levels bias the measurements due to the non-Gaussian nature of the noise, which in turn can lead to a false and biased estimation of the diffusion parameters. Additionally, the usage of in-plane acceleration techniques during the acquisition leads to a spatially varying noise distribution, which depends on the parallel acceleration method implemented on the scanner. This paper proposes a novel diffusion MRI denoising technique that can be used on all existing data, without adding to the scanning time. We first apply a statistical framework to convert the noise to Gaussian distributed noise, effectively removing the bias. We then introduce a spatially and angular adaptive denoising technique, the Non Local Spatial and Angular Matching (NLSAM) algorithm. Each volume is first decomposed in small 4D overlapping patches to capture the structure of the diffusion data and a dictionary of atoms is learned on those patches. A local sparse decomposition is then found by bounding the reconstruction error with the local noise variance. We compare against three other state-of-the-art denoising methods and show quantitative local and connectivity results on a synthetic phantom and on an in-vivo high resolution dataset. Overall, our method restores perceptual information, removes the noise bias in common diffusion metrics, restores the extracted peaks coherence and improves reproducibility of tractography. Our work paves the way for higher spatial resolution acquisition of diffusion MRI datasets, which could in turn reveal new anatomical details that are not discernible at the spatial resolution currently used by the diffusion MRI community.

##### Abstract (translated by Google)
扩散磁共振成像数据集具有较低的信噪比，特别是在较高的b值下。以高b值获取数据包含相关信息，现在对微观结构和连接组学研究非常感兴趣。由于噪声的非高斯特性，高噪声水平对测量结果产生偏差，这反过来会导致对扩散参数的错误和有偏差的估计。另外，在采集期间使用平面内加速技术会导致空间上变化的噪声分布，这取决于在扫描仪上实现的并行加速度方法。本文提出了一种新的扩散MRI去噪技术，可以在不增加扫描时间的情况下，在所有现有数据上使用。我们首先应用统计框架将噪声转换成高斯分布噪声，有效消除偏差。然后我们引入空间和角度自适应去噪技术，非局部空间和角度匹配（NLSAM）算法。每个体积首先在小的4D重叠小块中被分解以捕获扩散数据的结构，并且在这些小块上学习原子字典。然后通过将重建误差与局部噪声方差进行边界来找到局部稀疏分解。我们与其他三种最先进的去噪方法进行比较，并在合成体模和体内高分辨率数据集上显示定量局部和连通性结果。总的来说，我们的方法恢复知觉信息，消除了共同扩散指标中的噪声偏差，恢复了提取的峰值一致性，提高了纤维束成像的可重复性。我们的工作为扩散MRI数据集的更高空间分辨率采集铺平了道路，这可能反过来揭示在扩散MRI社区目前使用的空间分辨率上不能辨别的新解剖细节。

##### URL
[https://arxiv.org/abs/1606.07239](https://arxiv.org/abs/1606.07239)

##### PDF
[https://arxiv.org/pdf/1606.07239](https://arxiv.org/pdf/1606.07239)

