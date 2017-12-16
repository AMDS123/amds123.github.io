---
layout: post
title: "Human pose estimation via Convolutional Part Heatmap Regression"
date: 2016-09-06 20:25:30
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection Relation
author: Adrian Bulat, Georgios Tzimiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is on human pose estimation using Convolutional Neural Networks. Our main contribution is a CNN cascaded architecture specifically designed for learning part relationships and spatial context, and robustly inferring pose even for the case of severe part occlusions. To this end, we propose a detection-followed-by-regression CNN cascade. The first part of our cascade outputs part detection heatmaps and the second part performs regression on these heatmaps. The benefits of the proposed architecture are multi-fold: It guides the network where to focus in the image and effectively encodes part constraints and context. More importantly, it can effectively cope with occlusions because part detection heatmaps for occluded parts provide low confidence scores which subsequently guide the regression part of our network to rely on contextual information in order to predict the location of these parts. Additionally, we show that the proposed cascade is flexible enough to readily allow the integration of various CNN architectures for both detection and regression, including recent ones based on residual learning. Finally, we illustrate that our cascade achieves top performance on the MPII and LSP data sets. Code can be downloaded from this http URL

##### Abstract (translated by Google)
本文是关于使用卷积神经网络的人体姿态估计。我们的主要贡献是专门设计用于学习部分关系和空间环境的CNN级联结构，并且即使对于严重部分遮挡的情况也能够强有力地推断姿态。为此，我们提出一种检测 - 随后的回归CNN级联。我们级联的第一部分输出部分检测热图，第二部分对这些热图进行回归。所提出的体系结构的好处是多方面的：它引导网络集中在图像中，并有效地编码部分约束和上下文。更重要的是，它可以有效地应对遮挡，因为遮挡部分的部分检测热图提供低置信度分数，随后指导我们网络的回归部分依靠上下文信息来预测这些部分的位置。此外，我们表明，所提出的级联是足够灵活的，以容易地允许整合各种CNN架构的检测和回归，包括最近的基于残留学习。最后，我们说明我们的级联在MPII和LSP数据集上达到最高性能。代码可以从这个http URL下载

##### URL
[https://arxiv.org/abs/1609.01743](https://arxiv.org/abs/1609.01743)

##### PDF
[https://arxiv.org/pdf/1609.01743](https://arxiv.org/pdf/1609.01743)

