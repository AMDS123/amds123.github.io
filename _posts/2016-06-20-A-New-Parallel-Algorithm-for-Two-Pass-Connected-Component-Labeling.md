---
layout: post
title: "A New Parallel Algorithm for Two-Pass Connected Component Labeling"
date: 2016-06-20 05:13:28
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Siddharth Gupta, Diana Palsetia, Md. Mostofa Ali Patwary, Ankit Agrawal, Alok Choudhary
mathjax: true
---

* content
{:toc}

##### Abstract
Connected Component Labeling (CCL) is an important step in pattern recognition and image processing. It assigns labels to the pixels such that adjacent pixels sharing the same features are assigned the same label. Typically, CCL requires several passes over the data. We focus on two-pass technique where each pixel is given a provisional label in the first pass whereas an actual label is assigned in the second pass. We present a scalable parallel two-pass CCL algorithm, called PAREMSP, which employs a scan strategy and the best union-find technique called REMSP, which uses REM's algorithm for storing label equivalence information of pixels in a 2-D image. In the first pass, we divide the image among threads and each thread runs the scan phase along with REMSP simultaneously. In the second phase, we assign the final labels to the pixels. As REMSP is easily parallelizable, we use the parallel version of REMSP for merging the pixels on the boundary. Our experiments show the scalability of PAREMSP achieving speedups up to $20.1$ using $24$ cores on shared memory architecture using OpenMP for an image of size $465.20$ MB. We find that our proposed parallel algorithm achieves linear scaling for a large resolution fixed problem size as the number of processing elements are increased. Additionally, the parallel algorithm does not make use of any hardware specific routines, and thus is highly portable.

##### Abstract (translated by Google)
连通组件标签（CCL）是模式识别和图像处理中的一个重要步骤。它为像素分配标签，使得共享相同特征的相邻像素被分配相同的标签。通常，CCL需要数据传递。我们专注于双通道技术，其中每个像素在第一遍中被赋予一个临时标签，而在第二遍中赋予一个实际的标签。我们提出了一种称为PAREMSP的可扩展并行双通CCL算法，该算法采用扫描策略和最佳联合发现技术（称为REMSP），其使用REM的算法来存储二维图像中的像素的标签等价信息。在第一遍中，我们将图像在线程之间进行划分，每个线程与REMSP一起同时运行扫描阶段。在第二阶段，我们将最终的标签分配给像素。由于REMSP易于并行化，因此我们使用REMSP的并行版本来合并边界上的像素。我们的实验显示，使用OpenMP的共享内存架构上的$ 24 $内核，PAREMSP可实现高达$ 20.1 $的可扩展性，图像大小为$ 465.20 $ MB。我们发现，我们提出的并行算法实现了一个大的分辨率固定问题的大小线性缩放随着处理单元的数量增加。此外，并行算法不使用任何硬件特定的例程，因此是高度便携的。

##### URL
[https://arxiv.org/abs/1606.05973](https://arxiv.org/abs/1606.05973)

##### PDF
[https://arxiv.org/pdf/1606.05973](https://arxiv.org/pdf/1606.05973)

