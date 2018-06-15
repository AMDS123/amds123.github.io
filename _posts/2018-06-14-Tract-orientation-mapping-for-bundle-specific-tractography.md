---
layout: post
title: "Tract orientation mapping for bundle-specific tractography"
date: 2018-06-14 14:38:06
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Recognition
author: Jakob Wasserthal, Peter F. Neher, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
While the major white matter tracts are of great interest to numerous studies in neuroscience and medicine, their manual dissection in larger cohorts from diffusion MRI tractograms is time-consuming, requires expert knowledge and is hard to reproduce. Tract orientation mapping (TOM) is a novel concept that facilitates bundle-specific tractography based on a learned mapping from the original fiber orientation distribution function (fODF) peaks to a list of tract orientation maps (also abbr. TOM). Each TOM represents one of the known tracts with each voxel containing no more than one orientation vector. TOMs can act as a prior or even as direct input for tractography. We use an encoder-decoder fully-convolutional neural network architecture to learn the required mapping. In comparison to previous concepts for the reconstruction of specific bundles, the presented one avoids various cumbersome processing steps like whole brain tractography, atlas registration or clustering. We compare it to four state of the art bundle recognition methods on 20 different bundles in a total of 105 subjects from the Human Connectome Project. Results are anatomically convincing even for difficult tracts, while reaching low angular errors, unprecedented runtimes and top accuracy values (Dice). Our code and our data are openly available.

##### Abstract (translated by Google)
尽管主要的白质束在神经科学和医学领域的众多研究中引起了极大的兴趣，但它们在扩散MRI束图中较大的队列中进行的手动解剖是耗时的，需要专业知识并且难以再现。根据从原始纤维取向分布函数（fODF）峰到道路取向图（缩写TOM）的列表的学习映射，道定向映射（TOM）是一种新颖的概念，有利于束特定的纤维束成像。每个TOM表示其中一个已知区域，每个体素只包含一个方向矢量。 TOM可以作为事先或甚至作为纤维束成像的直接输入。我们使用编码器 - 解码器全卷积神经网络架构来学习所需的映射。与以前的重建特定束的概念相比，本文提出的避免了像整个脑纤维束成像，图谱配准或聚类等繁琐的处理步骤。我们将其与来自Human Connectome项目的共105个科目的20个不同包中的四种最先进的包识别方法进行比较。结果在解剖学上令人信服，即使对于困难的小块，同时达到低角度误差，前所未有的运行时间和最高准确度值（骰子）。我们的代码和我们的数据是公开可用的。

##### URL
[http://arxiv.org/abs/1806.05580](http://arxiv.org/abs/1806.05580)

##### PDF
[http://arxiv.org/pdf/1806.05580](http://arxiv.org/pdf/1806.05580)

