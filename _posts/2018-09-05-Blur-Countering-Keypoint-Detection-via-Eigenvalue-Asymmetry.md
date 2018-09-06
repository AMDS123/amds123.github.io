---
layout: post
title: "Blur-Countering Keypoint Detection via Eigenvalue Asymmetry"
date: 2018-09-05 12:24:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Quantitative Detection
author: Chao Zhang, Xuequan Lu, Takuya Akashi
mathjax: true
---

* content
{:toc}

##### Abstract
Well-known corner or local extrema feature based detectors such as FAST and DoG have achieved noticeable successes. However, detecting keypoints in the presence of blur has remained to be an unresolved issue. As a matter of fact, various kinds of blur (e.g., motion blur, out-of-focus, and space-variant) remarkably increase challenges for keypoint detection. As a result, those methods have limited performance. To settle this issue, we propose a blur-countering method for detecting valid keypoints for various types and degrees of blurred images. Specifically, we first present a distance metric for derivative distributions, which preserves the distinctiveness of patch pairs well under blur. We then model the asymmetry by utilizing the difference of squared eigenvalues based on the distance metric. To make it scale-robust, we also extend it to scale space. The proposed detector is efficient as the main computational cost is the square of derivatives at each pixel. Extensive visual and quantitative results show that our method outperforms current approaches under different types and degrees of blur. Without any parallelization, our implementation\footnote{We will make our code publicly available upon the acceptance.} achieves real-time performance for low-resolution images (e.g., $320\times240$ pixel).

##### Abstract (translated by Google)
众所周知的角落或基于局部极值特征的检测器（如FAST和DoG）已经取得了显着的成功。然而，在存在模糊的情况下检测关键点仍然是未解决的问题。事实上，各种模糊（例如，运动模糊，离焦和空间变化）显着增加了关键点检测的挑战。结果，这些方法的性能有限。为了解决这个问题，我们提出了一种模糊对抗方法，用于检测各种类型和程度的模糊图像的有效关键点。具体来说，我们首先给出导数分布的距离度量，它在模糊下很好地保留了补丁对的独特性。然后，我们通过利用基于距离度量的平方特征值的差异来对不对称性进行建模。为了使其具有规模稳健性，我们还将其扩展到规模空间。所提出的检测器是有效的，因为主要的计算成本是每个像素处的导数的平方。广泛的视觉和定量结果表明，我们的方法在不同类型和程度的模糊下优于当前方法。没有任何并行化，我们的实现\脚注{我们将在接受时公开提供我们的代码。}实现低分辨率图像的实时性能（例如，$ 320 \ times240 $ pixel）。

##### URL
[http://arxiv.org/abs/1809.01456](http://arxiv.org/abs/1809.01456)

##### PDF
[http://arxiv.org/pdf/1809.01456](http://arxiv.org/pdf/1809.01456)

