---
layout: post
title: "Deep Unsupervised Learning of 3D Point Clouds via Graph Topology Inference and Filtering"
date: 2019-05-11 18:25:58
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Face Inference Classification Relation
author: Siheng Chen, Chaojing Duan, Yaoqing Yang, Duanshun Li, Chen Feng, Dong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep autoencoder with graph topology inference and filtering to achieve compact representations of unorganized 3D point clouds in an unsupervised manner. The encoder of the proposed networks adopts similar architectures as in PointNet, which is a well-acknowledged method for supervised learning of 3D point clouds. The decoder of the proposed networks involves three novel modules: the folding module, the graph-topology-inference module, and the graph-filtering module. The folding module folds a canonical 2D lattice to the underlying surface of a 3D point cloud, achieving coarse reconstruction; the graph-topology-inference module learns a graph topology to represent pairwise relationships between 3D points; and the graph-filtering module designs graph filters based on the learnt graph topology to obtain the refined reconstruction. We further provide theoretical analyses of the proposed architecture. We provide an upper bound for the reconstruction loss and further show the superiority of graph smoothness over spatial smoothness as a prior to model 3D point clouds. In the experiments, we validate the proposed networks in three tasks, including reconstruction, visualization, and classification. The experimental results show that (1) the proposed networks outperform the state-of-the-art methods in various tasks, including reconstruction and transfer classification; (2) a graph topology can be inferred as auxiliary information without specific supervision on graph topology inference; and (3) graph filtering refines the reconstruction, leading to better performances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04571](http://arxiv.org/abs/1905.04571)

##### PDF
[http://arxiv.org/pdf/1905.04571](http://arxiv.org/pdf/1905.04571)

