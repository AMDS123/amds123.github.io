---
layout: post
title: "Online Action Detection in Untrimmed, Streaming Videos - Modeling and Evaluation"
date: 2018-02-19 19:39:05
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Detection
author: Zheng Shou, Junting Pan, Jonathan Chan, Kazuyuki Miyazawa, Hassan Mansour, Anthony Vetro, Xavier Giro-i-Nieto, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of Online Action Detection (OAD) is to detect action in a timely manner and to recognize its action category. Early works focused on early action detection, which is effectively formulated as a classification problem instead of online detection in streaming videos, because these works used partially seen short video clip that begins at the start of action. Recently, researchers started to tackle the OAD problem in the challenging setting of untrimmed, streaming videos that contain substantial background shots. However, they evaluate OAD in terms of per-frame labeling, which does not require detection at the instance-level and does not evaluate the timeliness of the online detection process. In this paper, we design new protocols and metrics. Further, to specifically address challenges of OAD in untrimmed, streaming videos, we propose three novel methods: (1) we design a hard negative samples generation module based on Generative Adversarial Network (GAN) framework to better distinguish ambiguous background shots that share similar scenes but lack true characteristics of action start; (2) during training we impose a temporal consistency constraint between data around action start and data succeeding action start to model their similarity; (3) we introduce an adaptive sampling strategy to handle the scarcity of the important training data around action start. We conduct extensive experiments using THUMOS'14 and ActivityNet. We show that our proposed strategies lead to significant performance gains and improve state-of-the-art results. A systematic ablation study also confirms the effectiveness of each proposed method.

##### Abstract (translated by Google)
在线行为检测（OAD）的目标是及时发现行为并识别其行为类别。早期的作品集中于早期行为检测，它被有效地表述为分类问题，而不是在流式视频中进行在线检测，因为这些作品使用了部分可见的短视频剪辑，该视频剪辑始于行动开始。最近，研究人员开始在包含大量背景镜头的未修剪流式视频的具有挑战性的环境中解决OAD问题。然而，他们根据每帧标签评估OAD，不需要在实例级检测，也不评估在线检测过程的及时性。在本文中，我们设计了新的协议和指标。此外，为了具体解决未修剪流媒体视频中的OAD挑战，我们提出了三种新颖的方法：（1）基于生成对抗网络（GAN）框架设计硬阴图样本生成模块，以更好地区分共享相似场景的模糊背景镜头但缺乏行动开始的真实特征; （2）在训练过程中，我们在动作开始的数据和动作开始的数据之间施加时间一致性约束，以模拟它们的相似性; （3）我们引入适应性抽样策略来处理围绕行动开始的重要训练数据的稀缺性。我们使用THUMOS'14和ActivityNet进行广泛的实验。我们表明，我们提出的战略可以显着提高绩效并改善最新的结果。系统性消融研究也证实了每种方法的有效性。

##### URL
[http://arxiv.org/abs/1802.06822](http://arxiv.org/abs/1802.06822)

##### PDF
[http://arxiv.org/pdf/1802.06822](http://arxiv.org/pdf/1802.06822)

