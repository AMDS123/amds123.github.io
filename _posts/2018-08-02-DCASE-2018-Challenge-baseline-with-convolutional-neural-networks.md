---
layout: post
title: "DCASE 2018 Challenge baseline with convolutional neural networks"
date: 2018-08-02 12:03:09
categories: arXiv_SD
tags: arXiv_SD CNN Classification Detection
author: Qiuqiang Kong, Turab Iqbal, Yong Xu, Wenwu Wang, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
The Detection and Classification of Acoustic Scenes and Events (DCASE) is a well-known IEEE AASP challenge consisting of a number of audio classification and sound event detection tasks. DCASE 2018 has five tasks: 1) Acoustic scene classification, 2) General-purpose audio tagging, 3) Bird audio detection, 4) Weakly-labeled semi-supervised sound event detection and 5) Multi-channel audio tagging. In this paper, we describe our Python implementation of all of these tasks, which we have released under an open-source license. The baseline source code contains the implementation of convolutional neural networks (CNNs), including AlexNetish and VGGish -- networks originating from computer vision. We researched how the performance varies from task to task with the same configuration of neural networks. Experiments show that the deeper VGGish network performs better than AlexNetish on all tasks except Task 1, where VGGish and AlexNetish perform similarly. With the VGGish network, we achieve an accuracy of 0.680 on Task 1, a mean average precision (mAP) of 0.928 on Task 2, an area under the curve (AUC) of 0.854 on Task 3, a sound event detection F1 score of 20.8\% on Task 4 and an F1 score of 87.75\% on Task 5.

##### Abstract (translated by Google)
声学场景和事件的检测和分类（DCASE）是众所周知的IEEE AASP挑战，其由许多音频分类和声音事件检测任务组成。 DCASE 2018有五个任务：1）声学场景分类，2）通用音频标签，3）鸟类音频检测，4）弱标记的半监督声音事件检测和5）多声道音频标记。在本文中，我们描述了我们在开源许可下发布的所有这些任务的Python实现。基线源代码包含卷积神经网络（CNN）的实现，包括AlexNetish和VGGish  - 源自计算机视觉的网络。我们研究了使用相同的神经网络配置，性能如何随任务而变化。实验表明，除了任务1之外，更深层次的VGGish网络在所有任务上的表现都优于AlexNetish，其中VGGish和AlexNetish的表现相似。使用VGGish网络，我们在任务1上获得0.680的准确度，任务2的平均精度（mAP）为0.928，任务3的曲线下面积（AUC）为0.854，声音事件检测F1得分为20.8任务4上的\％和任务5上的F1得分为87.75 \％。

##### URL
[http://arxiv.org/abs/1808.00773](http://arxiv.org/abs/1808.00773)

##### PDF
[http://arxiv.org/pdf/1808.00773](http://arxiv.org/pdf/1808.00773)

