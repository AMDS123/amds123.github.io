---
layout: post
title: "Occlusion-Aware Human Pose Estimation with Mixtures of Sub-Trees"
date: 2015-12-03 12:25:33
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference Prediction Relation
author: Ibrahim Radwan, Abhinav Dhall, Roland Goecke
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of learning a model for human pose estimation as mixtures of compositional sub-trees in two layers of prediction. This involves estimating the pose of a sub-tree followed by identifying the relationships between sub-trees that are used to handle occlusions between different parts. The mixtures of the sub-trees are learnt utilising both geometric and appearance distances. The Chow-Liu (CL) algorithm is recursively applied to determine the inter-relations between the nodes and to build the structure of the sub-trees. These structures are used to learn the latent parameters of the sub-trees and the inference is done using a standard belief propagation technique. The proposed method handles occlusions during the inference process by identifying overlapping regions between different sub-trees and introducing a penalty term for overlapping parts. Experiments are performed on three different datasets: the Leeds Sports, Image Parse and UIUC People datasets. The results show the robustness of the proposed method to occlusions over the state-of-the-art approaches.

##### Abstract (translated by Google)
在本文中，我们研究了将人体姿态估计模型学习为两层预测中组合子树混合的问题。这包括估计子树的姿态，然后标识用于处理不同部分之间的遮挡的子树之间的关系。利用几何和外观距离来学习子树的混合。 Chow-Liu（CL）算法被递归地应用于确定节点之间的相互关系并构建子树的结构。这些结构用于学习子树的潜在参数，并且使用标准置信传播技术来进行推理。所提出的方法在推理过程中通过识别不同子树之间的重叠区域并且为重叠部分引入惩罚项来处理闭塞。实验在三个不同的数据集上进行：Leeds Sports，Image Parse和UIUC People数据集。结果显示了所提出的方法对最先进方法的闭塞的鲁棒性。

##### URL
[https://arxiv.org/abs/1512.01055](https://arxiv.org/abs/1512.01055)

##### PDF
[https://arxiv.org/pdf/1512.01055](https://arxiv.org/pdf/1512.01055)

