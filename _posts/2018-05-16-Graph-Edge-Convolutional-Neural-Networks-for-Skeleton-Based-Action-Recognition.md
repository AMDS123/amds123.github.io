---
layout: post
title: "Graph Edge Convolutional Neural Networks for Skeleton Based Action Recognition"
date: 2018-05-16 08:18:33
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Action_Recognition CNN Recognition
author: Xikun Zhang, Chang Xu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates body bones from skeleton data for skeleton based action recognition. Body joints, as the direct result of mature pose estimation technologies, are always the key concerns of traditional action recognition methods. However, instead of joints, we humans naturally identify how the human body moves according to shapes, lengths and places of bones, which are more obvious and stable for observation. Hence given graphs generated from skeleton data, we propose to develop convolutions over graph edges that correspond to bones in human skeleton. We describe an edge by integrating its spatial neighboring edges to explore the cooperation between different bones, as well as its temporal neighboring edges to address the consistency of movements in an action. A graph edge convolutional neural network is then designed for skeleton based action recognition. Considering the complementarity between graph node convolution and graph edge convolution, we additionally construct two hybrid neural networks to combine graph node convolutional neural network and graph edge convolutional neural network using shared intermediate layers. Experimental results on Kinetics and NTU-RGB+D datasets demonstrate that our graph edge convolution is effective to capture characteristic of actions and our graph edge convolutional neural network significantly outperforms existing state-of-art skeleton based action recognition methods. Additionally, more performance improvements can be achieved by the hybrid networks.

##### Abstract (translated by Google)
本文从基于骨架动作识别的骨架数据研究人体骨骼。作为成熟姿态估计技术的直接结果，身体关节一直是传统动作识别方法的关键问题。然而，我们人类根据骨骼的形状，长度和位置自然地识别人体如何移动，而不是关节，这些对于观察来说更加明显和稳定。因此，给定从骨架数据生成的图形，我们建议在图形边缘上开发与人体骨骼中的骨骼相对应的卷积。我们通过整合其空间相邻边缘来描述边缘，以探索不同骨骼之间的合作以及其时间相邻边缘，以解决动作中运动的一致性。然后设计图边缘卷积神经网络用于基于骨架的动作识别。考虑到图形节点卷积和图形边缘卷积之间的互补性，我们另外构造了两个混合神经网络，用图形节点卷积神经网络和图形边缘卷积神经网络共享中间层。在动力学和NTU-RGB + D数据集上的实验结果表明，我们的图边缘卷积有效捕获动作的特征，我们的图边缘卷积神经网络明显优于现有的基于先进骨架的动作识别方法。另外，混合网络可以实现更多的性能改进。

##### URL
[http://arxiv.org/abs/1805.06184](http://arxiv.org/abs/1805.06184)

##### PDF
[http://arxiv.org/pdf/1805.06184](http://arxiv.org/pdf/1805.06184)

