---
layout: post
title: "Visual Tracking via Learning Dynamic Patch-based Graph Representation"
date: 2017-10-04 03:00:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Classification Detection
author: Chenglong Li, Liang Lin, Wangmeng Zuo, Jin Tang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing visual tracking methods usually localize a target object with a bounding box, in which the performance of the foreground object trackers or detectors is often affected by the inclusion of background clutter. To handle this problem, we learn a patch-based graph representation for visual tracking. The tracked object is modeled by with a graph by taking a set of non-overlapping image patches as nodes, in which the weight of each node indicates how likely it belongs to the foreground and edges are weighted for indicating the appearance compatibility of two neighboring nodes. This graph is dynamically learned and applied in object tracking and model updating. During the tracking process, the proposed algorithm performs three main steps in each frame. First, the graph is initialized by assigning binary weights of some image patches to indicate the object and background patches according to the predicted bounding box. Second, the graph is optimized to refine the patch weights by using a novel alternating direction method of multipliers. Third, the object feature representation is updated by imposing the weights of patches on the extracted image features. The object location is predicted by maximizing the classification score in the structured support vector machine. Extensive experiments show that the proposed tracking algorithm performs well against the state-of-the-art methods on large-scale benchmark datasets.

##### Abstract (translated by Google)
现有的视觉跟踪方法通常使用边界框来定位目标对象，其中前景对象跟踪器或检测器的性能通常受包含背景杂波的影响。为了解决这个问题，我们学习了基于补丁的图形表示来进行视觉追踪。通过将一组不重叠的图像块作为节点，利用图来建模被跟踪对象，其中每个节点的权重指示它可能属于前景的可能性，并且加权边缘以指示两个相邻节点的外观兼容性。这个图形是动态学习和应用对象跟踪和模型更新。在跟踪过程中，所提出的算法在每个帧中执行三个主要步骤。首先，通过分配一些图像块的二进制权重来初始化图形，以根据预测的边界框来指示对象和背景块。其次，通过使用乘法器的新颖的交替方向方法来优化图形以优化贴片权重。第三，通过在提取的图像特征上施加贴片的权重来更新对象特征表示。通过使结构化支持向量机中的分类分数最大化来预测对象位置。广泛的实验表明，所提出的跟踪算法在大规模基准数据集上与最先进的方法相比表现良好。

##### URL
[https://arxiv.org/abs/1710.01444](https://arxiv.org/abs/1710.01444)

##### PDF
[https://arxiv.org/pdf/1710.01444](https://arxiv.org/pdf/1710.01444)

