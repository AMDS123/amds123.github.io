---
layout: post
title: "Multi-Model Hypothesize-and-Verify Approach for Incremental Loop Closure Verification"
date: 2016-08-06 02:06:23
categories: arXiv_CV
tags: arXiv_CV Detection SLAM Recognition
author: Kanji Tanaka
mathjax: true
---

* content
{:toc}

##### Abstract
Loop closure detection, which is the task of identifying locations revisited by a robot in a sequence of odometry and perceptual observations, is typically formulated as a visual place recognition (VPR) task. However, even state-of-the-art VPR techniques generate a considerable number of false positives as a result of confusing visual features and perceptual aliasing. In this paper, we propose a robust incremental framework for loop closure detection, termed incremental loop closure verification. Our approach reformulates the problem of loop closure detection as an instance of a multi-model hypothesize-and-verify framework, in which multiple loop closure hypotheses are generated and verified in terms of the consistency between loop closure hypotheses and VPR constraints at multiple viewpoints along the robot's trajectory. Furthermore, we consider the general incremental setting of loop closure detection, in which the system must update both the set of VPR constraints and that of loop closure hypotheses when new constraints or hypotheses arrive during robot navigation. Experimental results using a stereo SLAM system and DCNN features and visual odometry validate effectiveness of the proposed approach.

##### Abstract (translated by Google)
环路闭合检测是识别由机器人在测距和感知观测序列中重新定位的位置的任务，典型地被制定为视觉地点识别（VPR）任务。然而，即使是最先进的VPR技术也会由于混淆视觉特征和感知别名而产生相当多的误报。在本文中，我们提出了一个强大的闭环检测增量框架，称为增量闭环检验。我们的方法将环路闭合检测问题重新定义为多模型假设和验证框架的一个实例，其中多个闭环假设被生成并且在沿着多个视点的闭环假设和VPR约束之间的一致性方面被验证机器人的轨迹。此外，我们考虑环路闭合检测的一般增量设置，在机器人导航期间，当新的约束或假设到达时，系统必须更新VPR约束集合和环路闭合假设集合。使用立体声SLAM系统和DCNN特征和视觉测距的实验结果证实了所提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1608.02052](https://arxiv.org/abs/1608.02052)

##### PDF
[https://arxiv.org/pdf/1608.02052](https://arxiv.org/pdf/1608.02052)

