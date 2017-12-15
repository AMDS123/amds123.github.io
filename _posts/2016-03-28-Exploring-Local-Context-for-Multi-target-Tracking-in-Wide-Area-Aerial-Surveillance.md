---
layout: post
title: "Exploring Local Context for Multi-target Tracking in Wide Area Aerial Surveillance"
date: 2016-03-28 23:47:25
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Optimization Detection Relation
author: Bor-Jeng Chen, Gerard Medioni
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking many vehicles in wide coverage aerial imagery is crucial for understanding events in a large field of view. Most approaches aim to associate detections from frame differencing into tracks. However, slow or stopped vehicles result in long-term missing detections and further cause tracking discontinuities. Relying merely on appearance clue to recover missing detections is difficult as targets are extremely small and in grayscale. In this paper, we address the limitations of detection association methods by coupling it with a local context tracker (LCT), which does not rely on motion detections. On one hand, our LCT learns neighboring spatial relation and tracks each target in consecutive frames using graph optimization. It takes the advantage of context constraints to avoid drifting to nearby targets. We generate hypotheses from sparse and dense flow efficiently to keep solutions tractable. On the other hand, we use detection association strategy to extract short tracks in batch processing. We explicitly handle merged detections by generating additional hypotheses from them. Our evaluation on wide area aerial imagery sequences shows significant improvement over state-of-the-art methods.

##### Abstract (translated by Google)
在大范围的航拍图像中跟踪许多车辆对于理解大视野中的事件至关重要。大多数方法旨在将帧差异检测与轨迹关联起来。但是，缓慢或停车的车辆会导致长时间的检测不到，进一步导致跟踪不连续。仅仅依靠外观线索来恢复缺失的检测是困难的，因为目标是非常小的和灰度的。在本文中，我们通过将其与本地上下文跟踪器（LCT）耦合来解决检测关联方法的局限性，所述LCT不依赖于运动检测。一方面，我们的LCT学习相邻的空间关系，并使用图优化来跟踪连续帧中的每个目标。它利用上下文的约束来避免漂移到附近的目标。我们从稀疏和密集的流动中有效地产生假设，使解决方案易于处理。另一方面，我们使用检测关联策略来提取批量处理中的短轨道。我们明确地处理合并检测，通过产生额外的假设。我们对广域航空影像序列的评估显示，与现有技术方法相比，它有了显着的改进。

##### URL
[https://arxiv.org/abs/1603.08592](https://arxiv.org/abs/1603.08592)

##### PDF
[https://arxiv.org/pdf/1603.08592](https://arxiv.org/pdf/1603.08592)

