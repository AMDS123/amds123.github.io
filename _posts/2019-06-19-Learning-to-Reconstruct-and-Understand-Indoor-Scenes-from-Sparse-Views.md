---
layout: post
title: "Learning to Reconstruct and Understand Indoor Scenes from Sparse Views"
date: 2019-06-19 03:10:06
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation
author: Jingyu Yang, Ji Xu, Kun Li, Yu-Kun Lai, Huanjing Yue, Jianzhi Lu, Hao Wu, Yebin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new method for simultaneous 3D reconstruction and semantic segmentation of indoor scenes. Unlike existing methods that require recording a video using a color camera and/or a depth camera, our method only needs a small number of (e.g., 3-5) color images from uncalibrated sparse views as input, which greatly simplifies data acquisition and extends applicable scenarios. Since different views have limited overlaps, our method allows a single image as input to discern the depth and semantic information of the scene. The key issue is how to recover relatively accurate depth from single images and reconstruct a 3D scene by fusing very few depth maps. To address this problem, we first design an iterative deep architecture, IterNet, that estimates depth and semantic segmentation alternately, so that they benefit each other. To deal with the little overlap and non-rigid transformation between views, we further propose a joint global and local registration method to reconstruct a 3D scene with semantic information from sparse views. We also make available a new indoor synthetic dataset simultaneously providing photorealistic high-resolution RGB images, accurate depth maps and pixel-level semantic labels for thousands of complex layouts, useful for training and evaluation. Experimental results on public datasets and our dataset demonstrate that our method achieves more accurate depth estimation, smaller semantic segmentation errors and better 3D reconstruction results, compared with state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07892](http://arxiv.org/abs/1906.07892)

##### PDF
[http://arxiv.org/pdf/1906.07892](http://arxiv.org/pdf/1906.07892)

