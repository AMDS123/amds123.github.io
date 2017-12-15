---
layout: post
title: "Online Domain Adaptation for Multi-Object Tracking"
date: 2015-08-04 14:01:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Quantitative Detection
author: Adrien Gaidon, Eleonora Vig
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically detecting, labeling, and tracking objects in videos depends first and foremost on accurate category-level object detectors. These might, however, not always be available in practice, as acquiring high-quality large scale labeled training datasets is either too costly or impractical for all possible real-world application scenarios. A scalable solution consists in re-using object detectors pre-trained on generic datasets. This work is the first to investigate the problem of on-line domain adaptation of object detectors for causal multi-object tracking (MOT). We propose to alleviate the dataset bias by adapting detectors from category to instances, and back: (i) we jointly learn all target models by adapting them from the pre-trained one, and (ii) we also adapt the pre-trained model on-line. We introduce an on-line multi-task learning algorithm to efficiently share parameters and reduce drift, while gradually improving recall. Our approach is applicable to any linear object detector, and we evaluate both cheap "mini-Fisher Vectors" and expensive "off-the-shelf" ConvNet features. We quantitatively measure the benefit of our domain adaptation strategy on the KITTI tracking benchmark and on a new dataset (PASCAL-to-KITTI) we introduce to study the domain mismatch problem in MOT.

##### Abstract (translated by Google)
自动检测，标记和跟踪视频中的对象首先取决于准确的类别级别的对象检测器。然而，这些可能在实践中并不总是可用，因为获取高质量大规模标记的训练数据集对于所有可能的现实世界的应用场景来说代价太高或不切实际。可扩展的解决方案包括在通用数据集上重新使用预先训练的对象检测器。这项工作是第一个研究物体检测器的因果多目标跟踪（MOT）的在线域适应问题。我们提出通过将检测器从类别到实例进行自适应，从而减轻数据集偏差：（i）我们通过从预先训练的模型中适应所有目标模型来联合学习所有的目标模型;（ii）我们也调整预先训练的模型-线。我们引入了在线多任务学习算法来有效地共享参数，减少漂移，同时逐步提高召回率。我们的方法适用于任何线性物体检测器，我们评估便宜的“迷你费舍尔矢量”和昂贵的“现成”ConvNet功能。我们定量测量了我们的领域适应策略对KITTI跟踪基准和我们介绍的用于研究MOT中的领域不匹配问题的新数据集（PASCAL-to-KITTI）的益处。

##### URL
[https://arxiv.org/abs/1508.00776](https://arxiv.org/abs/1508.00776)

##### PDF
[https://arxiv.org/pdf/1508.00776](https://arxiv.org/pdf/1508.00776)

