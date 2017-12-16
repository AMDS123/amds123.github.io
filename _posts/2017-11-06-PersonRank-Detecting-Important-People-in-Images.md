---
layout: post
title: "PersonRank: Detecting Important People in Images"
date: 2017-11-06 16:09:50
categories: arXiv_CV
tags: arXiv_CV
author: Wei-Hong Li, Benchao Li, Wei-Shi Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Always, some individuals in images are more important/attractive than others in some events such as presentation, basketball game or speech. However, it is challenging to find important people among all individuals in images directly based on their spatial or appearance information due to the existence of diverse variations of pose, action, appearance of persons and various changes of occasions. We overcome this difficulty by constructing a multiple Hyper-Interaction Graph to treat each individual in an image as a node and inferring the most active node referring to interactions estimated by various types of clews. We model pairwise interactions between persons as the edge message communicated between nodes, resulting in a bidirectional pairwise-interaction graph. To enrich the personperson interaction estimation, we further introduce a unidirectional hyper-interaction graph that models the consensus of interaction between a focal person and any person in a local region around. Finally, we modify the PageRank algorithm to infer the activeness of persons on the multiple Hybrid-Interaction Graph (HIG), the union of the pairwise-interaction and hyperinteraction graphs, and we call our algorithm the PersonRank. In order to provide publicable datasets for evaluation, we have contributed a new dataset called Multi-scene Important People Image Dataset and gathered a NCAA Basketball Image Dataset from sports game sequences. We have demonstrated that the proposed PersonRank outperforms related methods clearly and substantially.

##### Abstract (translated by Google)
总是在一些事件中，比如在演讲，篮球比赛或演讲中，图像中的一些人比其他人更重要/有吸引力。然而，由于姿势，动作，人物的外观和场合的各种变化的存在，直接根据其空间或外观信息在所有图像中找到重要人物是具有挑战性的。我们通过构建一个多重超交互图来克服这个困难，将图像中的每个个体作为一个节点来处理，并且推断出指向由各种类型的线索所估计的交互作用的最活跃的节点。我们将人与人之间的相互作用建模为在节点之间传递的边缘消息，从而产生双向的成对交互图。为了丰富人际互动估计，我们进一步引入了一个单向的超互动图，它模拟了一个焦点人与周围地区任何人之间的互动共识。最后，我们修改PageRank算法来推断多重混合交互图（HIG）上的人的活动性，成对交互图和超交互图的联合，我们称该算法为PersonRank。为了提供可评估的可公开数据集，我们提供了一个名为多场景重要人物图像数据集的新数据集，并从体育游戏序列中收集了NCAA篮球图像数据集。我们已经证明，拟议的PersonRank比相关的方法明显和大幅。

##### URL
[https://arxiv.org/abs/1711.01984](https://arxiv.org/abs/1711.01984)

##### PDF
[https://arxiv.org/pdf/1711.01984](https://arxiv.org/pdf/1711.01984)

