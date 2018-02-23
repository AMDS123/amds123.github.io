---
layout: post
title: "Glimpse Clouds: Human Activity Recognition from Unstructured Feature Points"
date: 2018-02-22 04:09:30
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Action_Recognition Prediction Recognition
author: Fabien Baradel, Christian Wolf, Julien Mille, Graham W. Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for human activity recognition from RGB data which does not rely on any pose information during test time, and which does not explicitly calculate pose information internally. Instead, a visual attention module learns to predict glimpse sequences in each frame. These glimpses correspond to interest points in the scene which are relevant to the classified activities. No spatial coherence is forced on the glimpse locations, which gives the module liberty to explore different points at each frame and better optimize the process of scrutinizing visual information. Tracking and sequentially integrating this kind of unstructured data is a challenge, which we address by separating the set of glimpses from a set of recurrent tracking/recognition workers. These workers receive the glimpses, jointly performing subsequent motion tracking and prediction of the activity itself. The glimpses are soft-assigned to the workers, optimizing coherence of the assignments in space, time and feature space using an external memory module. No hard decisions are taken, i.e. each glimpse point is assigned to all existing workers, albeit with different importance. Our methods outperform state-of-the-art methods on the largest human activity recognition dataset available to-date; NTU RGB+D Dataset, and on a smaller human action recognition dataset Northwestern-UCLA Multiview Action 3D Dataset.

##### Abstract (translated by Google)
我们提出了一种从RGB数据中进行人体活动识别的方法，该方法在测试时间内不依赖任何姿态信息，并且不会在内部明确计算姿态信息。相反，视觉关注模块学习预测每帧中的一瞥序列。这些瞥见对应于场景中与分类活动相关的兴趣点。在瞥见位置上不需要空间连贯性，这使得模块可以自由地探索每一帧的不同点，并更好地优化仔细检查视觉信息的过程。跟踪和顺序整合这种非结构化数据是一项挑战，我们通过从一组反复跟踪/识别工作人员中分离出一组瞥见来解决这个问题。这些工作人员收到了一丝曙光，共同执行后续的活动跟踪和活动本身的预测。这些瞥见是软分配给工作人员的，通过使用外部存储器模块来优化空间，时间和特征空间分配的一致性。没有做出艰难的决定，即将每个瞥点分配给所有现有的工人，尽管具有不同的重要性。我们的方法在迄今为止最大的人类活动识别数据集上优于最先进的方法; NTU RGB + D数据集，以及较小的人类动作识别数据集Northwestern-UCLA Multiview Action 3D Dataset。

##### URL
[http://arxiv.org/abs/1802.07898](http://arxiv.org/abs/1802.07898)

##### PDF
[http://arxiv.org/pdf/1802.07898](http://arxiv.org/pdf/1802.07898)

