---
layout: post
title: "A Maximum A Posteriori Estimation Framework for Robust High Dynamic Range Video Synthesis"
date: 2016-12-08 18:33:08
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Yuelong Li, Chul Lee, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
High dynamic range (HDR) image synthesis from multiple low dynamic range (LDR) exposures continues to be actively researched. The extension to HDR video synthesis is a topic of significant current interest due to potential cost benefits. For HDR video, a stiff practical challenge presents itself in the form of accurate correspondence estimation of objects between video frames. In particular, loss of data resulting from poor exposures and varying intensity make conventional optical flow methods highly inaccurate. We avoid exact correspondence estimation by proposing a statistical approach via maximum a posterior (MAP) estimation, and under appropriate statistical assumptions and choice of priors and models, we reduce it to an optimization problem of solving for the foreground and background of the target frame. We obtain the background through rank minimization and estimate the foreground via a novel multiscale adaptive kernel regression technique, which implicitly captures local structure and temporal motion by solving an unconstrained optimization problem. Extensive experimental results on both real and synthetic datasets demonstrate that our algorithm is more capable of delivering high-quality HDR videos than current state-of-the-art methods, under both subjective and objective assessments. Furthermore, a thorough complexity analysis reveals that our algorithm achieves better complexity-performance trade-off than conventional methods.

##### Abstract (translated by Google)
继续积极研究来自多个低动态范围（LDR）曝光的高动态范围（HDR）图像合成。由于潜在的成本效益，HDR视频合成的扩展是目前重要的话题。对于HDR视频来说，一个严峻的实际挑战是以视频帧之间对象的精确对应估计的形式呈现出来的。特别是由于曝光不足和强度不同导致的数据丢失使得传统的光学流动方法非常不准确。我们通过最大后验（MAP）估计提出一种统计方法来避免精确的对应性估计，并且在合适的统计假设和先验和模型的选择下，我们将其减少到解决目标帧的前景和背景的优化问题。我们通过秩最小化获得背景，并通过新的多尺度自适应核回归技术估计前景，通过解决无约束优化问题隐式捕捉局部结构和时间运动。在真实和合成数据集上的广泛的实验结果表明，在主观和客观评估下，我们的算法能够提供比当前最先进的方法更高质量的HDR视频。此外，全面的复杂性分析显示，我们的算法实现了比传统方法更好的复杂性能折衷。

##### URL
[https://arxiv.org/abs/1612.02761](https://arxiv.org/abs/1612.02761)

##### PDF
[https://arxiv.org/pdf/1612.02761](https://arxiv.org/pdf/1612.02761)

