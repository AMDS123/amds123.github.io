---
layout: post
title: "Leveraging Motion Priors in Videos for Improving Human Segmentation"
date: 2018-07-30 16:52:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Reinforcement_Learning Semantic_Segmentation
author: Yu-Ting Chen, Wen-Yen Chang, Hai-Lun Lu, Tingfan Wu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Despite many advances in deep-learning based semantic segmentation, performance drop due to distribution mismatch is often encountered in the real world. Recently, a few domain adaptation and active learning approaches have been proposed to mitigate the performance drop. However, very little attention has been made toward leveraging information in videos which are naturally captured in most camera systems. In this work, we propose to leverage "motion prior" in videos for improving human segmentation in a weakly-supervised active learning setting. By extracting motion information using optical flow in videos, we can extract candidate foreground motion segments (referred to as motion prior) potentially corresponding to human segments. We propose to learn a memory-network-based policy model to select strong candidate segments (referred to as strong motion prior) through reinforcement learning. The selected segments have high precision and are directly used to finetune the model. In a newly collected surveillance camera dataset and a publicly available UrbanStreet dataset, our proposed method improves the performance of human segmentation across multiple scenes and modalities (i.e., RGB to Infrared (IR)). Last but not least, our method is empirically complementary to existing domain adaptation approaches such that additional performance gain is achieved by combining our weakly-supervised active learning approach with domain adaptation approaches.

##### Abstract (translated by Google)
尽管基于深度学习的语义分割有许多进步，但由于分布不匹配导致的性能下降经常在现实世界中遇到。最近，已经提出了一些域适应和主动学习方法来减轻性能下降。然而，很少关注利用在大多数相机系统中自然捕获的视频中的信息。在这项工作中，我们建议利用视频中的“运动先验”来改善弱监督主动学习环境中的人体分割。通过使用视频中的光流提取运动信息，我们可以提取可能对应于人类片段的候选前景运动片段（称为运动事件）。我们建议学习基于记忆网络的策略模型，通过强化学习选择强候选段（称为强运动先验）。选定的段具有高精度，可直接用于微调模型。在新收集的监视摄像机数据集和公开可用的UrbanStreet数据集中，我们提出的方法改进了跨多个场景和模态（即RGB到红外（IR））的人体分割的性能。最后但并非最不重要的是，我们的方法在经验上与现有的域自适应方法互补，从而通过将我们的弱监督主动学习方法与域自适应方法相结合来实现额外的性能增益。

##### URL
[http://arxiv.org/abs/1807.11436](http://arxiv.org/abs/1807.11436)

##### PDF
[http://arxiv.org/pdf/1807.11436](http://arxiv.org/pdf/1807.11436)

