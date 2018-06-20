---
layout: post
title: "MoE-SPNet: A Mixture-of-Experts Scene Parsing Network"
date: 2018-06-19 05:32:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Huan Fu, Mingming Gong, Chaohui Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Scene parsing is an indispensable component in understanding the semantics within a scene. Traditional methods rely on handcrafted local features and probabilistic graphical models to incorporate local and global cues. Recently, methods based on fully convolutional neural networks have achieved new records on scene parsing. An important strategy common to these methods is the aggregation of hierarchical features yielded by a deep convolutional neural network. However, typical algorithms usually aggregate hierarchical convolutional features via concatenation or linear combination, which cannot sufficiently exploit the diversities of contextual information in multi-scale features and the spatial inhomogeneity of a scene. In this paper, we propose a mixture-of-experts scene parsing network (MoE-SPNet) that incorporates a convolutional mixture-of-experts layer to assess the importance of features from different levels and at different spatial locations. In addition, we propose a variant of mixture-of-experts called the adaptive hierarchical feature aggregation (AHFA) mechanism which can be incorporated into existing scene parsing networks that use skip-connections to fuse features layer-wisely. In the proposed networks, different levels of features at each spatial location are adaptively re-weighted according to the local structure and surrounding contextual information before aggregation. We demonstrate the effectiveness of the proposed methods on two scene parsing datasets including PASCAL VOC 2012 and SceneParse150 based on two kinds of baseline models FCN-8s and DeepLab-ASPP.

##### Abstract (translated by Google)
场景解析是理解场景内语义的不可缺少的组成部分。传统的方法依靠手工制作的局部特征和概率图形模型来结合局部和全局线索。最近，基于完全卷积神经网络的方法在场景解析上取得了新的记录。这些方法共同的一个重要策略是由深卷积神经网络产生的分层特征的聚合。然而，典型的算法通常通过拼接或线性组合来聚合分层卷积特征，不能充分利用多尺度特征中情境信息的多样性和场景的空间不均匀性。在本文中，我们提出了一个混合专家场景解析网络（MoE-SPNet），该网络融合了卷积混合专家层来评估不同层次和不同空间位置的特征的重要性。另外，我们提出了一种被称为自适应分层特征聚合（AHFA）机制的专家混合体的变体，其可以结合到现有场景分析网络中，其使用跳跃连​​接来明确地融合特征。在提出的网络中，每个空间位置的不同层次的特征根据聚合前的局部结构和周围的上下文信息进行自适应重新加权。我们基于两种基准模型FCN-8和DeepLab-ASPP，演示了两种场景解析数据集（包括PASCAL VOC 2012和SceneParse150）上提议方法的有效性。

##### URL
[http://arxiv.org/abs/1806.07049](http://arxiv.org/abs/1806.07049)

##### PDF
[http://arxiv.org/pdf/1806.07049](http://arxiv.org/pdf/1806.07049)

