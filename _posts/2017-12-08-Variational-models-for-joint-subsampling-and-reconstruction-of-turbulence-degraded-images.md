---
layout: post
title: "Variational models for joint subsampling and reconstruction of turbulence-degraded images"
date: 2017-12-08 09:41:24
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Chun Pong Lau, Yu Hin Lai, Lok Ming Lui
mathjax: true
---

* content
{:toc}

##### Abstract
Turbulence-degraded image frames are distorted by both turbulent deformations and space-time-varying blurs. To suppress these effects, we propose a multi-frame reconstruction scheme to recover a latent image from the observed image sequence. Recent approaches are commonly based on registering each frame to a reference image, by which geometric turbulent deformations can be estimated and a sharp image can be restored. A major challenge is that a fine reference image is usually unavailable, as every turbulence-degraded frame is distorted. A high-quality reference image is crucial for the accurate estimation of geometric deformations and fusion of frames. Besides, it is unlikely that all frames from the image sequence are useful, and thus frame selection is necessary and highly beneficial. In this work, we propose a variational model for joint subsampling of frames and extraction of a clear image. A fine image and a suitable choice of subsample are simultaneously obtained by iteratively reducing an energy functional. The energy consists of a fidelity term measuring the discrepancy between the extracted image and the subsampled frames, as well as regularization terms on the extracted image and the subsample. Different choices of fidelity and regularization terms are explored. By carefully selecting suitable frames and extracting the image, the quality of the reconstructed image can be significantly improved. Extensive experiments have been carried out, which demonstrate the efficacy of our proposed model. In addition, the extracted subsamples and images can be put in existing algorithms to produce improved results.

##### Abstract (translated by Google)
湍流退化的图像帧由于湍流变形和时空变化的模糊而变形。为了抑制这些效应，我们提出了一种多帧重建方案来从观察图像序列中恢复潜像。最近的方法通常基于将每个帧记录到参考图像，通过该参考图像可以估计几何湍流变形并且可以恢复清晰的图像。一个主要的挑战是通常无法获得精确的参考图像，因为每个湍流退化帧都是失真的。高质量的参考图像对于精确估计几何变形和帧融合至关重要。此外，来自图像序列的所有帧不太可能是有用的，因此帧选择是必要的并且是非常有益的。在这项工作中，我们提出了一个变分模型的帧联合子采样和提取清晰的图像。通过迭代地减少能量功能同时获得精细图像和子样本的合适选择。能量由一个保真度项组成，测量提取的图像和子采样帧之间的差异，以及提取的图像和子采样的正则化项。对保真度和正则化术语的不同选择进行了探索。通过仔细选择合适的帧并提取图像，可以显着改善重建图像的质量。已经进行了大量的实验，证明了我们提出的模型的有效性。另外，可以将提取的子样本和图像放入现有算法中以产生改善的结果。

##### URL
[http://arxiv.org/abs/1712.03825](http://arxiv.org/abs/1712.03825)

##### PDF
[http://arxiv.org/pdf/1712.03825](http://arxiv.org/pdf/1712.03825)

