---
layout: post
title: "Skilled Experience Catalogue: A Skill-Balancing Mechanism for Non-Player Characters using Reinforcement Learning"
date: 2018-06-20 09:41:54
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Reinforcement_Learning
author: Frank G. Glavin, Michael G. Madden
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a skill-balancing mechanism for adversarial non-player characters (NPCs), called Skilled Experience Catalogue (SEC). The objective of this mechanism is to approximately match the skill level of an NPC to an opponent in real-time. We test the technique in the context of a First-Person Shooter (FPS) game. Specifically, the technique adjusts a reinforcement learning NPC's proficiency with a weapon based on its current performance against an opponent. Firstly, a catalogue of experience, in the form of stored learning policies, is built up by playing a series of training games. Once the NPC has been sufficiently trained, the catalogue acts as a timeline of experience with incremental knowledge milestones in the form of stored learning policies. If the NPC is performing poorly, it can jump to a later stage in the learning timeline to be equipped with more informed decision-making. Likewise, if it is performing significantly better than the opponent, it will jump to an earlier stage. The NPC continues to learn in real-time using reinforcement learning but its policy is adjusted, as required, by loading the most suitable milestones for the current circumstances.

##### Abstract (translated by Google)
在本文中，我们介绍了一种针对对手非玩家角色（NPC）的技能平衡机制，称为技能经验目录（SEC）。该机制的目标是实时将NPC的技能水平与对手大致匹配。我们在第一人称射击游戏（FPS）的背景下测试该技术。具体来说，该技术根据对抗对手的当前表现来调整强化学习NPC对武器的熟练度。首先，通过玩一系列训练游戏，以存储学习策略的形式体验一个经验目录。一旦NPC得到了充分的培训，该目录就像是一种以存储学习政策形式的增量知识里程碑为经验的时间表。如果NPC表现不佳，它可以跳到学习时间表的后期阶段，以配备更明智的决策。同样，如果它的表现明显优于对手，则会跳到更早的阶段。全国人大继续使用强化学习实时学习，但其政策根据需要通过加载最适合当前情况的里程碑进行调整。

##### URL
[http://arxiv.org/abs/1806.07637](http://arxiv.org/abs/1806.07637)

##### PDF
[http://arxiv.org/pdf/1806.07637](http://arxiv.org/pdf/1806.07637)

