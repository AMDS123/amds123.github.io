---
layout: post
title: "Deep RBFNet: Point Cloud Feature Learning using Radial Basis Functions"
date: 2018-12-11 09:45:04
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Classification Recognition
author: Weikai Chen, Xiaoguang Han, Guanbin Li, Chao Chen, Jun Xing, Yajie Zhao, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional object recognition has recently achieved great progress thanks to the development of effective point cloud-based learning frameworks, such as PointNet and its extensions. However, existing methods rely heavily on fully connected layers, which introduce a significant amount of parameters, making the network harder to train and prone to overfitting problems. In this paper, we propose a simple yet effective framework for point set feature learning by leveraging a nonlinear activation layer encoded by Radial Basis Function (RBF) kernels. Unlike PointNet variants, that fail to recognize local point patterns, our approach explicitly models the spatial distribution of point clouds by aggregating features from sparsely distributed RBF kernels. A typical RBF kernel, e.g. Gaussian function, naturally penalizes long-distance response and is only activated by neighboring points. Such localized response generates highly discriminative features given different point distributions. In addition, our framework allows the joint optimization of kernel distribution and its receptive field, automatically evolving kernel configurations in an end-to-end manner. We demonstrate that the proposed network with a single RBF layer can outperform the state-of-the-art Pointnet++ in terms of classification accuracy for 3D object recognition tasks. Moreover, the introduction of nonlinear mappings significantly reduces the number of network parameters and computational cost, enabling significantly faster training and a deployable point cloud recognition solution on portable devices with limited resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04302](http://arxiv.org/abs/1812.04302)

##### PDF
[http://arxiv.org/pdf/1812.04302](http://arxiv.org/pdf/1812.04302)

