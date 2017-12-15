---
layout: post
title: "Dynamic Pose-Robust Facial Expression Recognition by Multi-View Pairwise Conditional Random Forests"
date: 2016-07-21 10:07:33
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Classification Prediction Recognition
author: Arnaud Dapogny, Kévin Bailly, Séverine Dubuisson
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic facial expression classification (FER) from videos is a critical problem for the development of intelligent human-computer interaction systems. Still, it is a challenging problem that involves capturing high-dimensional spatio-temporal patterns describing the variation of one's appearance over time. Such representation undergoes great variability of the facial morphology and environmental factors as well as head pose variations. In this paper, we use Conditional Random Forests to capture low-level expression transition patterns. More specifically, heterogeneous derivative features (e.g. feature point movements or texture variations) are evaluated upon pairs of images. When testing on a video frame, pairs are created between this current frame and previous ones and predictions for each previous frame are used to draw trees from Pairwise Conditional Random Forests (PCRF) whose pairwise outputs are averaged over time to produce robust estimates. Moreover, PCRF collections can also be conditioned on head pose estimation for multi-view dynamic FER. As such, our approach appears as a natural extension of Random Forests for learning spatio-temporal patterns, potentially from multiple viewpoints. Experiments on popular datasets show that our method leads to significant improvements over standard Random Forests as well as state-of-the-art approaches on several scenarios, including a novel multi-view video corpus generated from a publicly available database.

##### Abstract (translated by Google)
视频中的自动表情分类（FER）是智能人机交互系统发展的关键问题。然而，这是一个具有挑战性的问题，涉及捕捉描述随着时间的推移而出现的外观变化的高维空间 - 时间模式。这种表现经历了面部形态和环境因素以及头部姿态变化的巨大变化。在本文中，我们使用条件随机森林来捕获低级表达式转换模式。更具体地说，在成对图像上评估异质派生特征（例如特征点移动或纹理变化）。当在视频帧上测试时，在当前帧和前一帧之间创建对，并且使用每个先前帧的预测来绘制成对有条件随机森林（PCRF），其成对输出随时间平均以产生鲁棒估计。此外，PCRF集合还可以以多视角动态FER的头部姿态估计为条件。因此，我们的方法似乎是随机森林的自然延伸，用于学习时空模式，可能来自多个观点。在流行数据集上的实验表明，我们的方法在标准随机森林方面取得了显着的进步，并且在多个场景中采用了最先进的方法，包括从公开可用的数据库生成的新型多视图视频语料库。

##### URL
[https://arxiv.org/abs/1607.06250](https://arxiv.org/abs/1607.06250)

##### PDF
[https://arxiv.org/pdf/1607.06250](https://arxiv.org/pdf/1607.06250)

