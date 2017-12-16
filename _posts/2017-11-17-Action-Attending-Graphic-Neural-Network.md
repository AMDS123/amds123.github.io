---
layout: post
title: "Action-Attending Graphic Neural Network"
date: 2017-11-17 06:32:09
categories: arXiv_CV
tags: arXiv_CV Salient Action_Recognition Recognition
author: Chaolong Li, Zhen Cui, Wenming Zheng, Chunyan Xu, Rongrong Ji, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The motion analysis of human skeletons is crucial for human action recognition, which is one of the most active topics in computer vision. In this paper, we propose a fully end-to-end action-attending graphic neural network (A$^2$GNN) for skeleton-based action recognition, in which each irregular skeleton is structured as an undirected attribute graph. To extract high-level semantic representation from skeletons, we perform the local spectral graph filtering on the constructed attribute graphs like the standard image convolution operation. Considering not all joints are informative for action analysis, we design an action-attending layer to detect those salient action units (AUs) by adaptively weighting skeletal joints. Herein the filtering responses are parameterized into a weighting function irrelevant to the order of input nodes. To further encode continuous motion variations, the deep features learnt from skeletal graphs are gathered along consecutive temporal slices and then fed into a recurrent gated network. Finally, the spectral graph filtering, action-attending and recurrent temporal encoding are integrated together to jointly train for the sake of robust action recognition as well as the intelligibility of human actions. To evaluate our A$^2$GNN, we conduct extensive experiments on four benchmark skeleton-based action datasets, including the large-scale challenging NTU RGB+D dataset. The experimental results demonstrate that our network achieves the state-of-the-art performances.

##### Abstract (translated by Google)
人体骨骼运动分析是人类行为识别的关键，也是计算机视觉中最活跃的话题之一。在本文中，我们提出了一个基于骨架的动作识别的完全端到端的动作图形神经网络（A $ ^ 2 $ GNN），其中每个不规则骨架被构造为一个无向属性图。为了从骨架中提取高层次的语义表示，我们对构造的属性图像进行局部谱图过滤，如标准图像卷积运算。考虑到并非所有的关节都是行动分析的信息，我们设计了一个行动参与层，通过自适应地加权骨骼关节来检测这些显着行动单位（AU）。这里，过滤响应被参数化为与输入节点的顺序无关的加权函数。为了进一步编码连续运动变化，从骨架图学习的深度特征沿着连续的时间切片收集，然后馈送到经常性的门控网络。最后，将频谱图滤波，动作参考和循环时间编码集成在一起，共同训练，以实现鲁棒行为识别以及人类行为的可理解性。为了评估我们的A $ ^ 2 $ GNN，我们在四个基准的基于骨架的动作数据集上进行了广泛的实验，其中包括大型的具有挑战性的NTU RGB + D数据集。实验结果表明，我们的网络达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1711.06427](https://arxiv.org/abs/1711.06427)

##### PDF
[https://arxiv.org/pdf/1711.06427](https://arxiv.org/pdf/1711.06427)

