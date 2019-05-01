---
layout: post
title: "3D Point Cloud Denoising using Graph Laplacian Regularization of a Low Dimensional Manifold Model"
date: 2019-04-30 05:39:28
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Face
author: Jin Zeng, Gene Cheung, Michael Ng, Jiahao Pang, Cheng Yang
mathjax: true
---

* content
{:toc}

##### Abstract
3D point cloud - a new signal representation of volumetric objects - is a discrete collection of triples marking exterior object surface locations in 3D space. Conventional imperfect acquisition processes of 3D point cloud - e.g., stereo-matching from multiple viewpoint images or depth data acquired directly from active light sensors - imply non-negligible noise in the data. In this paper, we adopt a previously proposed low-dimensional manifold model for the surface patches in the point cloud and seek self-similar patches to denoise them simultaneously using the patch manifold prior. Due to discrete observations of the patches on the manifold, we approximate the manifold dimension computation defined in the continuous domain with a patch-based graph Laplacian regularizer and propose a new discrete patch distance measure to quantify the similarity between two same-sized surface patches for graph construction that is robust to noise. We show that our graph Laplacian regularizer has a natural graph spectral interpretation, and has desirable numerical stability properties via eigenanalysis. Extensive simulation results show that our proposed denoising scheme can outperform state-of-the-art methods in objective metrics and can better preserve visually salient structural features like edges.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.07252](http://arxiv.org/abs/1803.07252)

##### PDF
[http://arxiv.org/pdf/1803.07252](http://arxiv.org/pdf/1803.07252)

