---
layout: post
title: "Deep Joint Rain Detection and Removal from a Single Image"
date: 2017-03-13 01:49:36
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Wenhan Yang, Robby T. Tan, Jiashi Feng, Jiaying Liu, Zongming Guo, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address a rain removal problem from a single image, even in the presence of heavy rain and rain streak accumulation. Our core ideas lie in the new rain image models and a novel deep learning architecture. We first modify an existing model comprising a rain streak layer and a background layer, by adding a binary map that locates rain streak regions. Second, we create a new model consisting of a component representing rain streak accumulation (where individual streaks cannot be seen, and thus visually similar to mist or fog), and another component representing various shapes and directions of overlapping rain streaks, which usually happen in heavy rain. Based on the first model, we develop a multi-task deep learning architecture that learns the binary rain streak map, the appearance of rain streaks, and the clean background, which is our ultimate output. The additional binary map is critically beneficial, since its loss function can provide additional strong information to the network. To handle rain streak accumulation (again, a phenomenon visually similar to mist or fog) and various shapes and directions of overlapping rain streaks, we propose a recurrent rain detection and removal network that removes rain streaks and clears up the rain accumulation iteratively and progressively. In each recurrence of our method, a new contextualized dilated network is developed to exploit regional contextual information and outputs better representation for rain detection. The evaluation on real images, particularly on heavy rain, shows the effectiveness of our novel models and architecture, outperforming the state-of-the-art methods significantly. Our codes and data sets will be publicly available.

##### Abstract (translated by Google)
在本文中，我们从单一的图像中解决了一个雨水清除问题，即使在大雨和雨水积累的情况下。我们的核心思想在于新的雨象模型和新颖的深度学习架构。我们首先通过添加一个定位雨带区域的二进制地图来修改包含雨纹层和背景层的现有模型。其次，我们创建了一个新的模型，这个模型由一个代表雨线积累的组成部分组成（其中单独的条纹不能被看到，因此在视觉上类似于雾或雾），另一个组成部分代表了不同形状和方向的重叠雨纹，这通常发生在倾盆大雨。在第一个模型的基础上，我们开发了一个多任务的深度学习架构，学习二元雨情图，雨痕的出现和干净的背景，这是我们最终的输出。附加的二进制映射是非常有益的，因为它的损失函数可以为网络提供额外的强大信息。为了处理雨水积聚（又一个雾气和雾的现象）和各种形状和方向的重叠雨纹，我们提出了一个反复的雨水检测和清除网络，可以反复地逐步清除雨水的积聚和清除积雨。在我们的方法每次重复发展，一个新的情境化扩张网络开发利用区域的情景信息，并输出更好的代表雨检测。对真实图像，特别是暴雨的评估显示了我们的新模型和架构的有效性，显着地超越了最先进的方法。我们的代码和数据集将公开发布。

##### URL
[https://arxiv.org/abs/1609.07769](https://arxiv.org/abs/1609.07769)

##### PDF
[https://arxiv.org/pdf/1609.07769](https://arxiv.org/pdf/1609.07769)

