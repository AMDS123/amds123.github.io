---
layout: post
title: "OCT segmentation: Integrating open parametric contour model of the retinal layers and shape constraint to the Mumford-Shah functional"
date: 2018-08-08 19:29:21
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jinming Duan, Weicheng Xie, Ryan Wen Liu, Christopher Tench, Irene Gottlob, Frank Proudlock, Li Bai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel retinal layer boundary model for segmentation of optical coherence tomography (OCT) images. The retinal layer boundary model consists of 9 open parametric contours representing the 9 retinal layers in OCT images. An intensity-based Mumford-Shah (MS) variational functional is first defined to evolve the retinal layer boundary model to segment the 9 layers simultaneously. By making use of the normals of open parametric contours, we construct equal sized adjacent narrowbands that are divided by each contour. Regional information in each narrowband can thus be integrated into the MS energy functional such that its optimisation is robust against different initialisations. A statistical prior is also imposed on the shape of the segmented parametric contours for the functional. As such, by minimising the MS energy functional the parametric contours can be driven towards the true boundaries of retinal layers, while the similarity of the contours with respect to training OCT shapes is preserved. Experimental results on real OCT images demonstrate that the method is accurate and robust to low quality OCT images with low contrast and high-level speckle noise, and it outperforms the recent geodesic distance based method for segmenting 9 layers of the retina in OCT images.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的视网膜层边界模型，用于光学相干断层扫描（OCT）图像的分割。视网膜层边界模型由9个开放参数轮廓组成，代表OCT图像中的9个视网膜层。首先定义基于强度的Mumford-Shah（MS）变分函数以进化视网膜层边界模型以同时分割9层。通过利用开放参数轮廓的法线，我们构造了由每个轮廓划分的相等大小的相邻窄带。因此，每个窄带中的区域信息可以被集成到MS能量函数中，使得其优化对于不同的初始化是鲁棒的。对于功能性的分段参数轮廓的形状也施加统计先验。这样，通过最小化MS能量功能，可以将参数轮廓朝向视网膜层的真实边界驱动，同时保持轮廓相对于训练OCT形状的相似性。实际OCT图像的实验结果表明，该方法对低对比度和高水平斑点噪声的低质量OCT图像具有准确性和鲁棒性，并且优于最近的基于测地距离的OCT图像中9层视网膜分割方法。

##### URL
[http://arxiv.org/abs/1808.02917](http://arxiv.org/abs/1808.02917)

##### PDF
[http://arxiv.org/pdf/1808.02917](http://arxiv.org/pdf/1808.02917)

