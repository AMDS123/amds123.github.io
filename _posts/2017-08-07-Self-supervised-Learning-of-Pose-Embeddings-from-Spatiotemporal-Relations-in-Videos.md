---
layout: post
title: "Self-supervised Learning of Pose Embeddings from Spatiotemporal Relations in Videos"
date: 2017-08-07 15:57:32
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Embedding CNN Quantitative Relation
author: Ömer Sümer, Tobias Dencker, Björn Ommer
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose analysis is presently dominated by deep convolutional networks trained with extensive manual annotations of joint locations and beyond. To avoid the need for expensive labeling, we exploit spatiotemporal relations in training videos for self-supervised learning of pose embeddings. The key idea is to combine temporal ordering and spatial placement estimation as auxiliary tasks for learning pose similarities in a Siamese convolutional network. Since the self-supervised sampling of both tasks from natural videos can result in ambiguous and incorrect training labels, our method employs a curriculum learning idea that starts training with the most reliable data samples and gradually increases the difficulty. To further refine the training process we mine repetitive poses in individual videos which provide reliable labels while removing inconsistencies. Our pose embeddings capture visual characteristics of human pose that can boost existing supervised representations in human pose estimation and retrieval. We report quantitative and qualitative results on these tasks in Olympic Sports, Leeds Pose Sports and MPII Human Pose datasets.

##### Abstract (translated by Google)
人体姿态分析目前主要是深层卷积网络，训练时需要大量的联合位置和更多的手动注释。为了避免昂贵的标签的需要，我们利用训练视频中的时空关系进行姿势嵌入的自我监督学习。关键的思想是将时间排序和空间布局估计结合起来，作为学习连体卷积网络中相似性的辅助任务。由于对自然视频的两个任务进行自我监督抽样会导致模糊和不正确的训练标签，我们的方法采用课程学习的思想，开始训练最可靠的数据样本，并逐渐增加难度。为了进一步细化训练过程，我们在单个视频中挖掘重复的姿势，这些视频提供可靠的标签，同时消除不一致。我们的姿态嵌入捕捉人类姿态的视觉特征，可以提升现有的监督表示在人体姿态估计和检索。我们在奥林匹克运动，利兹体育运动和MPII人体姿态数据集上报告这些任务的定量和定性结果。

##### URL
[https://arxiv.org/abs/1708.02179](https://arxiv.org/abs/1708.02179)

##### PDF
[https://arxiv.org/pdf/1708.02179](https://arxiv.org/pdf/1708.02179)

