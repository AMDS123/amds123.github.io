---
layout: post
title: "Implicit LOD for processing, visualisation and classification in Point Cloud Servers"
date: 2016-03-04 10:54:47
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Rémi Cura, Julien Perret, Nicolas Paparoditis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new paradigm to effortlessly get a portable geometric Level Of Details (LOD) for a point cloud inside a Point Cloud Server. The point cloud is divided into groups of points (patch), then each patch is reordered (MidOc ordering) so that reading points following this order provides more and more details on the patch. This LOD have then multiple applications: point cloud size reduction for visualisation (point cloud streaming) or speeding of slow algorithm, fast density peak detection and correction as well as safeguard for methods that may be sensible to density variations. The LOD method also embeds information about the sensed object geometric nature, and thus can be used as a crude multi-scale dimensionality descriptor, enabling fast classification and on-the-fly filtering for basic classes.

##### Abstract (translated by Google)
我们提出了一个新的范例，轻松获得点云服务器内的点云的可移植几何级别详细信息（LOD）。点云被分成多个点（补丁），然后每个补丁都被重新排序（MidOc排序），以便按照这个顺序的读取点在补丁上提供越来越多的细节。这个LOD有多种应用：可视化（点云流）的点云大小缩减或慢算法的加速，快速密度峰值检测和校正，以及可能对密度变化敏感的方法的保护。 LOD方法还嵌入了感知对象几何性质的信息，因此可以作为一个粗糙的多尺度维度描述符，实现对基本类的快速分类和实时过滤。

##### URL
[https://arxiv.org/abs/1602.06920](https://arxiv.org/abs/1602.06920)

##### PDF
[https://arxiv.org/pdf/1602.06920](https://arxiv.org/pdf/1602.06920)

