---
layout: post
title: "Robust SfM with Little Image Overlap"
date: 2017-03-28 09:57:56
categories: arXiv_CV
tags: arXiv_CV
author: Yohann Salaun, Renaud Marlet, Pascal Monasse
mathjax: true
---

* content
{:toc}

##### Abstract
Usual Structure-from-Motion (SfM) techniques require at least trifocal overlaps to calibrate cameras and reconstruct a scene. We consider here scenarios of reduced image sets with little overlap, possibly as low as two images at most seeing the same part of the scene. We propose a new method, based on line coplanarity hypotheses, for estimating the relative scale of two independent bifocal calibrations sharing a camera, without the need of any trifocal information or Manhattan-world assumption. We use it to compute SfM in a chain of up-to-scale relative motions. For accuracy, we however also make use of trifocal information for line and/or point features, when present, relaxing usual trifocal constraints. For robustness to wrong assumptions and mismatches, we embed all constraints in a parameterless RANSAC-like approach. Experiments show that we can calibrate datasets that previously could not, and that this wider applicability does not come at the cost of inaccuracy.

##### Abstract (translated by Google)
常用的动态结构（SfM）技术至少需要三焦点重叠才能校准摄像机并重建场景。我们在这里考虑缩小图像集的情景，重叠很少，可能最多只有两幅图像看到场景的相同部分。我们提出了一种基于线共面假设的新方法，用于估计共享相机的两个独立双焦校准的相对尺度，而不需要任何三焦点信息或曼哈顿世界假设。我们用它来计算SfM在一系列的规模相对运动。为了准确性，我们也可以利用线条和/或点特征的三焦点信息（当存在时），放松通常的三焦点约束。为了对错误假设和不匹配的鲁棒性，我们将所有约束嵌入到无参数RANSAC方法中。实验表明，我们可以校准先前无法做到的数据集，而这种更广泛的适用性不会以不准确为代价。

##### URL
[https://arxiv.org/abs/1703.07957](https://arxiv.org/abs/1703.07957)

##### PDF
[https://arxiv.org/pdf/1703.07957](https://arxiv.org/pdf/1703.07957)

