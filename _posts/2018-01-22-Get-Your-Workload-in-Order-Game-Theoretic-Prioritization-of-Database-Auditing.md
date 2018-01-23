---
layout: post
title: "Get Your Workload in Order: Game Theoretic Prioritization of Database Auditing"
date: 2018-01-22 17:42:32
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Detection
author: Chao Yan, Bo Li, Yevgeniy Vorobeychik, Aron Laszka, Daniel Fabbri, Bradley Malin
mathjax: true
---

* content
{:toc}

##### Abstract
For enhancing the privacy protections of databases, where the increasing amount of detailed personal data is stored and processed, multiple mechanisms have been developed, such as audit logging and alert triggers, which notify administrators about suspicious activities; however, the two main limitations in common are: 1) the volume of such alerts is often substantially greater than the capabilities of resource-constrained organizations, and 2) strategic attackers may disguise their actions or carefully choosing which records they touch, making incompetent the statistical detection models. For solving them, we introduce a novel approach to database auditing that explicitly accounts for adversarial behavior by 1) prioritizing the order in which types of alerts are investigated and 2) providing an upper bound on how much resource to allocate for each type. We model the interaction between a database auditor and potential attackers as a Stackelberg game in which the auditor chooses an auditing policy and attackers choose which records to target. A corresponding approach combining linear programming, column generation, and heuristic search is proposed to derive an auditing policy. For testing the policy-searching performance, a publicly available credit card application dataset are adopted, on which it shows that our methods produce high-quality mixed strategies as database audit policies, and our general approach significantly outperforms non-game-theoretic baselines.

##### Abstract (translated by Google)
为了加强数据库的隐私保护，在存储和处理越来越多的详细个人数据的过程中，开发了多种机制，例如审计日志和警报触发器，通知管理员可疑活动;然而，共同的两个主要限制是：1）这种警报的数量往往远远大于资源受限组织的能力; 2）战略攻击者可能掩饰自己的行为或仔细选择他们所触及的记录，使得无能统计检测模型。为了解决这些问题，我们引入了一种新颖的数据库审计方法，通过1）优先考虑警报类型的顺序，2）提供每种类型分配资源的上限。我们将数据库审计师和潜在的攻击者之间的交互作为一个Stackelberg博弈的模型进行建模，在这个博弈中，审计师选择审计策略，攻击者选择哪个记录作为目标。提出了一种结合线性规划，列生成和启发式搜索的相应方法来推导出审计策略。为了测试政策的搜索性能，我们采用了公开的信用卡申请数据集，表明我们的方法产生了高质量的混合策略作为数据库审计策略，我们的一般方法明显优于非博弈论基线。

##### URL
[https://arxiv.org/abs/1801.07215](https://arxiv.org/abs/1801.07215)

##### PDF
[https://arxiv.org/pdf/1801.07215](https://arxiv.org/pdf/1801.07215)

