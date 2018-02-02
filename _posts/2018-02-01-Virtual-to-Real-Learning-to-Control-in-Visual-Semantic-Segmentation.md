---
layout: post
title: "Virtual-to-Real: Learning to Control in Visual Semantic Segmentation"
date: 2018-02-01 13:52:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning Semantic_Segmentation
author: Zhang-Wei Hong, Chen Yu-Ming, Shih-Yang Su, Tzu-Yun Shann, Yi-Hsiang Chang, Hsuan-Kung Yang, Brian Hsi-Lin Ho, Chih-Chieh Tu, Yueh-Chuan Chang, Tsu-Ching Hsiao, Hsin-Wei Hsiao, Sih-Pin Lai, Chun-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Collecting training data from the physical world is usually time-consuming and even dangerous for fragile robots, and thus, recent advances in robot learning advocate the use of simulators as the training platform. Unfortunately, the reality gap between synthetic and real visual data prohibits direct migration of the models trained in virtual worlds to the real world. This paper proposes a modular architecture for tackling the virtual-to-real problem. The proposed architecture separates the learning model into a perception module and a control policy module, and uses semantic image segmentation as the meta representation for relating these two modules. The perception module translates the perceived RGB image to semantic image segmentation. The control policy module is implemented as a deep reinforcement learning agent, which performs actions based on the translated image segmentation. Our architecture is evaluated in an obstacle avoidance task and a target following task. Experimental results show that our architecture significantly outperforms all of the baseline methods in both virtual and real environments, and demonstrates a faster learning curve than them. We also present a detailed analysis for a variety of variant configurations, and validate the transferability of our modular architecture.

##### Abstract (translated by Google)
从现实世界中收集训练数据对于脆弱的机器人来说通常是耗时的，甚至是危险的，因此近来机器人学习的进展主张使用模拟器作为训练平台。不幸的是，合成视觉数据和真实视觉数据之间的现实差距阻碍了在虚拟世界中训练的模型直接迁移到现实世界。本文提出了一个解决虚拟到现实问题的模块化架构。所提出的体系结构将学习模型分为感知模块和控制策略模块，并将语义图像分割作为将这两个模块相关联的元表示。感知模块将感知的RGB图像转换为语义图像分割。控制策略模块被实现为深度强化学习代理，其基于翻译图像分割来执行动作。我们的架构被评估为避障任务和目标跟随任务。实验结果表明，我们的体系结构在虚拟环境和真实环境中显着优于所有的基准方法，并且展现出比他们更快的学习曲线。我们还提供了各种不同配置的详细分析，并验证了模块化体系结构的可转移性。

##### URL
[http://arxiv.org/abs/1802.00285](http://arxiv.org/abs/1802.00285)

##### PDF
[http://arxiv.org/pdf/1802.00285](http://arxiv.org/pdf/1802.00285)

