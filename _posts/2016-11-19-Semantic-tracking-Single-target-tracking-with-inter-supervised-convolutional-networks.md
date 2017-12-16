---
layout: post
title: "Semantic tracking: Single-target tracking with inter-supervised convolutional networks"
date: 2016-11-19 16:10:03
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Classification
author: Jingjing Xiao, Qiang Lan, Linbo Qiao, Ales Leonardis
mathjax: true
---

* content
{:toc}

##### Abstract
This article presents a semantic tracker which simultaneously tracks a single target and recognises its category. In general, it is hard to design a tracking model suitable for all object categories, e.g., a rigid tracker for a car is not suitable for a deformable gymnast. Category-based trackers usually achieve superior tracking performance for the objects of that specific category, but have difficulties being generalised. Therefore, we propose a novel unified robust tracking framework which explicitly encodes both generic features and category-based features. The tracker consists of a shared convolutional network (NetS), which feeds into two parallel networks, NetC for classification and NetT for tracking. NetS is pre-trained on ImageNet to serve as a generic feature extractor across the different object categories for NetC and NetT. NetC utilises those features within fully connected layers to classify the object category. NetT has multiple branches, corresponding to multiple categories, to distinguish the tracked object from the background. Since each branch in NetT is trained by the videos of a specific category or groups of similar categories, NetT encodes category-based features for tracking. During online tracking, NetC and NetT jointly determine the target regions with the right category and foreground labels for target estimation. To improve the robustness and precision, NetC and NetT inter-supervise each other and trigger network adaptation when their outputs are ambiguous for the same image regions (i.e., when the category label contradicts the foreground/background classification). We have compared the performance of our tracker to other state-of-the-art trackers on a large-scale tracking benchmark (100 sequences)---the obtained results demonstrate the effectiveness of our proposed tracker as it outperformed other 38 state-of-the-art tracking algorithms.

##### Abstract (translated by Google)
本文提出了一个语义跟踪器，它可以同时跟踪一个目标并识别其类别。一般来说，很难设计适用于所有对象类别的跟踪模型，例如，汽车的刚性跟踪器不适用于可变形的体操运动员。基于分类的跟踪器通常对于该特定类别的对象实现优越的跟踪性能，但难以被推广。因此，我们提出了一种新的统一的健壮跟踪框架，明确地编码泛型特征和基于类别的特征。跟踪器由一个共享的卷积网络（NetS）组成，该网络馈入两个并行网络，NetC用于分类，NetT用于跟踪。 NetS预先在ImageNet上训练，作为NetC和NetT的不同对象类别的通用特征提取器。 NetC利用完全连接的层中的这些功能来分类对象类别。 NetT有多个分支，对应于多个分类，以区分跟踪对象和背景。由于NetT中的每个分支都由特定类别的视频或类似类别的组进行训练，NetT对基于类别的特征进行编码以进行跟踪。在线跟踪过程中，NetC和NetT联合确定目标区域，并使用正确的类别和前景标签进行目标评估。为了提高鲁棒性和精确度，当NetC和NetT的输出对于相同图像区域模糊时（即，当类别标签与前景/背景分类相矛盾时），NetC和NetT相互监督并触发网络适应。我们已经将跟踪器的性能与大规模跟踪基准（100个序列）上的其他最先进的跟踪器的性能进行了比较 - 所获得的结果证明了我们提出的跟踪器的有效性，因为其超过了其他状态最先进的跟踪算法。

##### URL
[https://arxiv.org/abs/1611.06395](https://arxiv.org/abs/1611.06395)

##### PDF
[https://arxiv.org/pdf/1611.06395](https://arxiv.org/pdf/1611.06395)

