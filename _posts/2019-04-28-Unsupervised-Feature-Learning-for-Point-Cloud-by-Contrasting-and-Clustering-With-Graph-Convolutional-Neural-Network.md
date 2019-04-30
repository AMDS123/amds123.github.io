---
layout: post
title: "Unsupervised Feature Learning for Point Cloud by Contrasting and Clustering With Graph Convolutional Neural Network"
date: 2019-04-28 18:21:13
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Ling Zhang, Zhigang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
To alleviate the cost of collecting and annotating large-scale point cloud datasets, we propose an unsupervised learning approach to learn features from unlabeled point cloud "3D object" dataset by using part contrasting and object clustering with deep graph neural networks (GNNs). In the contrast learning step, all the samples in the 3D object dataset are cut into two parts and put into a "part" dataset. Then a contrast learning GNN (ContrastNet) is trained to verify whether two randomly sampled parts from the part dataset belong to the same object. In the cluster learning step, the trained ContrastNet is applied to all the samples in the original 3D object dataset to extract features, which are used to group the samples into clusters. Then another GNN for clustering learning (ClusterNet) is trained to predict the cluster ID of all the training samples. The contrasting learning forces the ContrastNet to learn high-level semantic features of objects but probably ignores low-level features, while the ClusterNet improves the quality of learned features by being trained to discover objects that probably belong to the same semantic categories by the use of cluster IDs. We have conducted extensive experiments to evaluate the proposed framework on point cloud classification tasks. The proposed unsupervised learning approach obtained comparable performance to the state-of-the-art unsupervised learning methods that used much more complicated network structures. The code of this work is publicly available via: https://github.com/lingzhang1/ContrastNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12359](http://arxiv.org/abs/1904.12359)

##### PDF
[http://arxiv.org/pdf/1904.12359](http://arxiv.org/pdf/1904.12359)

