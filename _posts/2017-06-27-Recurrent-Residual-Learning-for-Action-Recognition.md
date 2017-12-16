---
layout: post
title: "Recurrent Residual Learning for Action Recognition"
date: 2017-06-27 12:08:14
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Image_Classification Inference Classification Recognition
author: Ahsan Iqbal, Alexander Richard, Hilde Kuehne, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
Action recognition is a fundamental problem in computer vision with a lot of potential applications such as video surveillance, human computer interaction, and robot learning. Given pre-segmented videos, the task is to recognize actions happening within videos. Historically, hand crafted video features were used to address the task of action recognition. With the success of Deep ConvNets as an image analysis method, a lot of extensions of standard ConvNets were purposed to process variable length video data. In this work, we propose a novel recurrent ConvNet architecture called recurrent residual networks to address the task of action recognition. The approach extends ResNet, a state of the art model for image classification. While the original formulation of ResNet aims at learning spatial residuals in its layers, we extend the approach by introducing recurrent connections that allow to learn a spatio-temporal residual. In contrast to fully recurrent networks, our temporal connections only allow a limited range of preceding frames to contribute to the output for the current frame, enabling efficient training and inference as well as limiting the temporal context to a reasonable local range around each frame. On a large-scale action recognition dataset, we show that our model improves over both, the standard ResNet architecture and a ResNet extended by a fully recurrent layer.

##### Abstract (translated by Google)
动作识别是计算机视觉中的一个基本问题，具有很多潜在的应用，如视频监控，人机交互和机器人学习。鉴于预先分段的视频，其任务是识别视频中发生的行为。历史上，手工制作的视频功能被用来解决行动识别的任务。随着Deep ConvNet作为一种图像分析方法的成功，标准ConvNet的许多扩展用于处理可变长度的视频数据。在这项工作中，我们提出了一种新的经常性的ConvNet架构，称为经常性残差网络来解决行动识别的任务。该方法扩展了ResNet，这是一种最先进的图像分类模型。虽然ResNet的原始公式旨在学习其层中的空间残差，但我们通过引入允许学习时空残差的经常性连接来扩展该方法。与完全经常性的网络相反，我们的时间连接只允许有限范围的前一帧对当前帧的输出作出贡献，从而实现有效的训练和推断，并将时间上下文限制在每个帧周围的合理局部范围内。在一个大规模动作识别数据集上，我们展示了我们的模型同时改进了标准ResNet架构和ResNet扩展的ResNet。

##### URL
[https://arxiv.org/abs/1706.08807](https://arxiv.org/abs/1706.08807)

##### PDF
[https://arxiv.org/pdf/1706.08807](https://arxiv.org/pdf/1706.08807)

