---
layout: post
title: "Action Recognition Based on Joint Trajectory Maps with Convolutional Neural Networks"
date: 2016-12-30 06:32:38
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Classification Recognition
author: Pichao Wang, Wanqing Li, Chuankun Li, Yonghong Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (ConvNets) have recently shown promising performance in many computer vision tasks, especially image-based recognition. How to effectively apply ConvNets to sequence-based data is still an open problem. This paper proposes an effective yet simple method to represent spatio-temporal information carried in $3D$ skeleton sequences into three $2D$ images by encoding the joint trajectories and their dynamics into color distribution in the images, referred to as Joint Trajectory Maps (JTM), and adopts ConvNets to learn the discriminative features for human action recognition. Such an image-based representation enables us to fine-tune existing ConvNets models for the classification of skeleton sequences without training the networks afresh. The three JTMs are generated in three orthogonal planes and provide complimentary information to each other. The final recognition is further improved through multiply score fusion of the three JTMs. The proposed method was evaluated on four public benchmark datasets, the large NTU RGB+D Dataset, MSRC-12 Kinect Gesture Dataset (MSRC-12), G3D Dataset and UTD Multimodal Human Action Dataset (UTD-MHAD) and achieved the state-of-the-art results.

##### Abstract (translated by Google)
卷积神经网络（ConvNets）最近在许多计算机视觉任务中表现出有希望的性能，特别是基于图像的识别。如何有效地将ConvNets应用于基于序列的数据仍然是一个悬而未决的问题。本文提出了一种有效而简单的方法，通过将联合轨迹及其动力学编码成图像中的颜色分布，将$ 3D $骨架序列中携带的时空信息表示为三个$ 2D $图像，称为联合轨迹图（Joint Trajectory Maps，JTM ），并采用ConvNets来学习人类行为识别的判别特征。这种基于图像的表示使我们能够对现有的ConvNet模型进行微调，以对骨架序列进行分类，而无需重新训练网络。三个JTM在三个正交平面上生成，互相提供互相补充的信息。通过三个JTMs的乘法分数融合进一步改善了最终的认识。在NTU RGB + D数据集，MSRC-12 Kinect手势数据集（MSRC-12），G3D数据集和UTD多模态人类行为数据集（UTD-MHAD）四个公共基准数据集上进行评估，最先进的结果。

##### URL
[https://arxiv.org/abs/1612.09401](https://arxiv.org/abs/1612.09401)

##### PDF
[https://arxiv.org/pdf/1612.09401](https://arxiv.org/pdf/1612.09401)

