---
layout: post
title: "Adaptive Correlation Filters with Long-Term and Short-Term Memory for Object Tracking"
date: 2017-07-07 18:00:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection Relation
author: Chao Ma, Jia-Bin Huang, Xiaokang Yang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Object tracking is challenging as target objects often undergo drastic appearance changes over time. Recently, adaptive correlation filters have been successfully applied to object tracking. However, tracking algorithms relying on highly adaptive correlation filters are prone to drift due to noisy updates. Moreover, as these algorithms do not maintain long-term memory of target appearance, they cannot recover from tracking failures caused by heavy occlusion or target disappearance in the camera view. In this paper, we propose to learn multiple adaptive correlation filters with both long-term and short-term memory of target appearance for robust object tracking. First, we learn a kernelized correlation filter with an aggressive learning rate for locating target objects precisely. We take into account the appropriate size of surrounding context and the feature representations. Second, we learn a correlation filter over a feature pyramid centered at the estimated target position for predicting scale changes. Third, we learn a complementary correlation filter with a conservative learning rate to maintain long-term memory of target appearance. We use the output responses of this long-term filter to determine if tracking failure occurs. In the case of tracking failures, we apply an incrementally learned detector to recover the target position in a sliding window fashion. Extensive experimental results on large-scale benchmark datasets demonstrate that the proposed algorithm performs favorably against the state-of-the-art methods in terms of efficiency, accuracy, and robustness.

##### Abstract (translated by Google)
对象跟踪是具有挑战性的，因为目标对象经常经历剧烈的外观变化。最近，自适应相关滤波器已经成功应用于对象跟踪。然而，依靠高度自适应相关滤波器的跟踪算法由于噪声更新而容易发生漂移。而且，由于这些算法不能保持对目标外观的长期记忆，所以它们不能从由摄像机视野中的严重遮挡或目标消失引起的追踪失败中恢复。在本文中，我们建议学习多目标外观的长期和短期记忆的多个自适应相关滤波器用于鲁棒目标跟踪。首先，我们学习一个具有主动学习率的核化相关滤波器来精确地定位目标对象。我们考虑周围环境的适当大小和特征表示。其次，我们学习了一个以估计目标位置为中心的特征金字塔上的相关滤波器，以预测尺度变化。第三，我们学习一个保守学习率的互补相关滤波器来保持对目标外观的长期记忆。我们使用这个长期过滤器的输出响应来确定是否发生跟踪失败。在跟踪失败的情况下，我们应用渐进学习的检测器以滑动窗口的方式恢复目标位置。在大规模基准数据集上的广泛的实验结果表明，所提出的算法在效率，准确性和鲁棒性方面对于最先进的方法进行有利的处理。

##### URL
[https://arxiv.org/abs/1707.02309](https://arxiv.org/abs/1707.02309)

##### PDF
[https://arxiv.org/pdf/1707.02309](https://arxiv.org/pdf/1707.02309)

