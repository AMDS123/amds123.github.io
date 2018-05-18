---
layout: post
title: "A Robust Background Initialization Algorithm with Superpixel Motion Detection"
date: 2018-05-17 12:52:57
categories: arXiv_CV
tags: arXiv_CV Detection
author: Zhe Xu, Biao Min, Ray C.C. Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Scene background initialization allows the recovery of a clear image without foreground objects from a video sequence, which is generally the first step in many computer vision and video processing applications. The process may be strongly affected by some challenges such as illumination changes, foreground cluttering, intermittent movement, etc. In this paper, a robust background initialization approach based on superpixel motion detection is proposed. Both spatial and temporal characteristics of frames are adopted to effectively eliminate foreground objects. A subsequence with stable illumination condition is first selected for background estimation. Images are segmented into superpixels to preserve spatial texture information and foreground objects are eliminated by superpixel motion filtering process. A low-complexity density-based clustering is then performed to generate reliable background candidates for final background determination. The approach has been evaluated on SBMnet dataset and it achieves a performance superior or comparable to other state-of-the-art works with faster processing speed. Moreover, in those complex and dynamic categories, the algorithm produces the best results showing the robustness against very challenging scenarios.

##### Abstract (translated by Google)
场景背景初始化允许在没有来自视频序列的前景对象的情况下恢复清晰图像，这通常是许多计算机视觉和视频处理应用中的第一步。该过程可能会受到光照变化，前景杂乱，间歇运动等一些挑战的强烈影响。本文提出了一种基于超像素运动检测的鲁棒背景初始化方法。采用帧的空间和时间特征来有效消除前景物体。首先选择具有稳定照明条件的子序列用于背景估计。图像被分割成超像素以保存空间纹理信息，并且通过超像素运动滤波处理来消除前景对象。然后执行低复杂度的基于密度的聚类以生成用于最终背景确定的可靠背景候选。该方法已在SBMnet数据集上进行了评估，并且其性能优于或与其他具有更快处理速度的最先进作品相媲美。而且，在这些复杂而动态的类别中，该算法产生了最好的结果，显示了对于非常具有挑战性的场景的鲁棒性。

##### URL
[http://arxiv.org/abs/1805.06737](http://arxiv.org/abs/1805.06737)

##### PDF
[http://arxiv.org/pdf/1805.06737](http://arxiv.org/pdf/1805.06737)

