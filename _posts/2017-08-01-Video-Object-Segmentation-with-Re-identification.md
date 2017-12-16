---
layout: post
title: "Video Object Segmentation with Re-identification"
date: 2017-08-01 08:17:37
categories: arXiv_CV
tags: arXiv_CV Re-identification Segmentation
author: Xiaoxiao Li, Yuankai Qi, Zhe Wang, Kai Chen, Ziwei Liu, Jianping Shi, Ping Luo, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional video segmentation methods often rely on temporal continuity to propagate masks. Such an assumption suffers from issues like drifting and inability to handle large displacement. To overcome these issues, we formulate an effective mechanism to prevent the target from being lost via adaptive object re-identification. Specifically, our Video Object Segmentation with Re-identification (VS-ReID) model includes a mask propagation module and a ReID module. The former module produces an initial probability map by flow warping while the latter module retrieves missing instances by adaptive matching. With these two modules iteratively applied, our VS-ReID records a global mean (Region Jaccard and Boundary F measure) of 0.699, the best performance in 2017 DAVIS Challenge.

##### Abstract (translated by Google)
传统的视频分割方法通常依靠时间连续性来传播掩码。这样的假设存在诸如漂流和无法处理大位移的问题。为了克服这些问题，我们制定了一个有效的机制，通过自适应对象重新识别来防止目标丢失。具体而言，我们的带有重新识别的视频对象分割（VS-ReID）模型包括掩码传播模块和ReID模块。前一个模块通过流动变形产生初始概率图，而后一个模块通过自适应匹配检索缺失的实例。通过迭代应用这两个模块，我们的VS-ReID记录了一个0.699的全局均值（Region Jaccard和Boundary F度量），这是2017 DAVIS Challenge中的最佳性能。

##### URL
[https://arxiv.org/abs/1708.00197](https://arxiv.org/abs/1708.00197)

##### PDF
[https://arxiv.org/pdf/1708.00197](https://arxiv.org/pdf/1708.00197)

