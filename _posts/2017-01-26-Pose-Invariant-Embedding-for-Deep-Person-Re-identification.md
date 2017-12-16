---
layout: post
title: "Pose Invariant Embedding for Deep Person Re-identification"
date: 2017-01-26 14:59:19
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Pose_Estimation Person_Re-identification Embedding Detection
author: Liang Zheng, Yujia Huang, Huchuan Lu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Pedestrian misalignment, which mainly arises from detector errors and pose variations, is a critical problem for a robust person re-identification (re-ID) system. With bad alignment, the background noise will significantly compromise the feature learning and matching process. To address this problem, this paper introduces the pose invariant embedding (PIE) as a pedestrian descriptor. First, in order to align pedestrians to a standard pose, the PoseBox structure is introduced, which is generated through pose estimation followed by affine transformations. Second, to reduce the impact of pose estimation errors and information loss during PoseBox construction, we design a PoseBox fusion (PBF) CNN architecture that takes the original image, the PoseBox, and the pose estimation confidence as input. The proposed PIE descriptor is thus defined as the fully connected layer of the PBF network for the retrieval task. Experiments are conducted on the Market-1501, CUHK03, and VIPeR datasets. We show that PoseBox alone yields decent re-ID accuracy and that when integrated in the PBF network, the learned PIE descriptor produces competitive performance compared with the state-of-the-art approaches.

##### Abstract (translated by Google)
主要由检测器误差和姿态变化引起的行人不对准是健壮人重新识别（re-ID）系统的关键问题。如果对齐性不好，背景噪声会严重影响特征学习和匹配过程。为解决这个问题，本文将姿态不变嵌入（PIE）作为步行描述符。首先，为了使行人符合标准姿势，引入PoseBox结构，其通过姿态估计和仿射变换生成。其次，为了减少PoseBox构造过程中姿态估计误差和信息丢失的影响，设计了一个PoseBox融合（PBF）CNN架构，将原始图像，姿态框和姿态估计置信度作为输入。所提出的PIE描述符因此被定义为用于检索任务的PBF网络的完全连接层。在Market-1501，CUHK03和VIPeR数据集上进行实验。我们展示了单独的PoseBox产生不错的重新ID准确性，并且当集成在PBF网络中时，学习的PIE描述符产生与最先进的方法相比的竞争性表现。

##### URL
[https://arxiv.org/abs/1701.07732](https://arxiv.org/abs/1701.07732)

##### PDF
[https://arxiv.org/pdf/1701.07732](https://arxiv.org/pdf/1701.07732)

