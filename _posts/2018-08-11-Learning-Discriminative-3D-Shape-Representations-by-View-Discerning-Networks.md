---
layout: post
title: "Learning Discriminative 3D Shape Representations by View Discerning Networks"
date: 2018-08-11 16:09:45
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Biao Leng, Cheng Zhang, Xiaocheng Zhou, Cheng Xu, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In view-based 3D shape recognition, extracting discriminative visual representation of 3D shapes from projected images is considered the core problem. Projections with low discriminative ability can adversely influence the final 3D shape representation. Especially under the real situations with background clutter and object occlusion, the adverse effect is even more severe. To resolve this problem, we propose a novel deep neural network, View Discerning Network, which learns to judge the quality of views and adjust their contributions to the representation of shapes. In this network, a Score Generation Unit is devised to evaluate the quality of each projected image with score vectors. These score vectors are used to weight the image features and the weighted features perform much better than original features in 3D shape recognition task. In particular, we introduce two structures of Score Generation Unit, Channel-wise Score Unit and Part-wise Score Unit, to assess the quality of feature maps from different perspectives. Our network aggregates features and scores in an end-to-end framework, so that final shape descriptors are directly obtained from its output. Our experiments on ModelNet and ShapeNet Core55 show that View Discerning Network outperforms the state-of-the-arts in terms of the retrieval task, with excellent robustness against background clutter and object occlusion.

##### Abstract (translated by Google)
在基于视图的3D形状识别中，从投影图像中提取3D形状的辨别视觉表示被认为是核心问题。具有低辨别能力的投影会对最终的3D形状表示产生不利影响。特别是在背景杂乱和物体遮挡的实际情况下，不利影响甚至更严重。为了解决这个问题，我们提出了一种新颖的深度神经网络，即查看识别网络，它可以学习判断视图的质量并调整它们对形状表示的贡献。在该网络中，设计了分数生成单元以利用分数向量来评估每个投影图像的质量。这些得分向量用于加权图像特征，并且加权特征比3D形状识别任务中的原始特征执行得更好。特别是，我们引入了两个分数生成单元，渠道分数单元和分数分数单元结构，从不同角度评估特征地图的质量。我们的网络在端到端框架中聚合特征和分数，以便最终形状描述符直接从其输出中获得。我们在ModelNet和ShapeNet Core55上的实验表明，View Discerning Network在检索任务方面优于现有技术，具有出色的抗背景杂乱和对象遮挡的鲁棒性。

##### URL
[http://arxiv.org/abs/1808.03823](http://arxiv.org/abs/1808.03823)

##### PDF
[http://arxiv.org/pdf/1808.03823](http://arxiv.org/pdf/1808.03823)

