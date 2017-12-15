---
layout: post
title: "PiMPeR: Piecewise Dense 3D Reconstruction from Multi-View and Multi-Illumination Images"
date: 2015-03-17 12:59:24
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Reza Sabzevari, Vittori Murino, Alessio Del Bue
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of dense 3D reconstruction from multiple view images subject to strong lighting variations. In this regard, a new piecewise framework is proposed to explicitly take into account the change of illumination across several wide-baseline images. Unlike multi-view stereo and multi-view photometric stereo methods, this pipeline deals with wide-baseline images that are uncalibrated, in terms of both camera parameters and lighting conditions. Such a scenario is meant to avoid use of any specific imaging setup and provide a tool for normal users without any expertise. To the best of our knowledge, this paper presents the first work that deals with such unconstrained setting. We propose a coarse-to-fine approach, in which a coarse mesh is first created using a set of geometric constraints and, then, fine details are recovered by exploiting photometric properties of the scene. Augmenting the fine details on the coarse mesh is done via a final optimization step. Note that the method does not provide a generic solution for multi-view photometric stereo problem but it relaxes several common assumptions of this problem. The approach scales very well in size given its piecewise nature, dealing with large scale optimization and with severe missing data. Experiments on a benchmark dataset Robot data-set show the method performance against 3D ground truth.

##### Abstract (translated by Google)
在本文中，我们解决了从强烈的光照变化的多视图图像密集三维重建的问题。在这方面，提出了一个新的分段框架，明确考虑到几个宽基线图像的照明变化。与多视点立体和多视点光度立体方法不同，该流水线可处理未校准的宽基线图像，无论是摄像机参数还是照明条件。这种情况意味着避免使用任何特定的成像设置，并为没有任何专业知识的普通用户提供工具。就我们所知，本文提出了处理这种不受约束的环境的第一个工作。我们提出了一个粗到细的方法，其中首先使用一组几何约束创建粗网格，然后通过利用场景的光度属性来恢复细节。通过最终优化步骤来增加粗网格上的细节。请注意，该方法不提供多视图光度立体问题的通用解决方案，但是放松了这个问题的几个常见假设。考虑到其分段性，这种方法的规模非常好，处理大规模优化和严重缺失数据。基准数据集上的实验机器人数据集显示了针对3D地面真实的方法性能。

##### URL
[https://arxiv.org/abs/1503.04598](https://arxiv.org/abs/1503.04598)

##### PDF
[https://arxiv.org/pdf/1503.04598](https://arxiv.org/pdf/1503.04598)

