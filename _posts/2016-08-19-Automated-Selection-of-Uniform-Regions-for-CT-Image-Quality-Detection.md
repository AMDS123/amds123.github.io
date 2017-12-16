---
layout: post
title: "Automated Selection of Uniform Regions for CT Image Quality Detection"
date: 2016-08-19 19:08:58
categories: arXiv_CV
tags: arXiv_CV Quantitative Detection
author: Maitham D Naeemi, Adam M Alessio, Sohini Roychowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
CT images are widely used in pathology detection and follow-up treatment procedures. Accurate identification of pathological features requires diagnostic quality CT images with minimal noise and artifact variation. In this work, a novel Fourier-transform based metric for image quality (IQ) estimation is presented that correlates to additive CT image noise. In the proposed method, two windowed CT image subset regions are analyzed together to identify the extent of variation in the corresponding Fourier-domain spectrum. The two square windows are chosen such that their center pixels coincide and one window is a subset of the other. The Fourier-domain spectral difference between these two sub-sampled windows is then used to isolate spatial regions-of-interest (ROI) with low signal variation (ROI-LV) and high signal variation (ROI-HV), respectively. Finally, the spatial variance ($var$), standard deviation ($std$), coefficient of variance ($cov$) and the fraction of abdominal ROI pixels in ROI-LV ($\nu'(q)$), are analyzed with respect to CT image noise. For the phantom CT images, $var$ and $std$ correlate to CT image noise ($|r|>0.76$ ($p\ll0.001$)), though not as well as $\nu'(q)$ ($r=0.96$ ($p\ll0.001$)). However, for the combined phantom and patient CT images, $var$ and $std$ do not correlate well with CT image noise ($|r|<0.46$ ($p\ll0.001$)) as compared to $\nu'(q)$ ($r=0.95$ ($p\ll0.001$)). Thus, the proposed method and the metric, $\nu'(q)$, can be useful to quantitatively estimate CT image noise.

##### Abstract (translated by Google)
CT图像被广泛用于病理检测和后续处理程序。精确识别病理特征需要诊断质量的CT图像，而噪声和伪影变化最小。在这项工作中，提出了一种新的基于傅立叶变换的图像质量（IQ）估计量度，与加性CT图像噪声相关。在所提出的方法中，两个窗口CT图像子集区域被一起分析以识别相应的傅里叶域频谱的变化程度。选择两个正方形窗口，使得它们的中心像素重合，并且一个窗口是另一个窗口的子集。这两个子采样窗口之间的傅立叶域光谱差异然后分别用于分离具有低信号变化（ROI-LV）和高信号变化（ROI-HV）的空间感兴趣区域（ROI）。最后，ROI-LV（$ \ nu'（q）$）中的空间方差（$ var $），标准差（$ std $），方差系数（$ cov $）和腹部ROI像素的比例分别为分析了CT图像噪声。对于幻像CT图像，$ var $和$ std $与CT图像噪声相关（$ | r |> 0.76 $（$ p \ ll0.001 $）），尽管不如$ \ nu'（q）$ （$ r = 0.96 $（$ p \ ll0.001 $））。然而，对于组合的幻像和患者CT图像，与$ \ nu相比，$ var $和$ std $与CT图像噪声（$ | r | <0.46 $（$ p \ ll0.001 $））不相关'（q）$（$ r = 0.95 $（$ p \ ll0.001 $））。因此，所提出的方法和量度$ \ nu'（q）$对于定量估计CT图像噪声可能是有用的。

##### URL
[https://arxiv.org/abs/1608.04381](https://arxiv.org/abs/1608.04381)

##### PDF
[https://arxiv.org/pdf/1608.04381](https://arxiv.org/pdf/1608.04381)

