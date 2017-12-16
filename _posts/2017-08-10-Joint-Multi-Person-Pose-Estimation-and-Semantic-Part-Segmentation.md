---
layout: post
title: "Joint Multi-Person Pose Estimation and Semantic Part Segmentation"
date: 2017-08-10 20:59:31
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Pose_Estimation CNN Inference Detection
author: Fangting Xia, Peng Wang, Xianjie Chen, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose estimation and semantic part segmentation are two complementary tasks in computer vision. In this paper, we propose to solve the two tasks jointly for natural multi-person images, in which the estimated pose provides object-level shape prior to regularize part segments while the part-level segments constrain the variation of pose locations. Specifically, we first train two fully convolutional neural networks (FCNs), namely Pose FCN and Part FCN, to provide initial estimation of pose joint potential and semantic part potential. Then, to refine pose joint location, the two types of potentials are fused with a fully-connected conditional random field (FCRF), where a novel segment-joint smoothness term is used to encourage semantic and spatial consistency between parts and joints. To refine part segments, the refined pose and the original part potential are integrated through a Part FCN, where the skeleton feature from pose serves as additional regularization cues for part segments. Finally, to reduce the complexity of the FCRF, we induce human detection boxes and infer the graph inside each box, making the inference forty times faster. Since there's no dataset that contains both part segments and pose labels, we extend the PASCAL VOC part dataset with human pose joints and perform extensive experiments to compare our method against several most recent strategies. We show that on this dataset our algorithm surpasses competing methods by a large margin in both tasks.

##### Abstract (translated by Google)
人体姿态估计和语义部分分割是计算机视觉中的两个互补任务。在本文中，我们提出联合求解自然多人图像的两个任务，其中估计的姿态在部分区段正规化之前提供对象级的形状，而部分级的区段约束姿态位置的变化。具体来说，我们首先训练两个完全卷积神经网络（FCN），即姿态FCN和部分FCN，以提供姿势联合势和语义部分势的初始估计。然后，为了优化姿态关节的位置，将两种势能与全连接的条件随机场（FCRF）进行融合，使用新颖的节段关节平滑项来激励零件和关节之间的语义和空间一致性。为了精炼零件段，通过零件FCN将精制姿态和原始零件位势集成，其中姿态的骨架特征用作零件段的附加正则化提示。最后，为了减少FCRF的复杂性，我们引入人类检测框并推断每个框内的图形，使得推理快四十倍。由于没有包含零件段和姿态标签的数据集，因此我们用人体姿势关节来扩展PASCAL VOC零件数据集，并进行大量的实验来比较我们的方法和最近的几种策略。我们表明，在这个数据集中，我们的算法在两个任务中都大大优于竞争方法。

##### URL
[https://arxiv.org/abs/1708.03383](https://arxiv.org/abs/1708.03383)

##### PDF
[https://arxiv.org/pdf/1708.03383](https://arxiv.org/pdf/1708.03383)

