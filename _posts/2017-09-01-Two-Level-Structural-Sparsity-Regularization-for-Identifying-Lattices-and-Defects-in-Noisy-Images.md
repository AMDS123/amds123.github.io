---
layout: post
title: "Two-Level Structural Sparsity Regularization for Identifying Lattices and Defects in Noisy Images"
date: 2017-09-01 19:22:15
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Xin Li, Alex Belianinov, Ondrej Dyck, Stephen Jesse, Chiwoo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a regularized regression model with a two-level structural sparsity penalty applied to locate individual atoms in a noisy scanning transmission electron microscopy image (STEM). In crystals, the locations of atoms is symmetric, condensed into a few lattice groups. Therefore, by identifying the underlying lattice in a given image, individual atoms can be accurately located. We propose to formulate the identification of the lattice groups as a sparse group selection problem. Furthermore, real atomic scale images contain defects and vacancies, so atomic identification based solely on a lattice group may result in false positives and false negatives. To minimize error, model includes an individual sparsity regularization in addition to the group sparsity for a within-group selection, which results in a regression model with a two-level sparsity regularization. We propose a modification of the group orthogonal matching pursuit (gOMP) algorithm with a thresholding step to solve the atom finding problem. The convergence and statistical analyses of the proposed algorithm are presented. The proposed algorithm is also evaluated through numerical experiments with simulated images. The applicability of the algorithm on determination of atom structures and identification of imaging distortions and atomic defects was demonstrated using three real STEM images. We believe this is an important step toward automatic phase identification and assignment with the advent of genomic databases for materials.

##### Abstract (translated by Google)
本文提出了一个正则化的回归模型，应用两级结构稀疏罚分来定位个体原子在噪声扫描透射电子显微镜图像（STEM）。在晶体中，原子的位置是对称的，凝聚成几个晶格组。因此，通过识别给定图像中的基础晶格，可以准确地定位各个原子。我们建议将格组的识别作为稀疏组选择问题。此外，真实的原子尺度图像包含缺陷和空位，因此仅基于晶格组的原子识别可能会导致误报和漏报。为了使误差最小化，除了群内稀疏选择之外，模型还包括个体稀疏正则化，其导致具有两级稀疏正则化的回归模型。我们提出了修改组正交匹配追踪（gOMP）算法的阈值步骤来解决原子发现问题。给出了算法的收敛性和统计分析。所提出的算法也通过数值实验与模拟图像进行评估。该算法的适用性确定的原子结构和成像失真和原子缺陷的识别是演示使用三个真正的STEM图像。我们相信，随着材料基因组数据库的出现，这是朝自动化阶段鉴定和分配迈出的重要一步。

##### URL
[https://arxiv.org/abs/1611.08280](https://arxiv.org/abs/1611.08280)

##### PDF
[https://arxiv.org/pdf/1611.08280](https://arxiv.org/pdf/1611.08280)

