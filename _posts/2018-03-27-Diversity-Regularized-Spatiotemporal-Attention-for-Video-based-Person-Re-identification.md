---
layout: post
title: "Diversity Regularized Spatiotemporal Attention for Video-based Person Re-identification"
date: 2018-03-27 03:47:53
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Attention GAN Face Person_Re-identification
author: Shuang Li, Slawomir Bak, Peter Carr, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based person re-identification matches video clips of people across non-overlapping cameras. Most existing methods tackle this problem by encoding each video frame in its entirety and computing an aggregate representation across all frames. In practice, people are often partially occluded, which can corrupt the extracted features. Instead, we propose a new spatiotemporal attention model that automatically discovers a diverse set of distinctive body parts. This allows useful information to be extracted from all frames without succumbing to occlusions and misalignments. The network learns multiple spatial attention models and employs a diversity regularization term to ensure multiple models do not discover the same body part. Features extracted from local image regions are organized by spatial attention model and are combined using temporal attention. As a result, the network learns latent representations of the face, torso and other body parts using the best available image patches from the entire video sequence. Extensive evaluations on three datasets show that our framework outperforms the state-of-the-art approaches by large margins on multiple metrics.

##### Abstract (translated by Google)
基于视频的人员重新识别与非重叠摄像机上人员的视频剪辑匹配。大多数现有方法通过对每个视频帧进行完整编码并计算跨所有帧的聚合表示来解决此问题。在实践中，人们常常部分被遮挡，这会破坏提取的特征。相反，我们提出了一种新的时空关注模型，可以自动发现多种独特的身体部位。这允许从所有帧中提取有用的信息而不会屈服于遮挡和未对齐。该网络学习多个空间关注模型并采用多样性正则化术语来确保多个模型不会发现相同的身体部分。从局部图像区域提取的特征由空间关注模型组织，并且使用时间关注进行组合。因此，网络使用整个视频序列中的最佳可用图像补丁来学习脸部，躯干和其他身体部位的潜在表示。对三个数据集的广泛评估表明，我们的框架在多个指标上大幅超越了最先进的方法。

##### URL
[https://arxiv.org/abs/1803.09882](https://arxiv.org/abs/1803.09882)

##### PDF
[https://arxiv.org/pdf/1803.09882](https://arxiv.org/pdf/1803.09882)

