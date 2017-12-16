---
layout: post
title: "Robust Keyframe-based Dense SLAM with an RGB-D Camera"
date: 2017-11-14 16:18:04
categories: arXiv_CV
tags: arXiv_CV Face Tracking Optimization SLAM
author: Haomin Liu, Chen Li, Guojun Chen, Guofeng Zhang, Michael Kaess, Hujun Bao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present RKD-SLAM, a robust keyframe-based dense SLAM approach for an RGB-D camera that can robustly handle fast motion and dense loop closure, and run without time limitation in a moderate size scene. It not only can be used to scan high-quality 3D models, but also can satisfy the demand of VR and AR applications. First, we combine color and depth information to construct a very fast keyframe-based tracking method on a CPU, which can work robustly in challenging cases (e.g.~fast camera motion and complex loops). For reducing accumulation error, we also introduce a very efficient incremental bundle adjustment (BA) algorithm, which can greatly save unnecessary computation and perform local and global BA in a unified optimization framework. An efficient keyframe-based depth representation and fusion method is proposed to generate and timely update the dense 3D surface with online correction according to the refined camera poses of keyframes through BA. The experimental results and comparisons on a variety of challenging datasets and TUM RGB-D benchmark demonstrate the effectiveness of the proposed system.

##### Abstract (translated by Google)
在本文中，我们介绍RKD-SLAM，这是一种基于关键帧的鲁棒密集SLAM方法，可以稳健地处理快速运动和密集闭环，并在中等大小的场景中无时间限制地运行。它不仅可以扫描高质量的3D模型，而且可以满足VR和AR应用的需求。首先，我们将颜色和深度信息结合起来，在CPU上构建一个非常快速的基于关键帧的跟踪方法，可以在具有挑战性的情况下（例如快速摄像机运动和复杂环路）稳健地工作。为了减少累积误差，我们还引入了一个非常有效的增量式捆绑调整（BA）算法，它可以大大节省不必要的计算，并在统一的优化框架中执行局部和全局BA。提出了一种基于关键帧的高效深度表示和融合方法，通过BA根据关键帧的精确摄像机姿态，通过在线校正生成并及时更新密集三维表面。实验结果和各种具有挑战性的数据集和TUM RGB-D基准的比较证明了所提出的系统的有效性。

##### URL
[https://arxiv.org/abs/1711.05166](https://arxiv.org/abs/1711.05166)

##### PDF
[https://arxiv.org/pdf/1711.05166](https://arxiv.org/pdf/1711.05166)

