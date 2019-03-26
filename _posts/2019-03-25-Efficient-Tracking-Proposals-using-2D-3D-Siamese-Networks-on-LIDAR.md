---
layout: post
title: "Efficient Tracking Proposals using 2D-3D Siamese Networks on LIDAR"
date: 2019-03-25 08:09:13
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Relation
author: Jesus Zarzar, Silvio Giancola, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking vehicles in LIDAR point clouds is a challenging task due to the sparsity of the data and the dense search space. The lack of structure in point clouds impedes the use of convolution and correlation filters usually employed in 2D object tracking. In addition, structuring point clouds is cumbersome and implies losing fine-grained information. As a result, generating proposals in 3D space is expensive and inefficient. In this paper, we leverage the dense and structured Bird Eye View (BEV) representation of LIDAR point clouds to efficiently search for objects of interest. We use an efficient Region Proposal Network and generate a small number of object proposals in 3D. Successively, we refine our selection of 3D object candidates by exploiting the similarity capability of a 3D Siamese network. We regularize the latter 3D Siamese network for shape completion to enhance its discrimination capability. Our method attempts to solve both for an efficient search space in the BEV space and a meaningful selection using 3D LIDAR point cloud. We show that the Region Proposal in the BEV outperforms Bayesian methods such as Kalman and Particle Filters in providing proposal by a significant margin and that such candidates are suitable for the 3D Siamese network. By training our method end-to-end, we outperform the previous baseline in vehicle tracking by 12% / 18% in Success and Precision when using only 16 candidates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10168](http://arxiv.org/abs/1903.10168)

##### PDF
[http://arxiv.org/pdf/1903.10168](http://arxiv.org/pdf/1903.10168)

