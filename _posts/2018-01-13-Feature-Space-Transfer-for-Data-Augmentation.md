---
layout: post
title: "Feature Space Transfer for Data Augmentation"
date: 2018-01-13 01:02:28
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Recognition
author: Bo Liu, Mandar Dixit, Roland Kwitt, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of data augmentation in feature space is considered. A new architecture, denoted the FeATure TransfEr Network (FATTEN), is proposed for the modeling of feature trajectories induced by variations of object pose. This architecture exploits a parametrization of the pose manifold in terms of pose and appearance. This leads to a deep encoder/decoder network architecture, where the encoder factors into an appearance and a pose predictor. Unlike previous attempts at trajectory transfer, FATTEN can be efficiently trained end-to-end, with no need to train separate feature transfer functions. This is realized by supplying the decoder with information about a target pose and the use of a multi-task loss that penalizes category- and pose-mismatches. In result, FATTEN discourages discontinuous or non-smooth trajectories that fail to capture the structure of the pose manifold, and generalizes well on object recognition tasks involving large pose variation. Experimental results on the artificial ModelNet database show that it can successfully learn to map source features to target features of a desired pose, while preserving class identity. Most notably, by using feature space transfer for data augmentation (w.r.t. pose and depth) on SUN-RGBD objects, we demonstrate considerable performance improvements on one/few-shot object recognition in a transfer learning setup, compared to current state-of-the-art methods.

##### Abstract (translated by Google)
考虑特征空间中数据增加的问题。针对物体姿态变化引起的特征轨迹建模，提出了一种新的体系结构，称为Feature TransfEr网络（FATTEN）。该架构利用姿态和外观方面的姿态流形的参数化。这导致了深入的编码器/解码器网络架构，其中编码器将因素考虑到外观和姿态预测器中。与以前的弹道传输尝试不同，FATTEN可以高效地进行端到端的训练，不需要训练单独的特征传递函数。这通过向解码器提供关于目标姿态的信息和使用处理类别和姿态不匹配的多任务丢失来实现。结果，FATTEN阻止了不能捕获姿态流形结构的不连续或不平滑的轨迹，并在涉及大姿态变化的物体识别任务上得到了很好的推广。在人工ModelNet数据库的实验结果表明，它可以成功地学习映射源特征，以期望姿态的目标特征，同时保持类的身份。最值得注意的是，通过在SUN-RGBD对象上使用特征空间传输来进行数据增强（包括姿态和深度），与目前的状态相比，我们证明在传输学习设置中一个/几个物体识别具有显着的性能改进-art方法。

##### URL
[https://arxiv.org/abs/1801.04356](https://arxiv.org/abs/1801.04356)

##### PDF
[https://arxiv.org/pdf/1801.04356](https://arxiv.org/pdf/1801.04356)

