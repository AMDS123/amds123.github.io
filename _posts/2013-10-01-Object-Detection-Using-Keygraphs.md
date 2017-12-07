---
layout: post
title: "Object Detection Using Keygraphs"
date: 2013-10-01 07:45:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Marcelo Hashimoto, Roberto Marcondes Cesar Junior
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new framework for object detection based on a generalization of the keypoint correspondence framework. This framework is based on replacing keypoints by keygraphs, i.e. isomorph directed graphs whose vertices are keypoints, in order to explore relative and structural information. Unlike similar works in the literature, we deal directly with graphs in the entire pipeline: we search for graph correspondences instead of searching for individual point correspondences and then building graph correspondences from them afterwards. We also estimate the pose from graph correspondences instead of falling back to point correspondences through a voting table. The contributions of this paper are the proposed framework and an implementation that properly handles its inherent issues of loss of locality and combinatorial explosion, showing its viability for real-time applications. In particular, we introduce the novel concept of keytuples to solve a running time issue. The accuracy of the implementation is shown by results of over 800 experiments with a well-known database of images. The speed is illustrated by real-time tracking with two different cameras in ordinary hardware.

##### Abstract (translated by Google)
基于关键点对应框架的推广，提出了一种新的对象检测框架。这个框架是基于用关键图代替关键点，即顶点是关键点的同构有向图，以便探索相关和结构信息。与文献中的类似工作不同，我们直接处理整个管道中的图形：我们搜索图形对应关系，而不是搜索各个点的对应关系，然后再建立图形对应关系。我们也通过图表对应关系来估计姿势，而不是通过投票表格回落到点对应关系。本文的贡献是提出的框架和一个实现，正确处理其固有的局部性和组合爆炸的固有问题，显示其实时应用程序的可行性。我们特别介绍了keytuples的新概念来解决运行时间问题。通过800多个实验的结果显示了实施的准确性，其中使用了众所周知的图像数据库。通过在普通硬件中使用两个不同摄像机的实时跟踪来说明速度。

##### URL
[https://arxiv.org/abs/1310.0171](https://arxiv.org/abs/1310.0171)

##### PDF
[https://arxiv.org/pdf/1310.0171](https://arxiv.org/pdf/1310.0171)

