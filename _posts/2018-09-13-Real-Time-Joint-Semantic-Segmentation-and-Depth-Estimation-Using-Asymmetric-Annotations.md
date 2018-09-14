---
layout: post
title: "Real-Time Joint Semantic Segmentation and Depth Estimation Using Asymmetric Annotations"
date: 2018-09-13 04:19:26
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Semantic_Segmentation Deep_Learning Quantitative
author: Vladimir Nekrasov, Thanuja Dharmasiri, Andrew Spek, Tom Drummond, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Deployment of deep learning models in robotics as sensory information extractors can be a daunting task to handle, even using generic GPU cards. Here, we address three of its most prominent hurdles, namely, i) the adaptation of a single model to perform multiple tasks at once (in this work, we consider depth estimation and semantic segmentation crucial for acquiring geometric and semantic understanding of the scene), while ii) doing it in real-time, and iii) using asymmetric datasets with uneven numbers of annotations per each modality. To overcome the first two issues, we adapt a recently proposed real-time semantic segmentation network, making few changes to further reduce the number of floating point operations. To approach the third issue, we embrace a simple solution based on hard knowledge distillation under the assumption of having access to a powerful `teacher' network. Finally, we showcase how our system can be easily extended to handle more tasks, and more datasets, all at once. Quantitatively, we achieve 42% mean iou, 0.56m RMSE (lin) and 0.20 RMSE (log) with a single model on NYUDv2-40, 87% mean iou, 3.45m RMSE (lin) and 0.18 RMSE (log) on KITTI-6 for segmentation and KITTI for depth estimation, with one forward pass costing just 17ms and 6.45 GFLOPs on 1200x350 inputs. All these results are either equivalent to (or better than) current state-of-the-art approaches, which were achieved with larger and slower models solving each task separately.

##### Abstract (translated by Google)
在机器人中部署深度学习模型作为感官信息提取器可能是一项艰巨的任务，即使使用通用GPU卡也是如此。在这里，我们解决了三个最突出的障碍，即i）单个模型的适应性同时执行多个任务（在这项工作中，我们考虑深度估计和语义分割对获取场景的几何和语义理解至关重要） ，ii）实时完成，以及iii）使用每种模态具有不均匀数量的注释的不对称数据集。为了克服前两个问题，我们调整了最近提出的实时语义分段网络，几乎没有进行任何更改以进一步减少浮点运算的数量。为了解决第三个问题，我们采用了基于硬知识蒸馏的简单解决方案，假设可以访问强大的“教师”网络。最后，我们展示了如何轻松扩展我们的系统以同时处理更多任务和更多数据集。定量地，我们在NYUDv2-40上使用单个模型获得42％平均值，0.56m RMSE（lin）和0.20 RMSE（log），在KITTI上获得87％平均值，3.45m RMSE（lin）和0.18 RMSE（log） 6用于分段，KITTI用​​于深度估计，一个正向通过仅需17ms，在1200x350输入上通过6.45 GFLOP。所有这些结果或者等同于（或者更好）当前最先进的方法，这些方法是通过分别解决每个任务的更大和更慢的模型来实现的。

##### URL
[http://arxiv.org/abs/1809.04766](http://arxiv.org/abs/1809.04766)

##### PDF
[http://arxiv.org/pdf/1809.04766](http://arxiv.org/pdf/1809.04766)

