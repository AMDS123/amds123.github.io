---
layout: post
title: "A Survey of Structure from Motion"
date: 2017-05-09 01:19:41
categories: arXiv_CV
tags: arXiv_CV Review Survey SLAM
author: Onur Ozyesil, Vladislav Voroninski, Ronen Basri, Amit Singer
mathjax: true
---

* content
{:toc}

##### Abstract
The structure from motion (SfM) problem in computer vision is the problem of recovering the three-dimensional ($3$D) structure of a stationary scene from a set of projective measurements, represented as a collection of two-dimensional ($2$D) images, via estimation of motion of the cameras corresponding to these images. In essence, SfM involves the three main stages of (1) extraction of features in images (e.g., points of interest, lines, etc.) and matching these features between images, (2) camera motion estimation (e.g., using relative pairwise camera positions estimated from the extracted features), and (3) recovery of the $3$D structure using the estimated motion and features (e.g., by minimizing the so-called reprojection error). This survey mainly focuses on relatively recent developments in the literature pertaining to stages (2) and (3). More specifically, after touching upon the early factorization-based techniques for motion and structure estimation, we provide a detailed account of some of the recent camera location estimation methods in the literature, followed by discussion of notable techniques for $3$D structure recovery. We also cover the basics of the simultaneous localization and mapping (SLAM) problem, which can be viewed as a specific case of the SfM problem. Further, our survey includes a review of the fundamentals of feature extraction and matching (i.e., stage (1) above), various recent methods for handling ambiguities in $3$D scenes, SfM techniques involving relatively uncommon camera models and image features, and popular sources of data and SfM software.

##### Abstract (translated by Google)
计算机视觉中的运动结构（SfM）问题是从一组投影测量中恢复静止场景的三维（$ 3 $ D）结构的问题，表示为二维（$ 2 $ D）图像，通过估计与这些图像对应的摄像机的运动。实质上，SfM包括以下三个主要阶段：（1）提取图像中的特征（例如，兴趣点，线条等）并且在图像之间匹配这些特征;（2）相机运动估计（例如，使用相对成对相机（3）使用估计的运动和特征（例如通过最小化所谓的再投影误差）恢复$ 3 $ D结构。本调查主要集中在与第（2）和第（3）阶段有关的文献的相对最新进展。更具体地说，在介绍了用于运动和结构估计的早期分解技术之后，我们详细地介绍了文献中最近的一些相机位置估计方法，随后讨论了用于$ 3 $ D结构恢复的显着技术。我们还介绍了同时定位和映射（SLAM）问题的基础知识，它可以被看作是SfM问题的一个具体案例。此外，我们的调查包括回顾特征提取和匹配的基础（即上面的阶段（1）），处理$ 3 $ D场景中的歧义的各种最新方法，涉及相对不常见的相机模型和图像特征的SfM技术，以及流行数据来源和SfM软件。

##### URL
[https://arxiv.org/abs/1701.08493](https://arxiv.org/abs/1701.08493)

##### PDF
[https://arxiv.org/pdf/1701.08493](https://arxiv.org/pdf/1701.08493)

