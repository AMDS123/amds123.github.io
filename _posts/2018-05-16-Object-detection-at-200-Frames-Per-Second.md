---
layout: post
title: "Object detection at 200 Frames Per Second"
date: 2018-05-16 15:07:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Rakesh Mehta, Cemalettin Ozturk
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient and fast object detector which can process hundreds of frames per second. To achieve this goal we investigate three main aspects of the object detection framework: network architecture, loss function and training data (labeled and unlabeled). In order to obtain compact network architecture, we introduce various improvements, based on recent work, to develop an architecture which is computationally light-weight and achieves a reasonable performance. To further improve the performance, while keeping the complexity same, we utilize distillation loss function. Using distillation loss we transfer the knowledge of a more accurate teacher network to proposed light-weight student network. We propose various innovations to make distillation efficient for the proposed one stage detector pipeline: objectness scaled distillation loss, feature map non-maximal suppression and a single unified distillation loss function for detection. Finally, building upon the distillation loss, we explore how much can we push the performance by utilizing the unlabeled data. We train our model with unlabeled data using the soft labels of the teacher network. Our final network consists of 10x fewer parameters than the VGG based object detection network and it achieves a speed of more than 200 FPS and proposed changes improve the detection accuracy by 14 mAP over the baseline on Pascal dataset.

##### Abstract (translated by Google)
在本文中，我们提出了一种高效快速的物体检测器，可以每秒处理数百帧。为了实现这个目标，我们调查了目标检测框架的三个主要方面：网络架构，损失函数和训练数据（标记和未标记）。为了获得紧凑的网络体系结构，我们在最近的工作的基础上引入了各种改进，以开发计算轻量并且达到合理性能的体系结构。为了进一步提高性能，同时保持复杂性，我们利用蒸馏损失函数。使用蒸馏损失，我们将更准确的老师网络的知识转移到提议的轻量级学生网络。我们提出了各种创新技术，以使提出的一级检测器管道的蒸馏效率更高：对象比例蒸馏损失，特征映射非最大抑制和单一统一蒸馏损失函数进行检测。最后，在蒸馏损失的基础上，我们探索利用未标记的数据可以推动性能。我们使用教师网络的软标签对未标记的数据进行训练。我们的最终网络比基于VGG的对象检测网络少10倍的参数，并且它的速度可达到200 FPS以上，并且所提议的改变将Pascal数据集上的基线检测精度提高了14 mAP。

##### URL
[http://arxiv.org/abs/1805.06361](http://arxiv.org/abs/1805.06361)

##### PDF
[http://arxiv.org/pdf/1805.06361](http://arxiv.org/pdf/1805.06361)

