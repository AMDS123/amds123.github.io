---
layout: post
title: "Multiview 2D/3D Rigid Registration via a Point-Of-Interest Network for Tracking and Triangulation"
date: 2019-03-10 01:03:46
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization
author: Haofu Liao, Wei-An Lin, Jiarui Zhang, Jingdan Zhang, Jiebo Luo, S. Kevin Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to tackle the problem of multiview 2D/3D rigid registration for intervention via a Point-Of-Interest Network for Tracking and Triangulation (POINT^2). POINT^2 learns to establish 2D point-to-point correspondences between the pre- and intra-intervention images by tracking a set of random POIs. The 3D pose of the pre-intervention volume is then estimated through a triangulation layer. In POINT^2, the unified framework of the POI tracker and the triangulation layer enables learning informative 2D features and estimating 3D pose jointly. In contrast to existing approaches, POINT^2 only requires a single forward-pass to achieve a reliable 2D/3D registration. As the POI tracker is shift-invariant, POINT^2 is more robust to the initial pose of the 3D pre-intervention image. Extensive experiments on a large-scale clinical cone-beam CT (CBCT) dataset show that the proposed POINT^2 method outperforms the existing learning-based method in terms of accuracy, robustness and running time. Furthermore, when used as an initial pose estimator, our method also improves the robustness and speed of the state-of-the-art optimization-based approaches by ten folds.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03896](https://arxiv.org/abs/1903.03896)

##### PDF
[https://arxiv.org/pdf/1903.03896](https://arxiv.org/pdf/1903.03896)

