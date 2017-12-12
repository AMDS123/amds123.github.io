---
layout: post
title: "Tracking using Numerous Anchor points"
date: 2017-12-10 21:31:28
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Tanushri Chakravorty, Guillaume-Alexandre Bilodeau, Eric Granger
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an online adaptive model-free tracker is proposed to track single objects in video sequences to deal with real-world tracking challenges like low-resolution, object deformation, occlusion and motion blur. The novelty lies in the construction of a strong appearance model that captures features from the initialized bounding box and then are assembled into anchor-point features. These features memorize the global pattern of the object and have an internal star graph-like structure. These features are unique and flexible and helps tracking generic and deformable objects with no limitation on specific objects. In addition, the relevance of each feature is evaluated online using short-term consistency and long-term consistency. These parameters are adapted to retain consistent features that vote for the object location and that deal with outliers for long-term tracking scenarios. Additionally, voting in a Gaussian manner helps in tackling inherent noise of the tracking system and in accurate object localization. Furthermore, the proposed tracker uses pairwise distance measure to cope with scale variations and combines pixel-level binary features and global weighted color features for model update. Finally, experimental results on a visual tracking benchmark dataset are presented to demonstrate the effectiveness and competitiveness of the proposed tracker.

##### Abstract (translated by Google)
本文提出了一种在线自适应无模型跟踪器来跟踪视频序列中的单个物体，以解决低分辨率，物体变形，遮挡和运动模糊等实际跟踪难题。新颖之处在于构建了一个强大的外观模型，该模型从初始化的边界框中捕获特征，然后被组合成锚点特征。这些特征记住了对象的全局模式，并具有内部星形图结构。这些功能是独特而灵活的，有助于跟踪通用和可变形的物体，而不受特定物体的限制。此外，使用短期一致性和长期一致性，在线评估每个功能的相关性。这些参数适用于保留对物体位置投票的一致特征，并针对长期跟踪情景处理异常值。另外，以高斯方式进行投票有助于解决跟踪系统的固有噪声和准确的物体定位。此外，所提出的跟踪器使用成对距离度量来应对尺度变化，并将像素级二进制特征和全局加权颜色特征组合以用于模型更新。最后，提出了一个视觉跟踪基准数据集的实验结果，以证明所提出的跟踪器的有效性和竞争力。

##### URL
[http://arxiv.org/abs/1702.02012](http://arxiv.org/abs/1702.02012)

##### PDF
[http://arxiv.org/pdf/1702.02012](http://arxiv.org/pdf/1702.02012)

