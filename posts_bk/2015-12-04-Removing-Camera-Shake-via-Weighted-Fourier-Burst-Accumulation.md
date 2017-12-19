---
layout: post
title: "Removing Camera Shake via Weighted Fourier Burst Accumulation"
date: 2015-12-04 15:10:36
categories: arXiv_CV
tags: arXiv_CV
author: Mauricio Delbracio, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous recent approaches attempt to remove image blur due to camera shake, either with one or multiple input images, by explicitly solving an inverse and inherently ill-posed deconvolution problem. If the photographer takes a burst of images, a modality available in virtually all modern digital cameras, we show that it is possible to combine them to get a clean sharp version. This is done without explicitly solving any blur estimation and subsequent inverse problem. The proposed algorithm is strikingly simple: it performs a weighted average in the Fourier domain, with weights depending on the Fourier spectrum magnitude. The method can be seen as a generalization of the align and average procedure, with a weighted average, motivated by hand-shake physiology and theoretically supported, taking place in the Fourier domain. The method's rationale is that camera shake has a random nature and therefore each image in the burst is generally blurred differently. Experiments with real camera data, and extensive comparisons, show that the proposed Fourier Burst Accumulation (FBA) algorithm achieves state-of-the-art results an order of magnitude faster, with simplicity for on-board implementation on camera phones. Finally, we also present experiments in real high dynamic range (HDR) scenes, showing how the method can be straightforwardly extended to HDR photography.

##### Abstract (translated by Google)
许多最近的方法试图通过明确地求解逆和固有的不适定的解卷积问题来消除由于相机抖动造成的图像模糊，无论是使用一个还是多个输入图像。如果摄影师拍摄了几乎所有现代数码相机中的图像，我们表明可以将它们组合起来以获得清晰的锐利版本。这是在没有明确解决任何模糊估计和随后的逆问题的情况下完成的所提出的算法非常简单：它在傅立叶域中执行加权平均，权重取决于傅里叶谱的大小。该方法可以看作是对齐和平均过程的推广，具有加权平均，由手抖动生理学和理论支持，发生在傅里叶域。该方法的基本原理是相机抖动具有随机性质，因此，突发中的每个图像通常都会有不同的模糊。实际摄像机数据的实验和广泛的比较表明，所提出的傅立叶突发累积（FBA）算法能够实现最先进的结果，速度提高了一个数量级，同时在拍照手机上实现了简单的板载实现。最后，我们还在真实的高动态范围（HDR）场景中展示了实验，展示了该方法如何直接扩展到HDR摄影。

##### URL
[https://arxiv.org/abs/1505.02731](https://arxiv.org/abs/1505.02731)

##### PDF
[https://arxiv.org/pdf/1505.02731](https://arxiv.org/pdf/1505.02731)

