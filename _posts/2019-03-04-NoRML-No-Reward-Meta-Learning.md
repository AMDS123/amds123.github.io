---
layout: post
title: "NoRML: No-Reward Meta Learning"
date: 2019-03-04 04:00:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yuxiang Yang, Ken Caluwaerts, Atil Iscen, Jie Tan, Chelsea Finn
mathjax: true
---

* content
{:toc}

##### Abstract
Efficiently adapting to new environments and changes in dynamics is critical for agents to successfully operate in the real world. Reinforcement learning (RL) based approaches typically rely on external reward feedback for adaptation. However, in many scenarios this reward signal might not be readily available for the target task, or the difference between the environments can be implicit and only observable from the dynamics. To this end, we introduce a method that allows for self-adaptation of learned policies: No-Reward Meta Learning (NoRML). NoRML extends Model Agnostic Meta Learning (MAML) for RL and uses observable dynamics of the environment instead of an explicit reward function in MAML's finetune step. Our method has a more expressive update step than MAML, while maintaining MAML's gradient based foundation. Additionally, in order to allow more targeted exploration, we implement an extension to MAML that effectively disconnects the meta-policy parameters from the fine-tuned policies' parameters. We first study our method on a number of synthetic control problems and then validate our method on common benchmark environments, showing that NoRML outperforms MAML when the dynamics change between tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01063](http://arxiv.org/abs/1903.01063)

##### PDF
[http://arxiv.org/pdf/1903.01063](http://arxiv.org/pdf/1903.01063)

