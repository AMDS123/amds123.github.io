---
layout: post
title: "Features, Projections, and Representation Change for Generalized Planning"
date: 2018-01-30 15:32:02
categories: arXiv_AI
tags: arXiv_AI Relation
author: Blai Bonet, Hector Geffner
mathjax: true
---

* content
{:toc}

##### Abstract
Generalized planning is concerned with the characterization and computation of plans that solve many instances at once. In the standard formulation, a generalized plan is a mapping from feature or observation histories into actions, assuming that the instances share a common pool of features and actions. This assumption, however, excludes the standard relational planning domains where actions and objects change across instances. In this work, we extend the formulation of generalized planning to such domains. This is achieved by projecting the actions over the features, resulting in a common set of abstract actions which can be tested for soundness and completeness, and which can be used for generating general policies such as "if the gripper is empty, pick the clear block above x and place it on the table" that achieve the goal clear(x) in any Blocksworld instance. In this policy, "pick the clear block above x" is an abstract action that may represent the action Unstack(a, b) in one situation and the action Unstack(b, c) in another. Transformations are also introduced for computing such policies by means of fully observable non-deterministic (FOND) planners. The value of generalized representations for learning general policies is also discussed.

##### Abstract (translated by Google)
通用计划涉及一次解决多个实例的计划的表征和计算。在标准的表述中，一个概括的计划是从特征或观察历史到行动的映射，假设这些实例共享一组共同的特征和行为。然而，这种假设排除了动作和对象跨实例更改的标准关系规划域。在这项工作中，我们将广义计划的制定扩展到这些领域。这是通过将动作投影到特征上来实现的，从而产生一组通用的抽象动作，这些抽象动作可以被测试的正确性和完整性，并且可以用于产生一般的策略，例如“如果抓取器是空的，选择清除块上面的x并放在桌面上“，在任何Blocksworld实例中实现clear（x）目标。在这个策略中，“选择上面的清除块”是一个抽象的动作，可以表示一个情况下的动作Unstack（a，b），另一个动作是Unstack（b，c）。通过完全可观察的非确定性（FOND）规划者，还引入了转换来计算这些策略。还讨论了学习一般政策的广义表征的价值。

##### URL
[http://arxiv.org/abs/1801.10055](http://arxiv.org/abs/1801.10055)

##### PDF
[http://arxiv.org/pdf/1801.10055](http://arxiv.org/pdf/1801.10055)

