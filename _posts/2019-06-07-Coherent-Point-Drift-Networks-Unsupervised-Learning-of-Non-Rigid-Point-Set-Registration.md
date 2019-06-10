---
layout: post
title: "Coherent Point Drift Networks: Unsupervised Learning of Non-Rigid Point Set Registration"
date: 2019-06-07 12:12:22
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Lingjing Wang, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Given new pairs of source and target point sets, standard point set registration methods often repeatedly conduct the independent iterative search of desired geometric transformation to align the source point set with the target one. This limits their use in applications to handle the real-time point set registration with large volume dataset. This paper presents a novel method, named coherent point drift networks (CPD-Net), for unsupervised learning of geometric transformation towards real-time non-rigid point set registration. In contrast to previous efforts (e.g. coherent point drift), CPD-Net can learn displacement field function to estimate geometric transformation from a training dataset, consequently, to predict the desired geometric transformation for the alignment of previously unseen pairs without any additional iterative optimization process. Furthermore, CPD-Net leverages the power of deep neural network to fit an arbitrary function, that adaptively accommodates different levels of complexity of the desired geometric transformation. Particularly, CPD-Net is proved with a theoretical guarantee to learn a continuous displacement vector function that could further avoid imposing additional parametric smoothness constraint as in previous works. Our experiments verify CPD-Net's impressive performance for non-rigid point set registration on various 2D/3D datasets, even in presence of significant displacement noise, outliers, and missing points. Our code is availabel at https://github.com/Lingjing324/CPD-Net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03039](http://arxiv.org/abs/1906.03039)

##### PDF
[http://arxiv.org/pdf/1906.03039](http://arxiv.org/pdf/1906.03039)

