---
layout: post
title: "Fast Semantic Segmentation on Video Using Motion Vector-Based Feature Interpolation"
date: 2018-03-21 04:05:45
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Inference Prediction
author: Samvit Jain, Joseph E. Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Models optimized for accuracy on challenging, dense prediction tasks such as semantic segmentation entail significant inference costs, and are prohibitively slow to run on each frame in a video. Since nearby video frames are spatially similar, however, there is substantial opportunity to reuse computation. Existing work has explored basic feature reuse and feature warping based on optical flow, but has encountered limits to the speedup attainable with these techniques. In this paper, we present a new, two part approach to accelerating inference on video. Firstly, we propose a fast feature propagation scheme that utilizes the block motion vector maps present in compressed video to cheaply propagate features from frame to frame. Secondly, we develop a novel feature estimation scheme, termed feature interpolation, that fuses features propagated from enclosing keyframes to render accurate feature estimates, even at sparse keyframe frequencies. We evaluate our system on the Cityscapes dataset, comparing to both a frame-by-frame baseline and related work. We find that we are able to substantially accelerate segmentation on video, achieving almost twice the average inference speed as prior work at any target accuracy level.

##### Abstract (translated by Google)
对具有挑战性的高密度预测任务（如语义分割）进行精度优化的模型会带来显着的推理成本，并且在视频中的每帧上运行速度过于缓慢。由于附近的视频帧在空间上是相似的，但是，重用计算有很大的机会。现有的工作已经探索了基于光流的基本特征重用和特征变形，但是已经遇到了使用这些技术可实现的加速的限制。在本文中，我们提出了一种新的两部分方法来加速对视频的推断。首先，我们提出了一种快速特征传播方案，该方案利用压缩视频中存在的块运动矢量图来便宜地传播帧间特征。其次，我们开发了一种新的特征估计方案，称为特征插值，即使在稀疏关键帧频率下，该特征融合从围绕关键帧传播的特征以提供精确的特征估计。我们在Cityscapes数据集上评估我们的系统，并与逐帧基线和相关工作进行比较。我们发现，我们能够大幅加快视频分割速度，在任何目标精度级别上实现的平均推理速度几乎是先前工作的两倍。

##### URL
[http://arxiv.org/abs/1803.07742](http://arxiv.org/abs/1803.07742)

##### PDF
[http://arxiv.org/pdf/1803.07742](http://arxiv.org/pdf/1803.07742)

