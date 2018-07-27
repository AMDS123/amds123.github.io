---
layout: post
title: "Linkage between Piecewise Constant Mumford-Shah model and ROF model and its virtue in image segmentation"
date: 2018-07-26 15:28:12
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Xiaohao Cai, Raymond Chan, Carola-Bibiane Schonlieb, Gabriele Steidl, Tieyong Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
The piecewise constant Mumford-Shah (PCMS) model and the Rudin-Osher-Fatemi (ROF) model are two of the most famous variational models in image segmentation and image restoration, respectively. They have ubiquitous applications in image processing. In this paper, we explore the linkage between these two important models. We prove that for two-phase segmentation problem the optimal solution of the PCMS model can be obtained by thresholding the minimizer of the ROF model. This linkage is still valid for multiphase segmentation under mild assumptions. Thus it opens a new segmentation paradigm: image segmentation can be done via image restoration plus thresholding. This new paradigm, which circumvents the innate non-convex property of the PCMS model, therefore improves the segmentation performance in both efficiency (much faster than state-of-the-art methods based on PCMS model, particularly when the phase number is high) and effectiveness (producing segmentation results with better quality) due to the flexibility of the ROF model in tackling degraded images, such as noisy images, blurry images or images with information loss. As a by-product of the new paradigm, we derive a novel segmentation method, coined thresholded-ROF (T-ROF) method, to illustrate the virtue of manipulating image segmentation through image restoration techniques. The convergence of the T-ROF method under certain conditions is proved, and elaborate experimental results and comparisons are presented.

##### Abstract (translated by Google)
分段常数Mumford-Shah（PCMS）模型和Rudin-Osher-Fatemi（ROF）模型分别是图像分割和图像恢复中最着名的两个变分模型。它们在图像处理中具有无处不在的应用。在本文中，我们探讨了这两个重要模型之间的联系。我们证明了对于两阶段分割问题，可以通过对ROF模型的最小化器进行阈值处理来获得PCMS模型的最优解。在温和假设下，这种联系对于多相分割仍然有效。因此，它打开了一种新的分割范例：图像分割可以通过图像恢复和阈值处理来完成。这种绕过PCMS模型先天非凸特性的新范例因此提高了效率的分割性能（比基于PCMS模型的最先进方法快得多，特别是当相数高时）由于ROF模型在处理劣化图像（例如噪声图像，模糊图像或信息丢失图像）方面的灵活性，因此有效性（产生更好质量的分割结果）。作为新范式的副产品，我们推导出一种新颖的分割方法，即创造的阈值-ROF（T-ROF）方法，以说明通过图像恢复技术操纵图像分割的优点。证明了T-ROF方法在一定条件下的收敛性，并给出了精细的实验结果和比较。

##### URL
[http://arxiv.org/abs/1807.10194](http://arxiv.org/abs/1807.10194)

##### PDF
[http://arxiv.org/pdf/1807.10194](http://arxiv.org/pdf/1807.10194)

