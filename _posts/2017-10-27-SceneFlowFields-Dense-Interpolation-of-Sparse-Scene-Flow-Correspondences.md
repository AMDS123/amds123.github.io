---
layout: post
title: "SceneFlowFields: Dense Interpolation of Sparse Scene Flow Correspondences"
date: 2017-10-27 12:03:37
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Optimization
author: René Schuster, Oliver Wasenmüller, Georg Kuschk, Christian Bailer, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
While most scene flow methods use either variational optimization or a strong rigid motion assumption, we show for the first time that scene flow can also be estimated by dense interpolation of sparse matches. To this end, we find sparse matches across two stereo image pairs that are detected without any prior regularization and perform dense interpolation preserving geometric and motion boundaries by using edge information. A few iterations of variational energy minimization are performed to refine our results, which are thoroughly evaluated on the KITTI benchmark and additionally compared to state-of-the-art on MPI Sintel. For application in an automotive context, we further show that an optional ego-motion model helps to boost performance and blends smoothly into our approach to produce a segmentation of the scene into static and dynamic parts.

##### Abstract (translated by Google)
虽然大多数场景流方法使用变分优化或强刚性运动假设，但是我们首次显示，通过稀疏匹配的密集插值也可以估计场景流。为此，我们发现在没有任何预先正则化的情况下检测到的两个立体图像对之间的稀疏匹配，并且通过使用边缘信息执行保密几何和运动边界的密集插值。进行几次迭代的变分能量最小化，以改进我们的结果，这些结果在KITTI基准测试中进行了全面评估，并与MPI Sintel的最新技术进行了比较。对于在汽车领域的应用，我们进一步表明，可选的自我运动模型有助于提高性能，并顺利融入到我们的方法中，将场景分割成静态和动态部分。

##### URL
[https://arxiv.org/abs/1710.10096](https://arxiv.org/abs/1710.10096)

##### PDF
[https://arxiv.org/pdf/1710.10096](https://arxiv.org/pdf/1710.10096)

