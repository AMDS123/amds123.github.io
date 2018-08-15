---
layout: post
title: "An Optimal Policy for Patient Laboratory Tests in Intensive Care Units"
date: 2018-08-14 13:34:06
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Li-Fang Cheng, Niranjani Prasad, Barbara E Engelhardt
mathjax: true
---

* content
{:toc}

##### Abstract
Laboratory testing is an integral tool in the management of patient care in hospitals, particularly in intensive care units (ICUs). There exists an inherent trade-off in the selection and timing of lab tests between considerations of the expected utility in clinical decision-making of a given test at a specific time, and the associated cost or risk it poses to the patient. In this work, we introduce a framework that learns policies for ordering lab tests which optimizes for this trade-off. Our approach uses batch off-policy reinforcement learning with a composite reward function based on clinical imperatives, applied to data that include examples of clinicians ordering labs for patients. To this end, we develop and extend principles of Pareto optimality to improve the selection of actions based on multiple reward function components while respecting typical procedural considerations and prioritization of clinical goals in the ICU. Our experiments show that we can estimate a policy that reduces the frequency of lab tests and optimizes timing to minimize information redundancy. We also find that the estimated policies typically suggest ordering lab tests well ahead of critical onsets--such as mechanical ventilation or dialysis--that depend on the lab results. We evaluate our approach by quantifying how these policies may initiate earlier onset of treatment.

##### Abstract (translated by Google)
实验室检测是医院患者护理管理中不可或缺的工具，特别是在重症监护病房（ICU）。在特定时间给定测试的临床决策中的预期效用的考虑与其对患者相关的成本或风险之间存在实验室测试的选择和时间的固有权衡。在这项工作中，我们引入了一个框架，该框架学习订购实验室测试的策略，以优化这种权衡。我们的方法使用基于临床要求的批量非政策强化学习和复合奖励功能，应用于包括临床医生为患者订购实验室的实例的数据。为此，我们开发和扩展帕累托最优性原则，以改进基于多个奖励功能组件的行动选择，同时尊重ICU中典型的程序考虑和临床目标的优先级。我们的实验表明，我们可以估算出一种策略，可以降低实验室测试的频率，并优化时序以最大限度地减少信息冗余我们还发现，估计的政策通常建议在实际结果之前订购实验室测试，例如机械通气或透析 - 这取决于实验室结果。我们通过量化这些政策如何开始早期治疗来评估我们的方法。

##### URL
[http://arxiv.org/abs/1808.04679](http://arxiv.org/abs/1808.04679)

##### PDF
[http://arxiv.org/pdf/1808.04679](http://arxiv.org/pdf/1808.04679)

