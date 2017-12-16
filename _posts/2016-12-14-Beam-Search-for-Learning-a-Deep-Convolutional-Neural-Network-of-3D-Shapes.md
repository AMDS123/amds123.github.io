---
layout: post
title: "Beam Search for Learning a Deep Convolutional Neural Network of 3D Shapes"
date: 2016-12-14 19:06:05
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Xu Xu, Sinisa Todorovic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses 3D shape recognition. Recent work typically represents a 3D shape as a set of binary variables corresponding to 3D voxels of a uniform 3D grid centered on the shape, and resorts to deep convolutional neural networks(CNNs) for modeling these binary variables. Robust learning of such CNNs is currently limited by the small datasets of 3D shapes available, an order of magnitude smaller than other common datasets in computer vision. Related work typically deals with the small training datasets using a number of ad hoc, hand-tuning strategies. To address this issue, we formulate CNN learning as a beam search aimed at identifying an optimal CNN architecture, namely, the number of layers, nodes, and their connectivity in the network, as well as estimating parameters of such an optimal CNN. Each state of the beam search corresponds to a candidate CNN. Two types of actions are defined to add new convolutional filters or new convolutional layers to a parent CNN, and thus transition to children states. The utility function of each action is efficiently computed by transferring parameter values of the parent CNN to its children, thereby enabling an efficient beam search. Our experimental evaluation on the 3D ModelNet dataset demonstrates that our model pursuit using the beam search yields a CNN with superior performance on 3D shape classification than the state of the art.

##### Abstract (translated by Google)
本文介绍了三维形状识别。最近的工作通常将3D形状表示为与以形状为中心的均匀3D网格的3D体素相对应的一组二进制变量，并且使用深度卷积神经网络（CNN）来对这些二进制变量建模。这种CNN的稳健学习目前受限于可用的三维形状的小数据集，比计算机视觉中的其他常见数据集小一个数量级。相关工作通常使用一些特设的手动调整策略来处理小型训练数据集。为了解决这个问题，我们将CNN学习制定为波束搜索，目的在于识别最优的CNN架构，即层数，节点及其在网络中的连通性，以及估计这种最优CNN的参数。波束搜索的每个状态对应于候选CNN。定义了两种类型的动作，将新的卷积过滤器或新的卷积层添加到父CNN，从而过渡到子状态。每个动作的效用函数通过将父CNN的参数值传送到其子节点来有效地计算，从而实现有效的波束搜索。我们对3D ModelNet数据集的实验评估表明，我们使用波束搜索的模型追求产生了比现有技术更好的三维形状分类性能的CNN。

##### URL
[https://arxiv.org/abs/1612.04774](https://arxiv.org/abs/1612.04774)

##### PDF
[https://arxiv.org/pdf/1612.04774](https://arxiv.org/pdf/1612.04774)

