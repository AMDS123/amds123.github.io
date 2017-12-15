---
layout: post
title: "SemiContour: A Semi-supervised Learning Approach for Contour Detection"
date: 2016-05-17 01:33:20
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Segmentation Detection
author: Zizhao Zhang, Fuyong Xing, Xiaoshuang Shi, Lin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised contour detection methods usually require many labeled training images to obtain satisfactory performance. However, a large set of annotated data might be unavailable or extremely labor intensive. In this paper, we investigate the usage of semi-supervised learning (SSL) to obtain competitive detection accuracy with very limited training data (three labeled images). Specifically, we propose a semi-supervised structured ensemble learning approach for contour detection built on structured random forests (SRF). To allow SRF to be applicable to unlabeled data, we present an effective sparse representation approach to capture inherent structure in image patches by finding a compact and discriminative low-dimensional subspace representation in an unsupervised manner, enabling the incorporation of abundant unlabeled patches with their estimated structured labels to help SRF perform better node splitting. We re-examine the role of sparsity and propose a novel and fast sparse coding algorithm to boost the overall learning efficiency. To the best of our knowledge, this is the first attempt to apply SSL for contour detection. Extensive experiments on the BSDS500 segmentation dataset and the NYU Depth dataset demonstrate the superiority of the proposed method.

##### Abstract (translated by Google)
监督轮廓检测方法通常需要许多标记的训练图像以获得令人满意的性能。但是，大量注释数据可能不可用或者非常劳动密集。在本文中，我们调查半监督学习（SSL）的使用，以获得有限的训练数据（三个标记的图像）的竞争检测准确性。具体来说，我们提出了一种基于结构随机森林（SRF）的轮廓检测半监督结构集成学习方法。为了使SRF适用于未标记的数据，我们提出了一种有效的稀疏表示方法来捕获图像块中的固有结构，方法是以无监督的方式找到一个紧凑且有区别的低维子空间表示，从而能够将大量未标记的块与其估计结构化的标签来帮助SRF执行更好的节点分割。重新审视稀疏性的作用，提出一种新颖快速的稀疏编码算法，提高整体学习效率。就我们所知，这是第一次尝试使用SSL进行轮廓检测。在BSDS500分割数据集和NYU深度数据集上的大量实验证明了所提出方法的优越性。

##### URL
[https://arxiv.org/abs/1605.04996](https://arxiv.org/abs/1605.04996)

##### PDF
[https://arxiv.org/pdf/1605.04996](https://arxiv.org/pdf/1605.04996)

