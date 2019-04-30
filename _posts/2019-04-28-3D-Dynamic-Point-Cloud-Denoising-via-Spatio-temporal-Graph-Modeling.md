---
layout: post
title: "3D Dynamic Point Cloud Denoising via Spatio-temporal Graph Modeling"
date: 2019-04-28 09:07:26
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Qianjiang Hu, Zehua Wang, Wei Hu, Xiang Gao, Zongming Guo
mathjax: true
---

* content
{:toc}

##### Abstract
The prevalence of accessible depth sensing and 3D laser scanning techniques has enabled the convenient acquisition of 3D dynamic point clouds, which provide efficient representation of arbitrarily-shaped objects in motion. Nevertheless, dynamic point clouds are often perturbed by noise due to hardware, software or other causes. While many methods have been proposed for the denoising of static point clouds, dynamic point cloud denoising has not been studied in the literature yet. Hence, we address this problem based on the proposed spatio-temporal graph modeling, exploiting both the intra-frame similarity and inter-frame consistency. Specifically, we first represent a point cloud sequence on graphs and model it via spatio-temporal Gaussian Markov Random Fields on defined patches. Then for each target patch, we pose a Maximum a Posteriori estimation, and propose the corresponding likelihood and prior functions via spectral graph theory, leveraging its similar patches within the same frame and corresponding patch in the previous frame. This leads to our problem formulation, which jointly optimizes the underlying dynamic point cloud and spatio-temporal graph. Finally, we propose an efficient algorithm for patch construction, similar/corresponding patch search, intra- and inter-frame graph construction, and the optimization of our problem formulation via alternating minimization. Experimental results show that the proposed method outperforms frame-by-frame denoising from state-of-the-art static point cloud denoising approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12284](http://arxiv.org/abs/1904.12284)

##### PDF
[http://arxiv.org/pdf/1904.12284](http://arxiv.org/pdf/1904.12284)

