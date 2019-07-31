---
layout: post
title: "Multi-Angle Point Cloud-VAE: Unsupervised Feature Learning for 3D Point Clouds from Multiple Angles by Joint Self-Reconstruction and Half-to-Half Prediction"
date: 2019-07-30 02:17:12
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning Prediction Relation
author: Zhizhong Han, Xiyang Wang, Yu-Shen Liu, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised feature learning for point clouds has been vital for large-scale point cloud understanding. Recent deep learning based methods depend on learning global geometry from self-reconstruction. However, these methods are still suffering from ineffective learning of local geometry, which significantly limits the discriminability of learned features. To resolve this issue, we propose MAP-VAE to enable the learning of global and local geometry by jointly leveraging global and local self-supervision. To enable effective local self-supervision, we introduce multi-angle analysis for point clouds. In a multi-angle scenario, we first split a point cloud into a front half and a back half from each angle, and then, train MAP-VAE to learn to predict a back half sequence from the corresponding front half sequence. MAP-VAE performs this half-to-half prediction using RNN to simultaneously learn each local geometry and the spatial relationship among them. In addition, MAP-VAE also learns global geometry via self-reconstruction, where we employ a variational constraint to facilitate novel shape generation. The outperforming results in four shape analysis tasks show that MAP-VAE can learn more discriminative global or local features than the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12704](http://arxiv.org/abs/1907.12704)

##### PDF
[http://arxiv.org/pdf/1907.12704](http://arxiv.org/pdf/1907.12704)

