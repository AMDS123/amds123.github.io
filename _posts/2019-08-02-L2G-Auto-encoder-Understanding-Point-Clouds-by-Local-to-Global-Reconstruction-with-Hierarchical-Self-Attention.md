---
layout: post
title: "L2G Auto-encoder: Understanding Point Clouds by Local-to-Global Reconstruction with Hierarchical Self-Attention"
date: 2019-08-02 06:50:59
categories: arXiv_CV
tags: arXiv_CV Attention RNN Classification
author: Xinhai Liu, Zhizhong Han, Xin Wen, Yu-Shen Liu, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
Auto-encoder is an important architecture to understand point clouds in an encoding and decoding procedure of self reconstruction. Current auto-encoder mainly focuses on the learning of global structure by global shape reconstruction, while ignoring the learning of local structures. To resolve this issue, we propose Local-to-Global auto-encoder (L2G-AE) to simultaneously learn the local and global structure of point clouds by local to global reconstruction. Specifically, L2G-AE employs an encoder to encode the geometry information of multiple scales in a local region at the same time. In addition, we introduce a novel hierarchical self-attention mechanism to highlight the important points, scales and regions at different levels in the information aggregation of the encoder. Simultaneously, L2G-AE employs a recurrent neural network (RNN) as decoder to reconstruct a sequence of scales in a local region, based on which the global point cloud is incrementally reconstructed. Our outperforming results in shape classification, retrieval and upsampling show that L2G-AE can understand point clouds better than state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00720](http://arxiv.org/abs/1908.00720)

##### PDF
[http://arxiv.org/pdf/1908.00720](http://arxiv.org/pdf/1908.00720)

