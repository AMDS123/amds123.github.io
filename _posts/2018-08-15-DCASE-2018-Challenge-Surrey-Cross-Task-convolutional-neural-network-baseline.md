---
layout: post
title: "DCASE 2018 Challenge Surrey Cross-Task convolutional neural network baseline"
date: 2018-08-15 18:41:33
categories: arXiv_SD
tags: arXiv_SD CNN Classification Detection
author: Qiuqiang Kong, Turab Iqbal, Yong Xu, Wenwu Wang, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
The Detection and Classification of Acoustic Scenes and Events (DCASE) consists of five audio classification and sound event detection tasks: 1) Acoustic scene classification, 2) General-purpose audio tagging of Freesound, 3) Bird audio detection, 4) Weakly-labeled semi-supervised sound event detection and 5) Multi-channel audio classification. In this paper, we create a cross-task baseline system for all five tasks based on a convlutional neural network (CNN): a `CNN Baseline' system. We implemented CNNs with 4 layers and 8 layers originating from AlexNet and VGG from computer vision. We investigated how the performance varies from task to task with the same configuration of neural networks. Experiments show that deeper CNN with 8 layers performs better than CNN with 4 layers on all tasks except Task 1. Using CNN with 8 layers, we achieve an accuracy of 0.680 on Task 1, an accuracy of 0.895 and a mean average precision (MAP) of 0.928 on Task 2, an accuracy of 0.751 and an area under the curve (AUC) of 0.854 on Task 3, a sound event detection F1 score of 20.8\% on Task 4, and an F1 score of 87.75\% on Task 5. We released the Python source code of the baseline systems under the MIT liscense for further research.

##### Abstract (translated by Google)
声学场景和事件的检测和分类（DCASE）包括五个音频分类和声音事件检测任务：1）声学场景分类，2）Freesound的通用音频标记，3）鸟类音频检测，4）弱标记半监督声音事件检测和5）多声道音频分类。在本文中，我们基于卷积神经网络（CNN）创建了一个针对所有五个任务的跨任务基线系统：一个“CNN基线”系统。我们通过计算机视觉实现了来自AlexNet和VGG的4层和8层CNN。我们研究了使用相同的神经网络配置，性能如何随任务而变化。实验表明，除了任务1以外，8层更深的CNN表现优于CNN，4层，除了任务1，使用8层CNN，任务1的精度达到0.680，精度为0.895，平均精度（MAP）任务2上的0.928，准确度为0.751，任务3的曲线下面积（AUC）为0.854，任务4的声音事件检测F1得分为20.8 \％，任务5的得分为87.75 \％我们在MIT liscense下发布了基线系统的Python源代码，供进一步研究。

##### URL
[http://arxiv.org/abs/1808.00773](http://arxiv.org/abs/1808.00773)

##### PDF
[http://arxiv.org/pdf/1808.00773](http://arxiv.org/pdf/1808.00773)

