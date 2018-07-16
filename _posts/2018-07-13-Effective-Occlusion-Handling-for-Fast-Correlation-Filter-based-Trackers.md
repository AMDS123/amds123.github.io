---
layout: post
title: "Effective Occlusion Handling for Fast Correlation Filter-based Trackers"
date: 2018-07-13 01:23:24
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Zheng Zhang, Yang Li, Jinwei Ren, Jianke Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filter-based trackers heavily suffer from the problem of multiple peaks in their response maps incurred by occlusions. Moreover, the whole tracking pipeline may break down due to the uncertainties brought by shifting among peaks, which will further lead to the degraded correlation filter model. To alleviate the drift problem caused by occlusions, we propose a novel scheme to choose the specific filter model according to different scenarios. Specifically, an effective measurement function is designed to evaluate the quality of filter response. A sophisticated strategy is employed to judge whether occlusions occur, and then decide how to update the filter models. In addition, we take advantage of both log-polar method and pyramid-like approach to estimate the best scale of the target. We evaluate our proposed approach on VOT2018 challenge and OTB100 dataset, whose experimental result shows that the proposed tracker achieves the promising performance compared against the state-of-the-art trackers.

##### Abstract (translated by Google)
基于相关滤波器的跟踪器严重地受到由遮挡引起的响应图中的多个峰值的问题。此外，由于峰值之间的偏移带来的不确定性，整个跟踪流水线可能会中断，这将进一步导致相关滤波器模型的退化。为了缓解由遮挡引起的漂移问题，我们提出了一种根据不同场景选择特定滤波器模型的新方案。具体而言，设计有效的测量功能来评估滤波器响应的质量。采用复杂的策略来判断是否发生遮挡，然后决定如何更新滤波器模型。此外，我们利用对数极坐标方法和类金字塔方法来估计目标的最佳尺度。我们评估了我们在VOT2018挑战和OTB100数据集上提出的方法，其实验结果表明，与最先进的跟踪器相比，所提出的跟踪器实现了有希望的性能。

##### URL
[http://arxiv.org/abs/1807.04880](http://arxiv.org/abs/1807.04880)

##### PDF
[http://arxiv.org/pdf/1807.04880](http://arxiv.org/pdf/1807.04880)

