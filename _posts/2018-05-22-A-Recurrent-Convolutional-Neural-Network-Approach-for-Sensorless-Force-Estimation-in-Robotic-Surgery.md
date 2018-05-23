---
layout: post
title: "A Recurrent Convolutional Neural Network Approach for Sensorless Force Estimation in Robotic Surgery"
date: 2018-05-22 12:39:24
categories: arXiv_CV
tags: arXiv_CV CNN Memory_Networks
author: Arturo Marban, Vignesh Srinivasan, Wojciech Samek, Josep Fernández, Alicia Casals
mathjax: true
---

* content
{:toc}

##### Abstract
Providing force feedback as relevant information in current Robot-Assisted Minimally Invasive Surgery systems constitutes a technological challenge due to the constraints imposed by the surgical environment. In this context, Sensorless Force Estimation techniques represent a potential solution, enabling to sense the interaction forces between the surgical instruments and soft-tissues. Specifically, if visual feedback is available for observing soft-tissues' deformation, this feedback can be used to estimate the forces applied to these tissues. To this end, a force estimation model, based on Convolutional Neural Networks and Long-Short Term Memory networks, is proposed in this work. This model is designed to process both, the spatiotemporal information present in video sequences and the temporal structure of tool data (the surgical tool-tip trajectory and its grasping status). A series of analyses are carried out to reveal the advantages of the proposal and the challenges that remain for real applications. This research work focuses on two surgical task scenarios, referred to as pushing and pulling tissue. For these two scenarios, different input data modalities and their effect on the force estimation quality are investigated. These input data modalities are tool data, video sequences and a combination of both. The results suggest that the force estimation quality is better when both, the tool data and video sequences, are processed by the neural network model. Moreover, this study reveals the need for a loss function, designed to promote the modeling of smooth and sharp details found in force signals. Finally, the results show that the modeling of forces due to pulling tasks is more challenging than for the simplest pushing actions.

##### Abstract (translated by Google)
在当前的机器人辅助微创手术系统中提供力反馈作为相关信息由于手术环境施加的限制而构成技术挑战。在这种情况下，无传感器力测量技术是一种潜在的解决方案，可以感知手术器械和软组织之间的相互作用力。具体来说，如果视觉反馈可用于观察软组织的变形，则可以使用该反馈来估计施加到这些组织的力。为此，本文提出了一种基于卷积神经网络和长短期记忆网络的力估计模型。该模型设计用于处理视频序列中存在的时空信息和工具数据的时间结构（手术工具尖端轨迹及其抓取状态）。进行了一系列分析以揭示该提案的优点以及实际应用中仍存在的挑战。这项研究工作主要集中在两个手术任务场景，即推拉组织。对于这两种情况，研究了不同的输入数据模态及其对力估计质量的影响。这些输入数据模式是工具数据，视频序列和两者的组合。结果表明，当工具数据和视频序列都由神经网络模型处理时，力估计质量更好。此外，这项研究揭示了对损失函数的需求，旨在促进在力信号中发现的光滑和尖锐细节的建模。最后，结果表明，拉动任务造成的力的建模比最简单的推动行为更具挑战性。

##### URL
[https://arxiv.org/abs/1805.08545](https://arxiv.org/abs/1805.08545)

##### PDF
[https://arxiv.org/pdf/1805.08545](https://arxiv.org/pdf/1805.08545)

