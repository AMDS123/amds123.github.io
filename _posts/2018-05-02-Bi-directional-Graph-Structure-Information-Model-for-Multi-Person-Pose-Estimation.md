---
layout: post
title: "Bi-directional Graph Structure Information Model for Multi-Person Pose Estimation"
date: 2018-05-02 02:25:28
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Jing Wang<wangjingzzu@gs.zzu.edu.cn>, Junyi Sun<jysun@ha.edu.cn>, Ze Peng<zpeng@ha.edu.cn>, Pei Lv<ielvpei@zzu.edu.cn>, Bing Zhou<iebzhou@zzu.edu.cn>, Mingliang Xu<iexumingliang@zzu.edu.cn>
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel multi-stage network architecture with two branches in each stage to estimate multi-person poses in images. The first branch predicts the confidence maps of joints and uses a geometrical transform kernel to propagate information between neighboring joints at the confidence level. The second branch proposes a bi-directional graph structure information model (BGSIM) to encode rich contextual information and to infer the occlusion relationship among different joints. We dynamically determine the joint point with highest response of the confidence maps as base point of passing message in BGSIM. Based on the proposed network structure, we achieve an average precision of 62.9 on the COCO Keypoint Challenge dataset and 77.6 on the MPII (multi-person) dataset. Compared with other state-of-art methods, our method can achieve highly promising results on our selected multi-person dataset without extra training.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的多阶段网络架构，在每个阶段有两个分支来估计图像中的多人姿势。第一个分支预测关节的置信度图，并使用几何变换核在置信水平上在相邻关节之间传播信息。第二个分支提出了一个双向图结构信息模型（BGSIM）来编码丰富的上下文信息并推断不同关节之间的遮挡关系。我们动态地确定信心映射的最高响应点作为BGSIM中消息传递的基点。根据所提出的网络结构，我们在COCO关键点挑战数据集上得到62.9的平均精度，在MPII（多人）数据集上得到77.6的平均精度。与其他最先进的方法相比，我们的方法可以在没有额外训练的情况下在我们选择的多人数据集上取得非常有前途的结果。

##### URL
[https://arxiv.org/abs/1805.00603](https://arxiv.org/abs/1805.00603)

##### PDF
[https://arxiv.org/pdf/1805.00603](https://arxiv.org/pdf/1805.00603)

