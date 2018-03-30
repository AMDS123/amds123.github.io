---
layout: post
title: "P2P-NET: Bidirectional Point Displacement Network for Shape Transform"
date: 2018-03-25 14:30:51
categories: arXiv_CV
tags: arXiv_CV Regularization Face
author: Kangxue Yin, Hui Huang, Daniel Cohen-Or, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce P2P-NET, a general-purpose deep neural network which learns geometric transformations between point-based shape representations from two domains, e.g., meso-skeletons and surfaces, partial and complete scans, etc. The architecture of the P2P-NET is that of a bi-directional point displacement network, which transforms a source point set to a target point set with the same cardinality, and vice versa, by applying point-wise displacement vectors learned from data. P2P-NET is trained on paired shapes from the source and target domains, but without relying on point-to-point correspondences between the source and target point sets. The training loss combines two uni-directional geometric losses, each enforcing a shape-wise similarity between the predicted and the target point sets, and a cross-regularization term to encourage consistency between displacement vectors going in opposite directions. We develop and present several different applications enabled by our general-purpose bidirectional P2P-NET to highlight the effectiveness, versatility, and potential of our network in solving a variety of point-based shape transformation problems.

##### Abstract (translated by Google)
我们引入了P2P-NET，一种通用的深度神经网络，它学习了两个领域的基于点的形状表示之间的几何变换，例如中观骨架和表面，部分和完整扫描等.P2P-NET的体系结构是通过应用从数据中学习的逐点位移矢量，双向点位移网络的转换点将一个源点集合转换为具有相同基数的目标点集合，反之亦然。 P2P-NET训练来自源域和目标域的成对形状，但不依赖源点集与目标点集之间的点对点对应关系。训练损失结合了两个单向几何损失，每个损失强化了预测点集和目标点集之间的形状相似性，以及一个交叉正则化项，以促进位移矢量沿相反方向行进的一致性。我们开发并展示了我们的通用双向P2P-NET支持的多种不同应用，以突出我们的网络在解决各种基于点的形状转换问题方面的有效性，多功能性和潜力。

##### URL
[https://arxiv.org/abs/1803.09263](https://arxiv.org/abs/1803.09263)

##### PDF
[https://arxiv.org/pdf/1803.09263](https://arxiv.org/pdf/1803.09263)

