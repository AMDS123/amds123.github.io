---
layout: post
title: "Seeing the Wood for the Trees: Reliable Localization in Urban and Natural Environments"
date: 2018-09-08 17:58:32
categories: arXiv_RO
tags: arXiv_RO Segmentation Quantitative Recognition
author: Georgi Tinchev, Simona Nobili, Maurice Fallon
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce Natural Segmentation and Matching (NSM), an algorithm for reliable localization, using laser, in both urban and natural environments. Current state-of-the-art global approaches do not generalize well to structure-poor vegetated areas such as forests or orchards. In these environments clutter and perceptual aliasing prevents repeatable extraction of distinctive landmarks between different test runs. In natural forests, tree trunks are not distinctive, foliage intertwines and there is a complete lack of planar structure. In this paper we propose a method for place recognition which uses a more involved feature extraction process which is better suited to this type of environment. First, a feature extraction module segments stable and reliable object-sized segments from a point cloud despite the presence of heavy clutter or tree foliage. Second, repeatable oriented key poses are extracted and matched with a reliable shape descriptor using a Random Forest to estimate the current sensor's position within the target map. We present qualitative and quantitative evaluation on three datasets from different environments - the KITTI benchmark, a parkland scene and a foliage-heavy forest. The experiments show how our approach can achieve place recognition in woodlands while also outperforming current state-of-the-art approaches in urban scenarios without specific tuning.

##### Abstract (translated by Google)
在这项工作中，我们介绍了自然分割和匹配（NSM），这是一种在城市和自然环境中使用激光进行可靠定位的算法。目前最先进的全球方法并不能很好地概括为结构贫乏的植被区域，如森林或果园。在这些环境中，杂乱和感知混叠阻止了在不同测试运行之间可重复地提取独特的界标。在天然林中，树干并不是独特的，树叶交织在一起，完全缺乏平面结构。在本文中，我们提出了一种地点识别方法，它使用更复杂的特征提取过程，更适合这种类型的环境。首先，特征提取模块从点云中分割稳定且可靠的物体大小的片段，尽管存在沉重的杂波或树叶。其次，使用随机森林提取可重复定向的关键姿势并与可靠的形状描述符匹配，以估计当前传感器在目标地图内的位置。我们对来自不同环境的三个数据集进行定性和定量评估--KITTI基准测试，公园场景和树叶茂密的森林。实验表明，我们的方法如何在林地中实现位置识别，同时在没有特定调整的情况下也优于当前最先进的城市场景方法。

##### URL
[http://arxiv.org/abs/1809.02846](http://arxiv.org/abs/1809.02846)

##### PDF
[http://arxiv.org/pdf/1809.02846](http://arxiv.org/pdf/1809.02846)

