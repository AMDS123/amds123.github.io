---
layout: post
title: "Recurrent Slice Networks for 3D Segmentation of Point Clouds"
date: 2018-03-29 19:22:24
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN
author: Qiangui Huang, Weiyue Wang, Ulrich Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Point clouds are an efficient data format for 3D data. However, existing 3D segmentation methods for point clouds either do not model local dependencies \cite{pointnet} or require added computations \cite{kd-net,pointnet2}. This work presents a novel 3D segmentation framework, RSNet\footnote{Codes are released here https://github.com/qianguih/RSNet}, to efficiently model local structures in point clouds. The key component of the RSNet is a lightweight local dependency module. It is a combination of a novel slice pooling layer, Recurrent Neural Network (RNN) layers, and a slice unpooling layer. The slice pooling layer is designed to project features of unordered points onto an ordered sequence of feature vectors so that traditional end-to-end learning algorithms (RNNs) can be applied. The performance of RSNet is validated by comprehensive experiments on the S3DIS\cite{stanford}, ScanNet\cite{scannet}, and ShapeNet \cite{shapenet} datasets. In its simplest form, RSNets surpass all previous state-of-the-art methods on these benchmarks. And comparisons against previous state-of-the-art methods \cite{pointnet, pointnet2} demonstrate the efficiency of RSNets.

##### Abstract (translated by Google)
点云是3D数据的高效数据格式。但是，现有的用于点云的3D分割方法或者不模拟局部依赖性\ cite {pointnet}或需要添加计算\ cite {kd-net，pointnet2}。这项工作提出了一种新颖的3D分割框架RSNet \ footnote {代码在这里发布https://github.com/qianguih/RSNet}，以有效地模拟点云中的局部结构。 RSNet的关键组件是轻量级本地依赖模块。它是一个新型切片池层，递归神经网络（RNN）层和切片解卷层的组合。切片池层被设计成将无序点的特征投影到特征矢量的有序序列上，以便可以应用传统的端到端学习算法（RNN）。 RSNet的性能通过S3DIS \ cite {stanford}，ScanNet \ cite {scannet}和ShapeNet \ cite {shapenet}数据集的全面实验进行验证。在最简单的形式中，RSNets超越了这些基准测试中所有先前的最先进的方法。与先前最先进的方法比较\ cite {pointnet，pointnet2}证明了RSNets的效率。

##### URL
[http://arxiv.org/abs/1802.04402](http://arxiv.org/abs/1802.04402)

##### PDF
[http://arxiv.org/pdf/1802.04402](http://arxiv.org/pdf/1802.04402)

