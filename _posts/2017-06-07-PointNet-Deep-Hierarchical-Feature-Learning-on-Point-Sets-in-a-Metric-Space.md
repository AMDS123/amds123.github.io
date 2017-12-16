---
layout: post
title: "PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space"
date: 2017-06-07 23:37:44
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Charles R. Qi, Li Yi, Hao Su, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
Few prior works study deep learning on point sets. PointNet by Qi et al. is a pioneer in this direction. However, by design PointNet does not capture local structures induced by the metric space points live in, limiting its ability to recognize fine-grained patterns and generalizability to complex scenes. In this work, we introduce a hierarchical neural network that applies PointNet recursively on a nested partitioning of the input point set. By exploiting metric space distances, our network is able to learn local features with increasing contextual scales. With further observation that point sets are usually sampled with varying densities, which results in greatly decreased performance for networks trained on uniform densities, we propose novel set learning layers to adaptively combine features from multiple scales. Experiments show that our network called PointNet++ is able to learn deep point set features efficiently and robustly. In particular, results significantly better than state-of-the-art have been obtained on challenging benchmarks of 3D point clouds.

##### Abstract (translated by Google)
很少有前期的作品在点集上学习深度学习。由Qi等人的PointNet是这个方向的先驱。然而，通过设计，PointNet不捕获由度量空间点引起的局部结构，限制了其识别细粒度图案的能力以及复杂场景的普遍性。在这项工作中，我们引入了一个分层神经网络，它将递归地应用于输入点集合的嵌套分割。通过利用度量空间距离，我们的网络能够通过增加上下文尺度来学习局部特征。随着进一步观察，点集通常采用不同的密度进行采样，导致网络训练均匀密度的性能大大下降，我们提出了新的集合学习层来自适应地结合多个尺度的特征。实验表明，我们称为PointNet ++的网络能够高效而强大地学习深点集特征。尤其是，在三维点云的挑战性基准测试中，获得的结果明显优于现有技术。

##### URL
[https://arxiv.org/abs/1706.02413](https://arxiv.org/abs/1706.02413)

##### PDF
[https://arxiv.org/pdf/1706.02413](https://arxiv.org/pdf/1706.02413)

