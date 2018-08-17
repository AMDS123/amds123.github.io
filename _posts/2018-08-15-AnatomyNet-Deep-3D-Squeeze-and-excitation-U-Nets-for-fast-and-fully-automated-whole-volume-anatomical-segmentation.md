---
layout: post
title: "AnatomyNet: Deep 3D Squeeze-and-excitation U-Nets for fast and fully automated whole-volume anatomical segmentation"
date: 2018-08-15 18:03:12
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Wentao Zhu, Yufang Huang, Hui Tang, Zhen Qian, Nan Du, Wei Fan, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Radiation therapy (RT) is a common treatment for head and neck (HaN) cancer where therapists are often required to manually delineate boundaries of the organs-at-risks (OARs). Automated head and neck anatomical segmentation provides a way to speed up and improve the reproducibility of radiation therapy planning. In this work, we propose the AnatomyNet, an end-to-end and atlas-free three dimensional squeeze-and-excitation U-Net (3D SE U-Net), for fast and fully automated whole-volume HaN anatomical segmentation. 
 There are two main challenges for fully automated HaN OARs segmentation: 1) challenge in segmenting small anatomies (i.e., optic chiasm and optic nerves) occupying only a few slices, and 2) training model with inconsistent data annotations with missing ground truth for some anatomical structures because of different RT planning. We propose the AnatomyNet that has one down-sampling layer with the trade-off between GPU memory and feature representation capacity, and 3D SE residual blocks for effective feature learning to alleviate these challenges. Moreover, we design a hybrid loss function with the Dice loss and the focal loss. The Dice loss is a class level distribution loss that depends less on the number of voxels in the anatomy, and the focal loss is designed to deal with highly unbalanced segmentation. For missing annotations, we propose masked loss and weighted loss for accurate and balanced weights updating in the learning of the AnatomyNet. 
 We collect 261 HaN CT images to train the AnatomyNet for segmenting nine anatomies. Compared to previous state-of-the-art methods for each anatomy from the MICCAI 2015 competition, the AnatomyNet increases Dice similarity coefficient (DSC) by 3.3% on average. The proposed AnatomyNet takes only 0.12 seconds on average to segment a whole-volume HaN CT image of an average dimension of 178x302x225.

##### Abstract (translated by Google)
放射疗法（RT）是头颈部（HaN）癌症的常见治疗方法，其中治疗师经常需要手动描绘风险器官（OAR）的边界。自动头部和颈部解剖分割提供了一种加速和改善放射治疗计划的再现性的方法。在这项工作中，我们提出了AnatomyNet，一种端到端和无寰椎的三维挤压和激发U-Net（3D SE U-Net），用于快速和全自动的全体积HaN解剖分割。
 完全自动化的HaN OAR分割存在两个主要挑战：1）分割小解剖结构（即，视交叉和视神经）仅占用少量切片的挑战;以及2）具有不一致的数据注释的训练模型，其中缺少一些解剖学的基础事实结构由于不同的RT规划。我们提出AnatomyNet，其具有一个下采样层，其具有GPU存储器和特征表示能力之间的折衷，以及用于有效特征学习的3D SE残余块以缓解这些挑战。此外，我们设计了具有骰子损失和焦点损失的混合损失函数。骰子损失是类级别分布损失，其较少依赖于解剖结构中的体素数量，并且焦点损失旨在处理高度不平衡的分割。对于缺失的注释，我们建议屏蔽损失和加权损失，以便在AnatomyNet的学习中更新准确和平衡的权重。
 我们收集261个HaN CT图像来训练AnatomyNet以分割九个解剖图。与MICCAI 2015竞赛中每个解剖学的先前最先进的方法相比，AnatomyNet平均增加了骰子相似系数（DSC）3.3％。拟议的AnatomyNet平均仅需0.12秒即可分割平均尺寸为178x302x225的全体积HaN CT图像。

##### URL
[http://arxiv.org/abs/1808.05238](http://arxiv.org/abs/1808.05238)

##### PDF
[http://arxiv.org/pdf/1808.05238](http://arxiv.org/pdf/1808.05238)

