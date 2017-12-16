---
layout: post
title: "Let Features Decide for Themselves: Feature Mask Network for Person Re-identification"
date: 2017-11-20 05:44:29
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Optimization Classification Detection
author: Guodong Ding, Salman Khan, Zhenmin Tang, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification aims at establishing the identity of a pedestrian from a gallery that contains images of multiple people obtained from a multi-camera system. Many challenges such as occlusions, drastic lighting and pose variations across the camera views, indiscriminate visual appearances, cluttered backgrounds, imperfect detections, motion blur, and noise make this task highly challenging. While most approaches focus on learning features and metrics to derive better representations, we hypothesize that both local and global contextual cues are crucial for an accurate identity matching. To this end, we propose a Feature Mask Network (FMN) that takes advantage of ResNet high-level features to predict a feature map mask and then imposes it on the low-level features to dynamically reweight different object parts for a locally aware feature representation. This serves as an effective attention mechanism by allowing the network to focus on local details selectively. Given the resemblance of person re-identification with classification and retrieval tasks, we frame the network training as a multi-task objective optimization, which further improves the learned feature descriptions. We conduct experiments on Market-1501, DukeMTMC-reID and CUHK03 datasets, where the proposed approach respectively achieves significant improvements of $5.3\%$, $9.1\%$ and $10.7\%$ in mAP measure relative to the state-of-the-art.

##### Abstract (translated by Google)
人物再认定的目的在于从包含从多摄像机系统获得的多个人的图像的画廊建立行人的身份。许多挑战，如遮挡，激烈的照明和整个相机视图的姿态变化，不分青红皂白的视觉外观，混乱的背景，不完美的检测，运动模糊和噪音使这项任务极具挑战性。虽然大多数方法的重点是学习功能和指标，以获得更好的表示，我们假设本地和全球的上下文线索是准确的身份匹配的关键。为此，我们提出了利用ResNet高级特征来预测特征映射掩码的特征掩码网络（FMN），然后将其强加在低级特征上，以动态地重新加权不同对象部分以用于本地感知特征表示。这是一个有效的关注机制，允许网络有选择地关注本地细节。鉴于人员重新识别与分类和检索任务的相似性，我们将网络训练作为多任务客观优化进行架构，进一步改进了学习特征的描述。我们在Market-1501，DukeMMC-reID和CUHK03数据集上进行了实验，其中，相对于最新的方法，所提出的方法分别在mAP测量中实现了$ 5.3 \％$，$ 9.1 \％$和$ 10.7 \％$的显着改进。艺术。

##### URL
[https://arxiv.org/abs/1711.07155](https://arxiv.org/abs/1711.07155)

##### PDF
[https://arxiv.org/pdf/1711.07155](https://arxiv.org/pdf/1711.07155)

