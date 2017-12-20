---
layout: post
title: "GoDP: Globally optimized dual pathway system for facial landmark localization in-the-wild"
date: 2017-12-19 15:14:18
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Detection Recognition Face_Recognition
author: Yuhang Wu, Shishir K. Shah, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
Facial landmark localization is a fundamental module for pose-invariant face recognition. The most common approach for facial landmark detection is cascaded regression, which is composed of two steps: feature extraction and facial shape regression. Recent methods employ deep convolutional networks to extract robust features for each step, while the whole system could be regarded as a deep cascaded regression architecture. In this work, instead of employing a deep regression network, a Globally Optimized Dual-Pathway (GoDP) deep architecture is proposed to identify the target pixels through solving a cascaded pixel labeling problem without resorting to high-level inference models or complex stacked architecture. The proposed end-to-end system relies on distance-aware softmax functions and dual-pathway proposal-refinement architecture. Results show that it outperforms the state-of-the-art cascaded regression-based methods on multiple in-the-wild face alignment databases. The model achieves 1.84 normalized mean error (NME) on the AFLW database, which outperforms 3DDFA by 61.8%. Experiments on face identification demonstrate that GoDP, coupled with DPM-headhunter, is able to improve rank-1 identification rate by 44.2% compared to Dlib toolbox on a challenging database.

##### Abstract (translated by Google)
面部标志定位是姿态不变人脸识别的基本模块。面部标志检测最常用的方法是级联回归，它由两个步骤组成：特征提取和面部形状回归。最近的方法采用深度卷积网络来提取每个步骤的鲁棒特征，而整个系统可以被看作是深度级联的回归结构。在这项工作中，不采用高级推理模型或复杂的堆栈结构，而是采用全局优化的双通道（GoDP）深层架构，通过求解级联像素标记问题来识别目标像素，而不是采用深度回归网络。所提出的端到端系统依靠感知距离的softmax函数和双路径建议 - 细化架构。结果表明，它在多个在野人脸对齐数据库中胜过了基于最先进的级联回归的方法。该模型在AFLW数据库上达到了1.84的归一化平均误差（NME），优于3DDFA的61.8％。人脸识别实验表明，GoDP与DPM-headhunter相结合，能够在具有挑战性的数据库上将D-1识别率提高44.2％。

##### URL
[http://arxiv.org/abs/1704.02402](http://arxiv.org/abs/1704.02402)

##### PDF
[http://arxiv.org/pdf/1704.02402](http://arxiv.org/pdf/1704.02402)

