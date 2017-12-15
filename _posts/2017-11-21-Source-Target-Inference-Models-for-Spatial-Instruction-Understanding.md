---
layout: post
title: "Source-Target Inference Models for Spatial Instruction Understanding"
date: 2017-11-21 16:57:02
categories: arXiv_CL
tags: arXiv_CL Attention Represenation_Learning Inference Classification Prediction
author: Hao Tan, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Models that can execute natural language instructions for situated robotic tasks such as assembly and navigation have several useful applications in homes, offices, and remote scenarios. We study the semantics of spatially-referred configuration and arrangement instructions, based on the challenging Bisk-2016 blank-labeled block dataset. This task involves finding a source block and moving it to the target position (mentioned via a reference block and offset), where the blocks have no names or colors and are just referred to via spatial location features. We present novel models for the subtasks of source block classification and target position regression, based on joint-loss language and spatial-world representation learning, as well as CNN-based and dual attention models to compute the alignment between the world blocks and the instruction phrases. For target position prediction, we compare two inference approaches: annealed sampling via policy gradient versus expectation inference via supervised regression. Our models achieve the new state-of-the-art on this task, with an improvement of 47% on source block accuracy and 22% on target position distance.

##### Abstract (translated by Google)
可以执行自然语言指令的机器人任务模型，例如装配和导航，在家庭，办公室和远程场景中有几个有用的应用。我们研究基于具有挑战性的Bisk-2016空白标记块数据集的空间参考配置和排列指令的语义。这个任务包括找到一个源块并将其移动到目标位置（通过参考块和偏移量提到），其中块没有名称或颜色，并且仅通过空间位置特征来引用。我们提出了基于联合损失语言和空间世界表示学习的源块分类和目标位置回归的子任务的新模型，以及基于CNN和双重注意模型来计算世界块与指令之间的对齐短语。对于目标位置预测，我们比较两种推断方法：通过策略梯度退火采样与通过监督回归的期望推断。我们的模型在这个任务上实现了最新的技术水平，源块精度提高了47％，目标位置距离提高了22％。

##### URL
[https://arxiv.org/abs/1707.03804](https://arxiv.org/abs/1707.03804)

##### PDF
[https://arxiv.org/pdf/1707.03804](https://arxiv.org/pdf/1707.03804)

