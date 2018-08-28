---
layout: post
title: "Fusion++: Volumetric Object-Level SLAM"
date: 2018-08-25 08:37:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Prediction Quantitative Detection SLAM
author: John McCormac, Ronald Clark, Michael Bloesch, Andrew J. Davison, Stefan Leutenegger
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an online object-level SLAM system which builds a persistent and accurate 3D graph map of arbitrary reconstructed objects. As an RGB-D camera browses a cluttered indoor scene, Mask-RCNN instance segmentations are used to initialise compact per-object Truncated Signed Distance Function (TSDF) reconstructions with object size-dependent resolutions and a novel 3D foreground mask. Reconstructed objects are stored in an optimisable 6DoF pose graph which is our only persistent map representation. Objects are incrementally refined via depth fusion, and are used for tracking, relocalisation and loop closure detection. Loop closures cause adjustments in the relative pose estimates of object instances, but no intra-object warping. Each object also carries semantic information which is refined over time and an existence probability to account for spurious instance predictions. We demonstrate our approach on a hand-held RGB-D sequence from a cluttered office scene with a large number and variety of object instances, highlighting how the system closes loops and makes good use of existing objects on repeated loops. We quantitatively evaluate the trajectory error of our system against a baseline approach on the RGB-D SLAM benchmark, and qualitatively compare reconstruction quality of discovered objects on the YCB video dataset. Performance evaluation shows our approach is highly memory efficient and runs online at 4-8Hz (excluding relocalisation) despite not being optimised at the software level.

##### Abstract (translated by Google)
我们提出了一种在线对象级SLAM系统，该系统可以构建任意重建对象的持久且准确的3D图形图。当RGB-D相机浏览杂乱的室内场景时，Mask-RCNN实例分割用于初始化具有对象大小相关分辨率的紧凑的每对象截断的符号距离函数（TSDF）重建和新的3D前景掩模。重建的对象存储在可优化的6DoF姿势图中，这是我们唯一的持久地图表示。物体通过深度融合逐步细化，并用于跟踪，重定位和环闭合检测。循环闭包导致对象实例的相对姿势估计的调整，但没有对象内变形。每个对象还携带随时间细化的语义信息和存在概率以解释虚假实例预测。我们在一个杂乱的办公室场景中展示我们对手持RGB-D序列的方法，该场景具有大量不同的对象实例，突出显示系统如何关闭循环并在重复循环中充分利用现有对象。我们定量地评估我们的系统的轨迹误差与RGB-D SLAM基准上的基线方法，并定性地比较YCB视频数据集上发现的对象的重建质量。性能评估显示我们的方法具有高内存效率，并且在4-8Hz（不包括重定位）的情况下在线运行，尽管没有在软件级别进行优化。

##### URL
[http://arxiv.org/abs/1808.08378](http://arxiv.org/abs/1808.08378)

##### PDF
[http://arxiv.org/pdf/1808.08378](http://arxiv.org/pdf/1808.08378)

