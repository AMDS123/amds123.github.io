---
layout: post
title: "Re-ranking Object Proposals for Object Detection in Automatic Driving"
date: 2016-05-20 01:45:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Zhun Zhong, Mingyi Lei, Shaozi Li, Jianping Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection often suffers from a plenty of bootless proposals, selecting high quality proposals remains a great challenge. In this paper, we propose a semantic, class-specific approach to re-rank object proposals, which can consistently improve the recall performance even with less proposals. We first extract features for each proposal including semantic segmentation, stereo information, contextual information, CNN-based objectness and low-level cue, and then score them using class-specific weights learnt by Structured SVM. The advantages of the proposed model are twofold: 1) it can be easily merged to existing generators with few computational costs, and 2) it can achieve high recall rate uner strict critical even using less proposals. Experimental evaluation on the KITTI benchmark demonstrates that our approach significantly improves existing popular generators on recall performance. Moreover, in the experiment conducted for object detection, even with 1,500 proposals, our approach can still have higher average precision (AP) than baselines with 5,000 proposals.

##### Abstract (translated by Google)
对象检测往往会遭受大量无谓的建议，选择高质量的建议仍然是一个很大的挑战。在本文中，我们提出了一种语义的，特定于类的方法来重新排列对象提议，即使提议较少，也可以持续提高召回性能。我们首先为每个提议提取特征，包括语义分割，立体信息，上下文信息，基于CNN的对象和低级提示，然后使用结构化SVM学习的特定于类的权重对它们进行评分。该模型的优点有两个：1）可以很容易地与现有的发电机合并，计算成本较低; 2）即使使用较少的建议，也可以实现高召回率。 KITTI基准测试的实验评估表明，我们的方法显着改善了现有流行的发电机对召回性能的影响。而且，在进行物体检测的实验中，即使有1500个提议，我们的方法仍然可以比具有5000个提议的基线更高的平均精确度（AP）。

##### URL
[https://arxiv.org/abs/1605.05904](https://arxiv.org/abs/1605.05904)

##### PDF
[https://arxiv.org/pdf/1605.05904](https://arxiv.org/pdf/1605.05904)

