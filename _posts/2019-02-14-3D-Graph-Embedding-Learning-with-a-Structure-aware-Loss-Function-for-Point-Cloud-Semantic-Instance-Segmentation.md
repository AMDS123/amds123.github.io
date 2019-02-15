---
layout: post
title: "3D Graph Embedding Learning with a Structure-aware Loss Function for Point Cloud Semantic Instance Segmentation"
date: 2019-02-14 07:29:40
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Sparse Segmentation Attention Embedding CNN Prediction
author: Zhidong Liang, Ming Yang, Chunxiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel approach for 3D semantic instance segmentation on point clouds. A 3D convolutional neural network called submanifold sparse convolutional network is used to generate semantic predictions and instance embeddings simultaneously. To obtain discriminative embeddings for each 3D instance, a structure-aware loss function is proposed which considers both the structure information and the embedding information. To get more consistent embeddings for each 3D instance, attention-based k nearest neighbour (KNN) is proposed to assign different weights for different neighbours. Based on the attention-based KNN, we add a graph convolutional network after the sparse convolutional network to get refined embeddings. Our network can be trained end-to-end. A simple mean-shift algorithm is utilized to cluster refined embeddings to get final instance predictions. As a result, our framework can output both the semantic prediction and the instance prediction. Experiments show that our approach outperforms all state-of-art methods on ScanNet benchmark and NYUv2 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05247](http://arxiv.org/abs/1902.05247)

##### PDF
[http://arxiv.org/pdf/1902.05247](http://arxiv.org/pdf/1902.05247)

