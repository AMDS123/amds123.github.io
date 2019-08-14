---
layout: post
title: "Interpolated Convolutional Networks for 3D Point Cloud Understanding"
date: 2019-08-13 06:44:04
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Classification Recognition
author: Jiageng Mao, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud is an important type of 3D representation. However, directly applying convolutions on point clouds is challenging due to the sparse, irregular and unordered data structure. In this paper, we propose a novel Interpolated Convolution operation, InterpConv, to tackle the point cloud feature learning and understanding problem. The key idea is to utilize a set of discrete kernel weights and interpolate point features to neighboring kernel-weight coordinates by an interpolation function for convolution. A normalization term is introduced to handle neighborhoods of different sparsity levels. Our InterpConv is shown to be permutation and sparsity invariant, and can directly handle irregular inputs. We further design Interpolated Convolutional Neural Networks (InterpCNNs) based on InterpConv layers to handle point cloud recognition tasks including shape classification, object part segmentation and indoor scene semantic parsing. Experiments show that the networks can capture both fine-grained local structures and global shape context information effectively. The proposed approach achieves state-of-the-art performance on public benchmarks including ModelNet40, ShapeNet Parts and S3DIS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04512](http://arxiv.org/abs/1908.04512)

##### PDF
[http://arxiv.org/pdf/1908.04512](http://arxiv.org/pdf/1908.04512)

