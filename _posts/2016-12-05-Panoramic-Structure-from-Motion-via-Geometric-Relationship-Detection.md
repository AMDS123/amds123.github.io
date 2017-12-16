---
layout: post
title: "Panoramic Structure from Motion via Geometric Relationship Detection"
date: 2016-12-05 06:24:10
categories: arXiv_CV
tags: arXiv_CV Face Detection Relation
author: Satoshi Ikehata, Ivaylo Boyadzhiev, Qi Shan, Yasutaka Furukawa
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of Structure from Motion (SfM) for indoor panoramic image streams, extremely challenging even for the state-of-the-art due to the lack of textures and minimal parallax. The key idea is the fusion of single-view and multi-view reconstruction techniques via geometric relationship detection (e.g., detecting 2D lines as coplanar in 3D). Rough geometry suffices to perform such detection, and our approach utilizes rough surface normal estimates from an image-to-normal deep network to discover geometric relationships among lines. The detected relationships provide exact geometric constraints in our line-based linear SfM formulation. A constrained linear least squares is used to reconstruct a 3D model and camera motions, followed by the bundle adjustment. We have validated our algorithm on challenging datasets, outperforming various state-of-the-art reconstruction techniques.

##### Abstract (translated by Google)
本文针对室内全景图像流的运动结构（SfM）问题，由于缺乏纹理和最小的视差，即使对于最新的技术也是极具挑战性的。关键思想是通过几何关系检测（例如，将2D线检测为3D中的共面）融合单视图和多视图重建技术。粗糙的几何图形足以执行这种检测，我们的方法利用从图像到正常深度网络的粗糙表面法线估计来发现线条之间的几何关系。检测到的关系在我们基于行的线性SfM公式中提供了精确的几何约束。约束线性最小二乘用于重建3D模型和相机运动，然后是束调整。我们验证了我们的算法在具有挑战性的数据集上，超越了各种最先进的重建技术。

##### URL
[https://arxiv.org/abs/1612.01256](https://arxiv.org/abs/1612.01256)

##### PDF
[https://arxiv.org/pdf/1612.01256](https://arxiv.org/pdf/1612.01256)

