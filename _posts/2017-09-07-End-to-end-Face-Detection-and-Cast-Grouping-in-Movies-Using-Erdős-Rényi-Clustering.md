---
layout: post
title: "End-to-end Face Detection and Cast Grouping in Movies Using Erdős-Rényi Clustering"
date: 2017-09-07 21:22:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: SouYoung Jin, Hang Su, Chris Stauffer, Erik Learned-Miller
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end system for detecting and clustering faces by identity in full-length movies. Unlike works that start with a predefined set of detected faces, we consider the end-to-end problem of detection and clustering together. We make three separate contributions. First, we combine a state-of-the-art face detector with a generic tracker to extract high quality face tracklets. We then introduce a novel clustering method, motivated by the classic graph theory results of Erd\H{o}s and R\'enyi. It is based on the observations that large clusters can be fully connected by joining just a small fraction of their point pairs, while just a single connection between two different people can lead to poor clustering results. This suggests clustering using a verification system with very few false positives but perhaps moderate recall. We introduce a novel verification method, rank-1 counts verification, that has this property, and use it in a link-based clustering scheme. Finally, we define a novel end-to-end detection and clustering evaluation metric allowing us to assess the accuracy of the entire end-to-end system. We present state-of-the-art results on multiple video data sets and also on standard face databases.

##### Abstract (translated by Google)
我们提供了一个端到端的系统，用于在全长电影中通过身份检测和聚类人脸。与以预定义的一组检测面开始的作品不同，我们将端到端的检测和聚类问题考虑在一起。我们做三个单独的贡献。首先，我们将最先进的人脸检测器与通用跟踪器结合起来，以提取高质量的人脸跟踪。然后引入了一个新的聚类方法，由Erd \ H {o} s和R \ enyi的经典图论理论结果驱动。它基于观察结果，即通过只加入一小部分点对就可以完全连接大集群，而两个不同人之间的单一连接可能导致较差的集群结果。这意味着使用验证系统进行聚类，只有极少的误报，但可能适度回忆。我们引入了一种新的验证方法，一级统计验证，具有这种属性，并将其用于基于链接的聚类方案。最后，我们定义了一种新型的端到端检测和聚类评估指标，使我们能够评估整个端到端系统的准确性。我们在多个视频数据集以及标准的人脸数据库上提供最新的结果。

##### URL
[https://arxiv.org/abs/1709.02458](https://arxiv.org/abs/1709.02458)

##### PDF
[https://arxiv.org/pdf/1709.02458](https://arxiv.org/pdf/1709.02458)

